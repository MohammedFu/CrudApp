# CrudApp

CrudApp is a cross-platform mobile application built using React Native and Expo.

## 🚀 Tech Stack
- **Framework:** React Native, Expo
- **Routing:** Expo Router (File-based routing)
- **Language:** TypeScript
- **UI/Styling:** React Native Web, Expo Vector Icons
- **Animations:** React Native Reanimated, Gesture Handler

## 🛠️ Project Setup

1. **Prerequisites**
   - Node.js installed on your machine
   - `npm` or `yarn` package manager
   - Expo Go app installed on your physical device (for testing), or an Android Emulator/iOS Simulator set up on your machine.

2. **Installation**
   Clone the repository, navigate to the directory, and install dependencies:
   ```bash
   npm install
   ```

3. **Running the App**
   Start the Expo development server:
   ```bash
   npx expo start
   ```
   - Press `a` to open the app on an Android Emulator.
   - Press `i` to open the app on an iOS Simulator.
   - Scan the QR code shown in the terminal using the Expo Go app on your mobile device.

## 📡 API Details

*(Note: These are placeholder API details. Please update them to reflect your actual backend configuration.)*

- **Base URL:** `http://localhost:8000/api`
- **Endpoints:**
  - `GET /items` - Retrieve a list of items.
  - `GET /items/{id}` - Retrieve a single item by ID.
  - `POST /items` - Create a new item.
  - `PUT /items/{id}` - Update an existing item.
  - `DELETE /items/{id}` - Delete an item.

## 📂 Project Structure
- `app/` - Application screens and routes (managed by Expo Router).
- `assets/` - Static assets like images and fonts.
- `components/` - Reusable UI components.
- `constants/` - App-wide constants (e.g., colors, layout sizing).
- `hooks/` - Custom React hooks for shared logic.
- `scripts/` - Helpful utility scripts.
