# firebase-emulators-exec-windows-10

Tried Windows 10
firebase-tools 9.8

`cd ./functions`

`npm install`

Try to run

`npm run serve`

in the terminal debug output you will be able to spot runtimeconfig.json variable `test.api_key` with value `testing2`

then try to run

`npm run test`

in the terminal debug output doesn't have the above variable `test.api_key` with value `testing2`
