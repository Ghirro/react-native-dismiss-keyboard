## react-native-dismiss-keyboard ![CircleCi](https://circleci.com/gh/DanielMSchmidt/react-native-dismiss-keyboard.png?circle-token=905f7ed099611e3f8079a5bf72674beab5e55e50) [![npm version](https://badge.fury.io/js/react-native-dismiss-keyboard.svg)](https://badge.fury.io/js/react-native-dismiss-keyboard) ![Downloads](https://img.shields.io/npm/dm/react-native-dismiss-keyboard.svg)

A simple way to dismiss the keyboard programmatically in a react native application. [A demo app can be found here](https://github.com/DanielMSchmidt/DismissKeyboardExample).

> This module extracts code from an undocumented React Native feature. The reason I wrote it is that the import of the internal module failed after updating and in some specific setups.

## Add it to your project

1. Run `npm install react-native-dismiss-keyboard --save`
2. To import the library choose one of these options
  - `var dismissKeyboard = require('react-native-dismiss-keyboard');`
  - `import dismissKeyboard from 'react-native-dismiss-keyboard';`
3. Run `dismissKeyboard()` anywhere in your code to close the keyboard.

## Support

| React Native Version      | react-native-dismiss-keyboard Version |
|---------------------------|---------------------------------------|
|  >= 11 & < 23             | < 1.0                                 |
| >= 23                     | >= 1.0                                |

If you experience any restrictions or if it works on other versions, please let us know.

## Contribution

Please make sure to run the tests before proposing a PR by running `npm test`.
