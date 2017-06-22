
# react-native-brightcove-bridge

## Getting started

`$ npm install react-native-brightcove-bridge --save`

### Mostly automatic installation

`$ react-native link react-native-brightcove-bridge`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-brightcove-bridge` and add `RNBrightcoveBridge.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNBrightcoveBridge.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNBrightcoveBridgePackage;` to the imports at the top of the file
  - Add `new RNBrightcoveBridgePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-brightcove-bridge'
  	project(':react-native-brightcove-bridge').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-brightcove-bridge/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-brightcove-bridge')
  	```

## Usage
```javascript
import RNBrightcoveBridge from 'react-native-brightcove-bridge';

// TODO: What to do with the module?
RNBrightcoveBridge;
```
