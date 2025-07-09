#  Task 0: Mobile Development Environment Setup

##  Setup Process

1. **Installed Node.js LTS (v18.x):**
   - Verified with: `node -v` → Output: `v18.x.x`
2. **Installed npm (Node Package Manager):**
   - Verified with: `npm -v` → Output: `8.x.x` or higher
3. **Installed VS Code** as the primary code editor.
4. **Installed Expo Go on a physical device (Android):**
   - Downloaded from [Google Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent)
   - Signed in with an Expo account.
5. **Switched from legacy Expo CLI to modern CLI:**
   - Removed legacy `expo-cli` due to compatibility issues with Node.js 17+.
   - Confirmed removal using `which expo`
   - Used `npx create-expo-app` for app scaffolding going forward.


##  Challenges Faced

-  **Deprecated Warnings** during `expo-cli` installation (e.g., `uuid@3.4.0`, `rimraf@2.x`, etc.).
-  **Compatibility Issue:** `expo-cli` warned that Node.js v17+ is unsupported.
-  **Solution:** Uninstalled `expo-cli` globally and switched to the modern Expo CLI using `npx`.
- **Cleanup:** Verified that `expo` binary was removed from system PATH using `which expo`.

