# :zap: Ionic Angular Explorer

* App to create new folders and files. 
* This is another great tutorial from [Simon Grimm of the IonicAcademy, Youtube video 'Ionic Native File Explorer'](https://www.youtube.com/watch?v=pDqG3iYDdM0&t=141s).

## :page_facing_up: Table of contents

* [:zap: Ionic Angular Explorer](#zap-ionic-angular-explorer)
  * [:page_facing_up: Table of contents](#page_facing_up-table-of-contents)
  * [:books: General info](#books-general-info)
  * [:camera: Screenshots](#camera-screenshots)
  * [:signal_strength: Technologies](#signal_strength-technologies)
  * [:floppy_disk: Setup](#floppy_disk-setup)
  * [:computer: Code Examples](#computer-code-examples)
  * [:cool: Features](#cool-features)
  * [:clipboard: Status & To-do list](#clipboard-status--to-do-list)
  * [:clap: Inspiration](#clap-inspiration)
  * [:file_folder: License](#file_folder-license)
  * [:envelope: Contact](#envelope-contact)

## :books: General info

* A file or directory can be selected from an ion-fab button at the bottom right of the screen.
* The **Cordova-plugin-file** plugin implements a File API allowing read/write access to files stored on the device.
* The **cordova-plugin-file-opener2** plugin will open a file on your device file system with its default application.

## :camera: Screenshots

* tba

## :signal_strength: Technologies

* [Ionic v6](https://ionicframework.com/)
* [Ionic/angular v6](https://ionicframework.com/)
* [Angular v13](https://angular.io/)
* [Apache Cordova v11](https://cordova.apache.org/) to target multiple platforms with one code base
* [cordova-plugin-file v6](https://cordova.apache.org/docs/en/latest/reference/cordova-plugin-file/)
* [cordova-plugin-file-opener v3](https://www.npmjs.com/package/cordova-plugin-file-opener2)

## :floppy_disk: Setup

* `npm i` to install dependencies
* To start the server on _localhost://8100_ type: 'ionic serve'
* The Ionic DevApp was installed on an Android device from the Google Play app store.

## :computer: Code Examples

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

## :cool: Features

* File storage and access.

## :clipboard: Status & To-do list

* Status: Code complete, but needs to be tested on a connected device.
* To-do: setup a connected device/simulator to test properly.

## :clap: Inspiration

* [Simon Grimm IonicAcademy Youtube video 'Ionic Native File Explorer'](https://www.youtube.com/watch?v=pDqG3iYDdM0&t=141s)

## :file_folder: License

* N/A

## :envelope: Contact

* Repo created by [ABateman](https://github.com/AndrewJBateman), email: gomezbateman@yahoo.com
