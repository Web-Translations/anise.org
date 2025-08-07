# Anise Dev Setup

These are brief instructions for getting started after importing the projects development repo - for @AlexeyDemidov.

---

## 1. `aniseProject` – React Native Frontend

This is the mobile app built with React Native using Expo.

### Setup:
1. Run `npm install` to install dependencies.
2. Open `src/utils/api.ts` and set it to point to your **development server URL**.
3. Start the app with:
   ```bash
   npx expo start
   ```
   This will launch an Expo Go server. You can test the app on your mobile device using the **Expo Go app**, as long as the backend server is running.

---

## 2. `aniseBackend` – Backend Server

This is the backend that powers the mobile app.

### Setup:
1. Run `npm install`.
2. Create a `.env` file – the required variables are listed in the folder's README.
3. Start the server:
   ```bash
   npm run dev
   ```

> If you're looking to use the **Firebase setup** that Will and I were using, ping me directly for details. Otherwise, follow standard Firebase configuration practices.

---

## 3. `aniseContracts` – Smart Contracts

Contains Solidity contracts, tests, and deployment scripts using **Hardhat**.

### Notes:
- No setup required unless you're redeploying contracts.
- Current contracts are already deployed to **Amoy**.
- Frontend is up to date with the latest deployed contract addresses.

---

If you have any questions or run into issues, feel free to message me -> nwalsh03@icloud.com
