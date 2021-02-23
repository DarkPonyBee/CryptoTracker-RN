# CryptoTracker App

Simple React Native Mobile Application for CryptoTracker

Tech stack : React Native + Redux + Redux Thunk + ReactNavigation + TypeScript

## Dev Setup

### Getting started

If you are new to the React native, please follow the instructions [Getting Started](https://reactnative.dev/docs/environment-setup)

It is a good material to the React native newbies.

### Running Locally

#### Install dependencies:

From the project root, run the following command.

```
npm install

```

Or if you prefer `yarn`:

```
yarn

```

#### Install cocoapods:

This installation is for iOS development.

```
cd ios && pod install

```

#### Run android app:

```
npm run android

```

```
yarn android

```

#### Run iOS app:

```
npm run ios

```

```
yarn ios

```

## Scripts

- `npm run lint` or `yarn lint` - For linting.
- `npm run test` or `yarn test` - For testing app.
- `npm run ios` or `yarn ios` - For building and running app on iOS simulator.
- `npm run android` or `yarn andrid` - For building and running app on Android emulator.

#### Editor

We use Visual Studio Code (Insiders) for IDE. And our project followed Eslint rule. No need to instally any npm packages, only run `npm install` or `yarn` command. Plus, please install ESLint, Prettier Plugin (VS Code extension) to keep the better code and auto-formatting, auto-linting while code editing.

## Features

- Typescript support.
- Consists of Functional component and React Hooks.
- Used Redux, Redux Thunk for state management.
- Used axios for api call (REST API client).
- Screen navigation with React Navigation v5.
- Code linting and formatting with ESLint & Prettier.
