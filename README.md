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
│   │  ├── Colors.js
│   │  ├── GlobalStyle.js
│   ├── utility
│   │  ├── index.js
```
## api/
<p>This folder contains logic related to external API communications</p>

## assets/
<p>This folder will store all the assets that we are using in react-native. You can add static files like fonts and images to it. Also, you can add more assets like videos in this folder according to your project requirements.</p>

## components/
<p>In this folder, we create all the React components that will be part of our app and any custom component that we create during the app’s development. We can group components by features or places they will be used and components that will be used throughout our app, like buttons or texts.</p>

## constants/
<p></p>

## hooks/
<p>If you have custom hooks defined in your project you can put it over here that can be shared across your entire project.</p>

## navigation/
<p></p>

## redux/
<p></p>

## screens/
<p></p>

## styles/
<p>If you have global styles defined in your project you can put it over here like colors, font styles like things.</p>

## utility/
<p></p>