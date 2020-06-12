# README #

### Cordova Plugin for iOS and Android to present a native input field for chat applications. ###

![IMG_B631B3A1D0D9-1](https://user-images.githubusercontent.com/51481828/84481818-fb55d680-ac96-11ea-9b69-30e2cd9ca642.jpeg)


## Supported platforms

- Android 5+
- iOS 11+


## Installation

```js
cordova plugin add cordova-plugin-impac-keyboard
```

## Show / hide input field

To add the input field to the current screen perform *showKeyboard*.

```js
window.plugins.impacKeyboard.showKeyboard(() => {
  // Keyboard is presented
});
```

To remove the input field again perform *hideKeyboard*

```js
window.plugins.impacKeyboard.hideKeyboard(() => {
  // Keyboard removed
});
```
