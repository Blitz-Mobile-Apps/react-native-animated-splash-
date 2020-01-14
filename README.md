
# react-native-animated-splash

## Getting started

`$ npm install react-native-animated-splash --save`

### Mostly automatic installation

`$ react-native link react-native-animated-splash`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-animated-splash` and add `RNAnimatedSplash.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNAnimatedSplash.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNAnimatedSplashPackage;` to the imports at the top of the file
  - Add `new RNAnimatedSplashPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-animated-splash'
  	project(':react-native-animated-splash').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-animated-splash/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-animated-splash')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNAnimatedSplash.sln` in `node_modules/react-native-animated-splash/windows/RNAnimatedSplash.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Animated.Splash.RNAnimatedSplash;` to the usings at the top of the file
  - Add `new RNAnimatedSplashPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNAnimatedSplash from 'react-native-animated-splash';

// TODO: What to do with the module?
RNAnimatedSplash;
```
  