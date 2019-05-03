
# react-native-in-app-purchase-android

## Getting started

`$ npm install react-native-in-app-purchase-android --save`

### Mostly automatic installation

`$ react-native link react-native-in-app-purchase-android`

### Manual installation


#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNInAppPurchaseAndroidPackage;` to the imports at the top of the file
  - Add `new RNInAppPurchaseAndroidPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-in-app-purchase-android'
  	project(':react-native-in-app-purchase-android').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-in-app-purchase-android/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-in-app-purchase-android')
  	```


## Usage
```javascript
import RNInAppPurchaseAndroid from 'react-native-in-app-purchase-android';

// TODO: What to do with the module?
RNInAppPurchaseAndroid;
```
  