# vendor-limiter

This is an app for Android that detects application included on vendor DIR on / file system.
It creates an app with identical package name of the one in vendor DIR.
This app will create an app and make it lighter, having less than 1 MB of size.

Example;

The app XAMPle 
pkg name: com.example.xample
Uninstallable: True
Size: 30 MB
Found on Vendor: True , Then every reboot, it restores/reinstalls the app.

My app,

Generate an app

app name format: vl <app-name>

app name: vl XAMPle
pkg name (auto/user-specified)
target size: Below 1 MB

Signed the app.
Removing original application, then installing this one. 

Then, Reboot.
Inspect the target app.
And the results.
