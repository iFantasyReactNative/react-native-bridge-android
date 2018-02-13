
# react-native-my-android-toast

## Getting started

`$ npm install react-native-my-android-toast --save`

### Mostly automatic installation

`$ react-native link react-native-my-android-toast`

### Manual installation


#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNMyAndroidToastPackage;` to the imports at the top of the file
  - Add `new RNMyAndroidToastPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-my-android-toast'
  	project(':react-native-my-android-toast').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-my-android-toast/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-my-android-toast')
  	```


## Usage
```javascript
import RNMyAndroidToast from 'react-native-my-android-toast';

// TODO: What to do with the module?
RNMyAndroidToast;
```
  