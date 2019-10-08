# Ionic Angular Explorer

App to create new folders and files. This is another great tutorial from [Simon Grimm of the IonicAcademy, Youtube video 'Ionic Native File Explorer'](https://www.youtube.com/watch?v=pDqG3iYDdM0&t=141s).

## Table of contents

* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info

* A file or directory can be selected from an ion-fab button at the bottom right of the screen.

* The **Cordova-plugin-file** plugin implements a File API allowing read/write access to files stored on the device.

* The **cordova-plugin-file-opener2** plugin will open a file on your device file system with its default application.

## Screenshots

![screenshot](./img/.png)
![screenshot](./img/.png)

## Technologies

* [Ionic v5.15.0](https://ionicframework.com/)
* [Ionic/angular v4.7.1](https://ionicframework.com/)
* [Angular v8.1.2](https://angular.io/)
* [cordova-plugin-file v6.0.2](https://cordova.apache.org/docs/en/latest/reference/cordova-plugin-file/)
* [cordova-plugin-file-opener v2.2.1](https://www.npmjs.com/package/cordova-plugin-file-opener2)

## Setup

* To start the server on _localhost://8100_ type: 'ionic serve'
* The Ionic DevApp was installed on an Android device from the Google Play app store.

## Code Examples

* code from Cordova plugin to open a file on mobile device file system with its default application

```typescript
cordova.plugins.fileOpener2.open(
    filePath,
    fileMIMEType,
    {
        error : function(){ },
        success : function(){ }
    }
);
```

## Features

* File storage and access.

## Status & To-do list

* Status: Code complete, but needs to be tested on a connected device.

* To-do: setup a conected device/simulator to test properly.

## Inspiration

[Simon Grimm IonicAcademy Youtube video 'Ionic Native File Explorer'](https://www.youtube.com/watch?v=pDqG3iYDdM0&t=141s)

## Contact

Repo created by [ABateman](https://www.andrewbateman.org) - feel free to contact me!
