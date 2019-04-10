# Pet Adoption ReactNative App

## Table of Contents
* [Preview](#preview)
  * [Android](#android)
  * [iPhone](#iphone)
* [SETUP](#setup)
  * [Config](#config)
  * [Install](#install)
  * [Build](#build)

## Preview

### Android
[Download on Google Play](https://play.google.com/store/apps/details?id=com.github.addyh.pinder)

<img src="./images/screenshot1.jpg" width="210" /> <img src="./images/screenshot2.jpg" width="210" /> <img src="./images/screenshot3.jpg" width="210" /> <img src="./images/screenshot4.jpg" width="210" />

### iPhone
<img src="./images/screenshot1-iphone.png" width="210" /> <img src="./images/screenshot2-iphone.png" width="210" /> <img src="./images/screenshot3-iphone.png" width="210" /> <img src="./images/screenshot4-iphone.png" width="210" />

# SETUP

## Config
First of all, before anything, please note that the URIs to `pets.json` and `settings.json` are set in:
```
/ API_CONFIG.json
```
## Install
```
git clone https://github.com/addyh/pinder.git
cd pinder
npm install && npm install -g react-native-cli
```

## Build 
### For Windows / Android dev
(while in same directory as above, turn on an Android emulator or plug in an android device)
```
react-native run-android --variant=release
```
### For MacOS / iPhone dev
Open the iOS project at `ios/pinder.xcodeproj` with Xcode
```
react-native run-ios --configuration Release
```
