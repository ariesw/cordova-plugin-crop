# cordova-plugin-crop

> This is just cordova-plugin-crop v0.4.0 with few changes which allow control crop mode via options.

> Based on https://www.npmjs.com/package/cordova-plugin-crop-mod

[![npm](https://img.shields.io/npm/v/cordova-plugin-crop.svg?style=flat-square)]() [![npm](https://img.shields.io/npm/l/cordova-plugin-crop.svg?style=flat-square)]()

## Install

```
$ cordova plugin add --save https://github.com/jeduan/cordova-plugin-crop
```

## Changes

```
options.keepingAspectRatio = true; // Default value is "false"
```
![keepingAspectRatio=false](https://img.shields.io/badge/keepingAspectRatio-false-orange.svg?style=flat-square) |  ![keepingAspectRatio=true](https://img.shields.io/badge/keepingAspectRatio-true-green.svg?style=flat-square)
--- | ---
![keepingAspectRatio=false](https://i.imgur.com/OUblUsM.png)  | ![keepingAspectRatio=true](https://i.imgur.com/S3nc199.png)
### Libraries used

 * Source: [cordova-plugin-crop ](https://www.npmjs.com/package/cordova-plugin-crop)
 * iOS: [PEPhotoCropEditor](https://github.com/kishikawakatsumi/PEPhotoCropEditor)
 * Android: [android-crop](https://github.com/jdamcd/android-crop)