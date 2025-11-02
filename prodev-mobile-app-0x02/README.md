# Task 3: Safe Areas, Images, and Touchable Components

## ✅ Setup
- Initialized new Expo Router project: `npx create-expo-app@latest prodev-mobile-app-0x02 --template with-router`
- Reset default template using `npm run reset-project`
- Moved assets to `assets/images`

## 🧱 Component Implementation
- Used `SafeAreaProvider` and `SafeAreaView` to protect layout from notches
- Applied full-screen background using `ImageBackground` and `Dimensions`
- Displayed logo with `Image`
- Added styled text blocks and interactive buttons using `TouchableOpacity`

## 🎨 Styling
- Background: `#90caf9`
- Buttons: white and transparent variants
- Text: large title + two small lines
- Navigation prompt: “Continue to home” at bottom

## 📱 Testing
- App launched successfully in Expo Go
- All components rendered correctly on Android emulator