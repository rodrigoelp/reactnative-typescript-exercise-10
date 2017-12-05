# Typography

Writing applications in react-native does not take long before you change a `Text` to the wrong font family, crashing the application in iOS.

Android is a little bit more tolerant when dealing with fonts, it will try to apply a default if the font
you have provided can not be found... but, the two systems have disctinctively different sents of fonts.

One solution is to use a single font family/typeface for your application... but there are several benefits to use the ones provided with the system.

So, decided to create this app to allow me to check the fonts in existence.

Searching online I've found the list found below... So, let's check what can we do!

[List of fonts](https://github.com/react-native-training/react-native-fonts)

The list contains a total of 294 font families for iOS and 10 for Android.

Now, the list includes `"San Francisco"` as a valid font... but iOS exposes it as `System Font` so that will be a change worth looking into.

Overall, this is going to be a pretty simple project in which I am going to put to test the debugging capabilities of iOS and Android (trying to find what might go wrong).

## How to run this code?

```sh
# Cloning the repo to 'typography'
git clone git@github.com:rodrigoelp/reactnative-typescript-exercise-10.git typography
# Changing directory
cd typography
# Installing dependencies
yarn # if you have not installed yarn, then change it to: npm install
# Compiling the typescript code
./node_modules/.bin/tsc
# Launching the react-native development server
open -a Terminal "`react-native start`"
# Compiling the code for ios and deploying it to the simulator
react-native run-ios # optionally, type: react-native run-android
# Alternatively, you could comment the line above and run the two lines below.
# open -a Terminal "`react-native run-ios`"
# open -a Terminal "`react-native run-android`"
```
