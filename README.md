~~# vendor-limiter~~
# System-PreLoad-Limiter

This is an app for Android that detects application included on preload DIR on /system file system.
It creates an app with identical package name of the one in vendor DIR.
This app will create an app and make it lighter, having less than 1 MB of size.

Example; ** For _High-End_ Devices **

The app XAMPle 
pkg name: com.example.xample
Uninstallable: True
Size: 30 MB
Found on PreLoad: True , Then every reboot, it restores/reinstalls the app.

Example; ** For _Low-End_ Devices **

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


It is useful on phones that has low storage.
And has useless Preload apps.

[Raw-DIR](https://raw.githubusercontent.com/1-2-Tree/system-preload-limiter/main/preload-dir-limiter.txt)
