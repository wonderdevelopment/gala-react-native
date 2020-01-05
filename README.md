# Gala – bootstrap react native template

Inside you will found more than 13 screens for creating your application.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
Dowload package unzip go to dir

### Prerequisites

For running and installation Gala you need 

Install [Node.js](https://nodejs.org/en/download/) on your local machine.

[NPM](https://www.npmjs.com/get-npm) or [Yarn](https://yarnpkg.com/lang/en/docs/install/) manager 

```
$ brew install node

$ brew install yarn

$ yarn global add expo-cli
```

### Installing


1. Go to Gala directory ```cd gala_expo_35```
2. Install packages ```yarn install```                   
3. Run Expo Gala ```yarn start``` 


## Coding style tests

For test run ```yarn test``` 

## Built With npm packages:

* [@expo/vector-icons](https://github.com/expo/vector-icons) - Vector icons library for expo
* [@react-navigation/web](https://reactnavigation.org/docs/en/web-support.html) - React Navigation on the Web
* [expo](https://expo.io/) - Build, deploy, and iterate on native Android, iOS from the same JavaScript codebase.
* [expo-asset](https://docs.expo.io/versions/latest/sdk/asset/) - Provides an interface to Expo's asset system. 
* [expo-constants](https://docs.expo.io/versions/latest/sdk/constants/) - Expo constants
* [expo-web-browser](https://docs.expo.io/versions/latest/sdk/constants/) - Expo web browser
* [expo-font](https://docs.expo.io/versions/latest/guides/using-custom-fonts/) - Adding a custom font to your Expo app
* [react](https://reactjs.org/) - A JavaScript library for building user interfaces
* [react-dom](https://www.npmjs.com/package/react-dom) - Serves as the entry point to the DOM
* [react-native](https://facebook.github.io/react-native/) - A framework for building native apps with React.
* [react-native-app-intro-slider](https://www.npmjs.com/package/react-native-app-intro-slider) - introduction slider/swiper based on FlatList
* [react-native-calendars](https://www.npmjs.com/package/react-native-calendars) - Various customizable react native calendar components.
* [react-native-elements](https://react-native-elements.github.io/react-native-elements/) - Cross Platform React Native UI Toolkit.
* [react-native-form-validation](https://www.npmjs.com/package/react-native-form-validation) - Simple JS component for validating forms.
* [react-native-gesture-handler](https://www.npmjs.com/package/react-native-gesture-handler) - Provides native-driven gesture management APIs.
* [react-native-progress-circle](https://www.npmjs.com/package/react-native-progress-circle) - React Native Progress Circle.
* [react-native-reanimated](https://www.npmjs.com/package/react-native-reanimated) - React Native's Animated library reimplemented.
* [react-native-safe-area-view](https://www.npmjs.com/package/react-native-safe-area-view) - Provides automatic padding when a view intersects with a safe area
* [react-native-svg](https://www.npmjs.com/package/react-native-svg) - Provides SVG support to React Native on iOS and Android
* [react-native-svg-uri](https://www.npmjs.com/package/react-native-svg-uri) - Render SVG images in React Native from an URL or a static file
* [react-native-web](https://www.npmjs.com/package/react-native-web) - Brings the platform-agnostic Components and APIs of React Native to the Web
* [react-navigation](https://reactnavigation.org/) - Routing and navigation for your React Native apps
* [react-navigation-drawer](https://www.npmjs.com/package/react-navigation-drawer) - Drawer navigator for use on iOS and Android
* [react-native-gesture-handler](https://www.npmjs.com/package/react-native-gesture-handler) - Declarative API exposing platform native touch and gesture system to React Native.


## File structure

├── App.js
├── __tests__
│   ├── App-test.js
│   └── __snapshots__
│       └── App-test.js.snap
├── app.json
├── assets
│   ├── fonts
│   │   ├── Lato-Black.ttf
│   │   ├── Lato-Bold.ttf
│   │   ├── Lato-Light.ttf
│   │   ├── Lato-Regular.ttf
│   │   └── Lato-Thin.ttf
│   └── images
│       ├── icon.png
│       ├── png
│       │   ├── ava.png
│       │   ├── ava2.png
│       │   ├── image1.png
│       │   ├── image10.jpg
│       │   ├── image2.png
│       │   ├── image3.png
│       │   ├── image4.png
│       │   ├── image5.png
│       │   ├── image6.png
│       │   ├── image7.png
│       │   ├── image8.png
│       │   └── image9.png
│       ├── splash.png
│       └── svg
│           ├── black
│           │   ├── back-arrow.svg
│           │   ├── bookmark.svg
│           │   ├── close.svg
│           │   ├── comment.svg
│           │   ├── download.svg
│           │   ├── grid.svg
│           │   ├── letter.svg
│           │   ├── letters.svg
│           │   ├── lock.svg
│           │   ├── menu.svg
│           │   ├── news.svg
│           │   ├── setting.svg
│           │   ├── stats.svg
│           │   ├── time.svg
│           │   ├── user-2.svg
│           │   └── user.svg
│           ├── color
│           │   ├── check.svg
│           │   ├── light.svg
│           │   ├── news.svg
│           │   └── sound.svg
│           ├── gray
│           │   ├── bookmark.svg
│           │   ├── check.svg
│           │   ├── comment.svg
│           │   ├── heart.svg
│           │   ├── mail.svg
│           │   ├── share.svg
│           │   ├── time.svg
│           │   └── user.svg
│           └── white
│               ├── arrow_back.svg
│               ├── download.svg
│               ├── letter.svg
│               ├── menu.svg
│               ├── phone.svg
│               ├── pin.svg
│               ├── settings.svg
│               └── upload.svg
├── babel.config.js
├── components
│   ├── ButtonGroupArticle.js
│   ├── ButtonGroupIconTabs.js
│   ├── ButtonGroupTabs.js
│   ├── Header.js
│   ├── SmartForm.js
│   ├── StyledText.js
│   ├── TabBarIcon.js
│   └── __tests__
│       ├── StyledText-test.js
│       └── __snapshots__
│           └── StyledText-test.js.snap
├── constants
│   ├── Bootstrap.js
│   ├── Colors.js
│   ├── Layout.js
│   └── Theme.js
├── navigation
│   ├── AppNavigator.js
│   └── DrawerNavigator.js
├── package.json
├── screens
│   ├── ArticleScreen.js
│   ├── CreateAccountScreen.js
│   ├── FeedChannelScreen.js
│   ├── FeedScreen.js
│   ├── FeedbackScreen.js
│   ├── ForgotPasswordScreen.js
│   ├── IntroScreen.js
│   ├── LoginScreen.js
│   ├── ProfileCalendarScreen.js
│   ├── ProfileDashboardScreen.js
│   ├── ProfileScreen.js
│   ├── ProfileSettingsScreen.js
│   └── ProfileTimelineScreen.js
└── yarn.lock


### - App.js

Main initialisation app file

1) App loader, while app loading  

```
if (!this.state.isLoadingComplete && !this.props.skipLoadingScreen) {
  return (
      <AppLoading
        startAsync={this._loadResourcesAsync}
        onError={this._handleLoadingError}
        onFinish={this._handleFinishLoading}
      />
  );
}
``` 

2) Async Font loading function. Here you can change path to your fonts 
```
_loadResourcesAsync = async () => {
    return Promise.all([
      Asset.loadAsync([
        require("./assets/images/robot-dev.png"),
        require("./assets/images/robot-prod.png")
      ]),
      Font.loadAsync({
        // This is the font that we are using for our tab bar
        ...Icon.Ionicons.font,
        // We include SpaceMono because we use it in DeliveryAddressScreen.js. Feel free
        // to remove this if you are not using it in your app
        "space-mono": require("./assets/fonts/SpaceMono-Regular.ttf"),
        "work-sans": require("./assets/fonts/WorkSans-Regular.ttf"),
        "work-sans-bold": require("./assets/fonts/WorkSans-Bold.ttf"),
        "work-sans-semibold": require("./assets/fonts/WorkSans-SemiBold.ttf")
      })
    ]);
};
``` 

3) Initial screen with calling Navigator component from /navigation/AppNavigator
```
<View style={styles.container}>
    {Platform.OS === "ios" && <StatusBar barStyle="default" />}
    <AppNavigator />
</View>
```

    


### - app.json

Expo configuration file. Here you can set path to app icon, change name and description for expo repo.


### - package.json

Configuration file with js packages

### - assets 
All assets: fonts, images etc.

#### -- fonts

Custom local fonts location

#### -- images

Images location

### - components

Custom components for screens, like buttons and badges

### - constants

Colors, Sizes, Layouts Constants for template customizing. Include Bootstrap.js file with classes with flex alighnmensts, postitions, borders, text sizes, paddings and margins. 

### - navigation

Navigation files: for bottom tab navigator, Auth navigation and Main navigation

### - screens

All screens witch uses in app

## Contributing

For Contributing please email: yes@wonder.network
 
## Authors

* [**Wonder Network**](https://wonder.network)


## License

This project is licensed under commercial license 

## Acknowledgments

* Happy coding !
