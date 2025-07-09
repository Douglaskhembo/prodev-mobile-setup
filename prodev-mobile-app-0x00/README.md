# 📱 Task 1: Create Your First Mobile App

## 🎯 Objective

Set up the first mobile application using the **Expo Router template**, understand the structure, modify the home screen, and reset the app structure using the provided script.

## 🛠️ Setup Process

1. Navigated to the project directory:

```bash
cd prodev-mobile-setup/prodev-mobile-app-0x00
```

2. Scaffolded a new Expo app using Expo Router template:

```bash
npx create-expo-app@latest .
```

- Chose the default Expo Router template.
- Installation completed successfully with some npm deprecation warnings:
  - inflight@1.0.6
  - rimraf@3.0.2
  - glob@7.2.3
- No critical errors encountered during setup.

3. Started the development server:

```bash
npx expo start
```

- Metro Bundler started at: `exp://192.168.1.110:8081`
- Scanned the QR code using the Expo Go app on Android.
- The app launched successfully on the device.

## ✏️ Modified Home Screen

- Opened: `app/(tabs)/index.tsx`
- Replaced the default `Text` component content from `"Welcome!"` to:

```tsx
<Text>** First App Created **</Text>
```

- Saved and reloaded the app.
- Confirmed that the change reflected in the running app.

## 🔄 Reset Project

4. Ran the reset script to clean and restructure the project:

```bash
npm run reset-project
```

- Prompted: `Do you want to move existing files to /app-example instead of deleting them? (Y/n): y`
- Responded: `y`

### Reset Observations:

- A new backup directory `/app-example` was created.
- The following were moved into it:
  - `app/`
  - `components/`
  - `hooks/`
  - `constants/`
  - `scripts/`
- A fresh `/app` directory was generated containing:
  - `app/index.tsx`
  - `app/_layout.tsx`

