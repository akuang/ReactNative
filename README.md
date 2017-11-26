# ReactNative.iOS
React Native Learning &amp; Experiments



Quick Start Guide: http://facebook.github.io/react-native/docs/getting-started.html

# A few edits to make it work:

Need /root/Administor permission:
# $ sudo npm install -g create-react-native-app

Hit error because npm 5 is not supported. Need to downgrade npm: 
# sudo npm install npm@4 -g
4.6.1

# $ create-react-native-app my-app
Success! Created Experiments.iOS
Inside that directory, you can run several commands:

#  npm start
    Starts the development server so you can open your app in the Expo
    app on your phone.

#  npm run ios
    (Mac only, requires Xcode)
    Starts the development server and loads your app in an iOS simulator.

#  npm run android
    (Requires Android build tools)
    Starts the development server and loads your app on a connected Android
    device or emulator.

#  npm test
    Starts the test runner.

#  npm run eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

We suggest that you begin by typing:

#  cd Experiments.iOS
#  npm start

Happy hacking!

# $ npm start
11:50:45: Unable to start server
See https://git.io/v5vcn for more information, either install watchman or run the following snippet:
  sudo sysctl -w kern.maxfiles=5242880
  sudo sysctl -w kern.maxfilesperproc=524288
        
# $ sudo sysctl -w kern.maxfiles=5242880
kern.maxfiles: 12288 -> 5242880
# $ sudo sysctl -w kern.maxfilesperproc=524288
kern.maxfilesperproc: 10240 -> 524288

# $ npm start
11:53:08: Starting packager...
Packager started!

 › Press Ctrl+C at any time to stop.
 › Press a to open Android device or emulator, or i to open iOS emulator.
