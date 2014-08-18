#Centaurus

## The First Stellar Wallet for Android!

Stellar aims for the stars. And the nearest star system to us is Alpha Centauri!
The next step to get there is a functional app for sending and receiving payments (starting with STR, only).

The app is built using AngularJS, Cordova and the Ionic Framework. We first focus on android, but as Ionic is a platform agnostic tool, feel free to try it on the platform you like.

## Features

* Display account balance and recent transactions
* Send STR (paste address or scan QR-code)
* Receive STR (generate QR-code)
* Lock sending by local password

## Contribute

I am a complete newbee to HTML/JS, Ionic, so 
* just contribute new code
* peer review and improve existing code
* Donate to our Stellar-Address `gEux6NhrybVLuvgaYrgThTk4d3Kmd3s4NP` (need 25$ for upload to Playstore)

## Levels of Contribution

There is a simple way for contribution as long as you don't develop on phone specific issues. 

While the simple mode is a good way to get started, you will soon want to see this on your own device. Or check the layout on several emulated devices or whatever.

### Simple 

* [Fork project](https://github.com/klopper/Centaurus) as usual.
* Open file './www/index.html' with your browser. What you see is close to what you have in the app.
* Modify the html views in './www/templates/' or the JS files in './www/js/'. Watch your changes immediatly by refreshing the page in the browser. 
* You might also want to add some JS libs to './www/lib/'.
* See [www/Readme.md](https://github.com/klopper/Centaurus/blob/master/www/README.md)

### Advanced (Android)

* [Install Ionic](http://ionicframework.com/getting-started/). The [video tutorial for Windows users](http://learn.ionicframework.com/videos/windows-android/) is quite comprehensive
* [Fork project](https://github.com/klopper/Centaurus) as usual.
* Make sure your device is visible to your computer. You can check this by running ```adb devices```. More information coming soon.
* Navigate to your Centaurus root folder in the command line, use ionic to add android platform
* Build, deploy and run the app. Be Happy!
```bash
ionic platform android
ionic run android
```

### Advanced (other platforms)

No experience yet, so let us know.

## Links
* [Ionic](http://ionicframework.com/)
* [Stellar](https://www.stellar.org/blog/introducing-stellar/)
* ...
