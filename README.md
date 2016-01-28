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

- Demo of the App, with tests running on the device.
- CI workflow 
    - Create a VSTS instance connected to a GITHUB repo
    - Create Build definitions for
        - Building the package (Cordova build)
        - Deployment to testers (HockeyApp)

##Pre-reqs
- Github account
- Fork https://github.com/subhagpo/App and then Git clone your repo, we will be connecting to it from our CI 
- Interest in hybrid app building & motivation to learn CI through VSTS
- Patience & lots of it!

*Note:* The workshop is performed on an Android device 
(but, should work for your iOS devices too, with some additional steps)
