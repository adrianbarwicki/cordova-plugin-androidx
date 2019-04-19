cordova-plugin-androidx
=======================

This Cordova/Phonegap plugin enables [AndroidX](https://developer.android.com/jetpack/androidx/migrate) in a project.

This allows the use of plugins which have migrated to AndroidX, etc.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Requirements

This plugin requires a minimum of [`cordova@9`](https://github.com/apache/cordova-cli) and [`cordova-android@8`](https://github.com/apache/cordova-android).
 
# Installation

    $ cordova plugin add cordova-plugin-androidx
    
**IMPORTANT:** This plugin relies on [Cordova hook scripts](https://cordova.apache.org/docs/en/latest/guide/appdev/hooks/) so will not work in Cloud Build environments such as Phonegap Build which do not support Cordova hook scripts. 
    
# Usage

There is no usage! Once the plugin is installed it will configure the native Android platform in your Cordova project to use AndroidX.

If you encounter subsequent issues such as build failures **do not report them against this plugin** as it simply enables AndroidX.
Instead check your other existing plugins to see if they are compatible with AndroidX and if not raise the issue against them.

License
================

The MIT License

Copyright (c) 2019 Dave Alden / Working Edge Ltd.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
