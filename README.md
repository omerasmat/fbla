# FBLA app "jericho central'

# Fast Facts: FBLA
### FBLA Mobile App Development 2021-2022
### Jericho Highschool
### Team Members: Omer Asmat, Alex Samadi

# Description
our app named jericho central is an app that is created according to the FBLA 21-22 guidlines that is made for students at jericho to organize their schedule, classes, or tasks, while also being able to quickly access various school related tasks. this includes the ability to email teachers, look at the lunch menu, extracurricular activities, and a calender, you may also create an account that uploads all information related to your account including your classes by logging in with an email. All account informations are uploaded to google firebase. 


$ flutter pub get
$ flutter packages pub run build_runner build --delete-conflicting-outputs

## Getting Started

FlutterFlow projects are built to run on the Flutter _stable_ release. To ensure the project runs smoothly. 

### IMPORTANT:

For projects with Firestore integration, you must first run the following commands to ensure the project compiles:

```
flutter pub get
flutter packages pub run build_runner build --delete-conflicting-outputs
```

This command creates the generated files that parse each Record from Firestore into a schema object.

### Getting started continued:

Instructions
Run in VSCODE, use latest version of cocoapods and run in the xcode simulator to an iphone 13. Open a simulator through vscode and make sure to run "flutter pub get"
"flutter packages pub run build_runner build --delete-conflicting-outputs to clear errors"

Flutterflow will launch a virtual machine and the app will be compiled and streamed into your browser. Our backend system uses firebase so our app will only function correctly this way due to the configurations we are using to build our app for multiple platforms on flutter. 

Click register and sign up with your email and a password and enter a username and any other related information.
Next, click login with the same email and same password that was used to register
From there you will be logged into the application
You can use the navigation bar on the bottom to navigate through different pages on the app. 
You can add tasks(classes) or a jericho highschool student can input their classes or as a shortcut click the bottom most right icon and you can enter your school ONLY IF YOU USE A JERICHO EMAIL
The home page also has a slider that you have to tap on and you can access the calendar, extracurricular list, or the lunch menu.
The send email page is also located in the home page menu. However you must note that we have to manually run a computer on our end for the API, so this will only be functional in a demonstration. This is however functional
If you were to download this app onto a mobile device, you will be able to login with your account and you will be able to see all of your information, like your schedule.


This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:


For help getting started with Flutter, 
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
