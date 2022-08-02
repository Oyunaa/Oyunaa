Information 
React native custom font-family

1. Download custom font family
2. Rename your font like this Nutito-Regular, Nutito-Bold
3. Install font and get postscript name to use font in your code
4. Create folder "assets/fonts" and copy fonts to this folder 
5. Create file "react-native.config.js"
    module.exports = {
      project: {
        ios: {},
        android: {},
      },
      assets: ['./assets/fonts/'],
    };
 6. npm react-native link => to link
 7. Open XCode project => main app => Build Phases => Copy Bundle Resources = copy fonts to this filder
 8. Run again => npm react-native run-ios, npm react-native run-android
