# Requirements
1. node v14.11.0
2. cordova 10.0.0

# Setup

1. `npm install`
3. `cordova prepare`
4. Open in Xcode and run.

# Testing
1. Set Twilio token in index.html and run the app on your iOS device.
2. Create a copy of index.html using another token and run the other instance using `http-server` on your browser.

# Issues
1. Video stream not visible on browser after unpublishing and then republishing video on iOS device (using toggleVideo)
2. Video stream hangs after switching camera using track.restart
