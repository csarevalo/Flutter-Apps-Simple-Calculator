# My Simple Calculator

## Why I built this app?
While researching for ways to build application across multiple platforms I came across flutter, which used *dart* to program application in various systems using one language: dart. This seemed appeal as opposed to learning various code languages to create a simple app across devices. This is my first Flutter application, with primary objection of becoming familiar with the widget structure of flutter and dart syntax. 

## App Intro
The goal of this Flutter project is to develop a calculator app with simple features. It can perform multiplication, division, addition, and subtraction. It also handles decimal numbers, as well as negative numbers.  

### Features
Some key features include: history, raw number, and main display.

1. Raw number display either shows the user input or the result from calculations. It is a relative straight forward feature. Plain for a consistent perception for the user.

1. The main display takes the raw number and convers it into a visually appeal number form (either scientific notation or decimal form) depending on how many digits are added; moreover, the main display adds a comma every order of 10^(3) (e.g. 1,000 or 1,000,000). 

1. History is shown using only raw numbers to not cause any confusion when looking at scientific notation. The primary purpose of history is to always remind the user of what calculations they have perform up to the current instance.

## Try it yourself
There are two ways easy methods you can test this simple calculator yourself (*without installing anything on your device*):

1. [FlutLab: an online IDE for Flutter](https://flutlab.io/)

2. [DartPad: an online code editor for Dart (it can run *flutter* programs)](https://dartpad.dev/?id)

If you have no intent on going through the code and want a **fast, hassle free test of the application, I recommend dart pad** (I even added a file just for it by combining all dart files together, just copy & paste and voilà, done). [DartPad File is here](lib/dartPad_main.dart).

However, if you want to look through the code, a more organize way of doing it would be through FlutLab (just import the project to your workspace from the rep url and change a few dependencies... mainly the flutter version from 10.1.3 to 10.1.0). This method is a bit lengthier (about 10-20mins if you watch tutorials) though so be warned.


## Thanks for reading
With this, I hope to be able to become a better programmer and make better apps in the future. Thanks for your time.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
