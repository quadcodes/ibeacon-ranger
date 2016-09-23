#iBeacon Ranger

##What Is It?
iBeacon Ranger is an iBeacon diagnostic tool for iOS and Android built with PhoneGap and Adobe PhoneGap Build. Built on [Peter Metz](https://github.com/petermetz)'s [iBeacon Phonegap/Cordova plugin](https://github.com/petermetz/cordova-plugin-ibeacon), range and monitor a specified set of iBeacons in real-time. This app serves as an example of how to utilize iBeacons and as a starting point for creating your own PhoneGap iBeacon app.

##Usage

###Adobe PhoneGap Build Usage

1. Fork this repository. Fork it!
2. Set iBeacons to monitor in [js/BeaconMonitor.js](https://github.com/owntheweb/ibeacon-ranger/blob/master/js/BeaconMonitor.js)
3. Visit [Adobe PhoneGap Build](https://build.phonegap.com/) and login.
4. Add a new app and paste the repository address in the related field. Example: The address for this repository is https://github.com/owntheweb/ibeacon-ranger .
5. Upload any keys for the desired mobile platform under your project settings.
6. Choose "Update Code" to pull in the latest committed code from the desired repository. PhoneGap Build will automatically build the app.
7. Once build is complete, scan the QR code with an authorized mobile device, starting the install process.
8. Joyfully range and monitor specified iBeacons in the area.

###PhoneGap Usage (self-build)
