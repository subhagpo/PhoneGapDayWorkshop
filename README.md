#PhoneGapDayWorkshop
Lets have fun building, testing and distributing your hybrid app on the cloud!

##Goal
Build and manage your hybrid application with unit/UI tests and integrating it with a CI system that maintains quality and distribution.

##What to expect?
- Demo of Hybrid app (based on Ionic tabs template) configured to run unit (Jasmine/Karma) and UI (protractor/Appium) tests.
- Learn how to create build definitions for continuous integration using VSTS 2015, that enables - build, test & distribution of your app, every time a change is committed to your repo.

##Audience
- Cordova developers tirelessly designing, developing, building, testing & validating their hybrid mobile applications.
- Cordova developers using CI systems for building, testing & continuous delivery of their apps to testers, clients and eventually the consumers.

##Should I stay? 
Here's the agenda, 

- Watch the local workflow in action, 
    - Clone the repo https://github.com/subhagpo/App : A feedback application, using Facebook authentication integrated with Firebase backend, that allows users to submit ratings to predefined set of questions using their mobile devices. 
    - Build the app, show it running on the device.
    - Create HockeyApp account and deploy the app for beta testers to download.
    - Add HockeyApp registration, unit tests and run unit/UI tests on a device.

- CI workflow 
    - Create a VSTS instance connected to the GITHUB repo
    - Build definitions for
        - Test (Unit/UI)
        - Building the package (Cordova build)
        - Deployment (HockeyApp)

##Pre-reqs
- Github account
- Fork https://github.com/subhagpo/App and then Git clone 
- [VS CODE](https://code.visualstudio.com/) & Cordova Tools extension @ https://marketplace.visualstudio.com/items?itemName=vsmobile.cordova-tools 
- Workshop steps performed on OSX & Android device (but, should work for your iOS devices too)
- Interest in hybrid app building & motivation to learn CI through VSTS
- Patience & lots of it!
- *[Optional]* Ionic/Cordova/Taco install (if you want to try stuff locally)