# sandbox-rn

## Overview

[React Native](https://reactnative.dev/) Sandbox, created with `npx react-native init`.

### Getting Started

```bash
nvm use
yarn install
bundle install
cd macos
bundle exec pod install
```

### Android

Have an Android emulator running.

```bash
npx react-native run-android
```

### iOS

```bash
npx react-native run-ios --project-path './macos' --scheme='sandbox-iOS' --simulator='iPhone 8'
```

### MacOS

```bash
npx react-native run-macos
```

### Testing

```bash
npm run test
```
