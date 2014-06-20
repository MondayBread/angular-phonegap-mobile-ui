grunt-angular-phonegap + Mobile Angular UI
==============================

An example project with dsimard/grunt-angular-phonegap

## Prepared

Globally install phonegap and [yeoman/generator-angular][generator-angular] :

    npm install -g phonegap cordova generator-angular


## Getting started

1. Clone this project

        git clone https://github.com/dsimard/grunt-angular-phonegap-example.git && cd grunt-angular-phonegap-example/ 

2. Install npm modules

        npm install

3. Install bower dependencies

        bower install

4. Add a mobile platform

        cordova platform add android

4. Build the project

        grunt phonegap:build

5. Start an emulator

        grunt phonegap:emulate

6. Start on device

        cordova run android
