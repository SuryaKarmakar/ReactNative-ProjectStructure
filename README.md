# React Native Project Folder And File Structure

## Basic Folder Structure :

```
├── src
│   ├── api
│   ├── assets
│   │  ├── fonts
│   │  ├── images
│   ├── components
│   │  ├── common
│   │  ├── presentation
│   ├── constants
│   ├── hooks
│   ├── navigation
│   ├── redux
│   │  ├── actions
│   │  ├── constants
│   │  ├── reducers
│   ├── screens
│   │  ├── homeScreen
│   │  ├── aboutScreen
│   ├── styles
│   ├── utility
```

## Folder With File Structure :

```
├── src
│   ├── api
│   │  ├── ApiCalls.js
│   │  ├── EndUrls.js
│   │  ├── index.js
│   ├── assets
│   │  ├── fonts
│   │  │  ├── font-name1.ttf
│   │  │  ├── font-name2.ttf
│   │  ├── images
│   │  │  ├── icon1.png
│   │  │  ├── icon2.png
│   ├── components
│   │  ├── common
│   │  │  ├── customButtonRN
│   │  │  │  ├── index.js
│   │  │  │  ├── styles.js
│   │  │  ├── customTextRN
│   │  │  │  ├── index.js
│   │  │  │  ├── styles.js
│   │  ├── presentation
│   │  │  ├── buttonRN
│   │  │  │  ├── index.js
│   │  │  │  ├── styles.js
│   │  │  ├── textRN
│   │  │  │  ├── index.js
│   │  │  │  ├── styles.js
│   ├── constants
│   │  │  ├── Enums.js
│   │  │  ├── Fonts.js
│   │  │  ├── Images.js
│   │  │  ├── ScreenNames.js
│   │  │  ├── StorageKeys.js
│   │  │  ├── Strings.js
│   │  │  ├── Colors.js
│   ├── hooks
│   │  │  ├── index.js
│   ├── navigation
│   │  │  ├── AppNavigator.js
│   │  │  ├── AuthNavigator.js
│   │  │  ├── TabNavigator.js
│   ├── redux
│   │  ├── actions
│   │  │  ├── Action1.js
│   │  │  ├── Action2.js
│   │  ├── constants
│   │  │  ├── Constants1.js
│   │  │  ├── Constants1.js
│   │  ├── reducers
│   │  │  ├── Reducer1.js
│   │  │  ├── Reducer2.js
│   │  ├── store.js
│   ├── screens
│   │  ├── homeScreen
│   │  │  ├── index.js
│   │  │  ├── styles.js
│   │  ├── aboutScreen
│   │  │  ├── index.js
│   │  │  ├── styles.js
│   ├── styles
│   │  ├── GlobalStyle.js
│   ├── utility
│   │  ├── index.js
```

## api/

This folder contains logic related to external API communications.

## assets/

This folder will store all the assets that we are using in react-native. You can add static files like fonts and images to it. Also, you can add more assets like videos in this folder according to your project requirements.

- **fonts/**
- **images/**

## components/

In this folder, we create all the React components that will be part of our app and any custom component that we create during the app’s development. We can group components by features or places they will be used and components that will be used throughout our app, like buttons or texts.

- **common/**
- **presentation/**

## constants/

This folder contains all the string related file.

## hooks/

If you have custom hooks defined in your project you can put it over here that can be shared across your entire project.

## navigation/

Your project base navigation goes here. You can create a stack navigator in it and export it to your application.

## redux/

This folder holds all the redux files if you are using react-redux for managing state. Inside redux folder you have actions, reducers, store which can easily manage your redux files.

- **actions/**
- **constants/**
- **reducers/**

## screens/

If you have multiple screens like auth screens: login, register and profile screens, product screens it can be saved here.

## styles/

If you have global styles defined in your project you can put it over here like colors, font styles like things.

## utility/

All the utils/helpers files go here that storing reusable methods and logic like validations, progress bar, date pickers, and according to your app requirements.
