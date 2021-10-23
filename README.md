An issue on RN repo https://github.com/facebook/react-native/issues/32465

steps to reporduce

- expo init shadowSample
- select `blank`
- cd shadowSample
- expo install @react-native-community/slider
- find App.js and paste code from https://snack.expo.dev/@aymkin/shadow-props
- yarn android: expected to have a shadow at square box, but it does not exist
- yarn ios: we see and can adjust a shadow as expected

  The snack link https://snack.expo.dev/@aymkin/shadow-props
  The react native docs example https://reactnative.dev/docs/0.64/shadow-props

The only one existing screen should represent the box with adjastable shodow. But is does not work. To compare it - run `yarn ios`
