# Sample React Native App

## Description

This Sample ReactJS front-end project demonstrates what a typical JavaScript (or node) CI workflow may look on CircleCI.
In this sample config, we have 2 workflows `test` and `build`. This config utilizes the node and android orbs, and runs through an android machine image for building and testing and a convenience image for deploying.

## Getting Started

To run this project you first need to setup [Android Studio](https://developer.android.com/studio/install) and setup an [Android Virtual Device](https://developer.android.com/studio/run/managing-avds). Next you will need to run `npm install` within the root directory of the project. Next you will have to open 2 terminals in the root directory.
First run `npx react-native start` in one terminal to start Metro and then run `npx react-native run-android` in the second to build the app.
