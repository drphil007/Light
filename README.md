# Light

App that changes the screen from black to white and back at the tap of a button, not unlike a flashlight. 
Made in Xcode 9.2 

Usage
- Code to change the screen from black to white is in ViewController.swift
- Layout for button linked to code is in Main.sotryboard.swift

- ViewController.swift and Main.storyboard.swift are linked trough the buttonPressed(), which is the button
that changes the background color of the view. butonPressed calls on updateUI() which changes the backgroundColor.

- Pressing the button in Main.storyboard.swift, simulator or your iphone/ipad changes the background color of view 
from black to white and back. Click Build and Running in Xcode to see in action. 
See screenshots in doc to see examples of app on iphone. 

Prerequisites
- latest version of Mac OS system 
- download latest version of Xcode in Mac Apple Store
- Make account for Apple developer team on developer.apple.com

Installing
- download file Light.xcodeproj
- open Light.xcodeproj in Xcode 
- connect your iphone or ipad and click build and running 
