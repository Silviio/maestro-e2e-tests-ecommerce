# Maestro E2E Tests for Ecommerce

This repository contains end-to-end UI tests for a mobile ecommerce app using Maestro.

## Structure

- `flows/` — Maestro flow definitions
- `shopdemo/` — sample ecommerce app used for testing
- `ShopDemo.apk` — Android build used for local test runs

## Prerequisites

- Node.js and npm
- Android emulator or device
- Maestro installed

## Setup

1. Install the app dependencies:
   ```bash
   cd shopdemo
   npm install
   ```

2. Start the app locally (optional if using the provided APK):
   ```bash
   cd shopdemo
   npm start
   ```

3. Run a Maestro flow:
   ```bash
   maestro test flows/s3-suite-shopdemo/e2e-purchase-flow.yaml
   ```

## Notes

- The flows are designed to exercise the purchase journey end to end.
- You can add new flows under the `flows/` folder.
