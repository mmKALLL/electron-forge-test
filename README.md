# Invasion

A simple game about defending your planet and escaping (?) solitude.

Made within the span of 48 hours during the Ludum Dare 38 event.

https://ldjam.com/events/ludum-dare/38/invasion


## Build instructions

First, you need npm@5.2 and node version 6.2.0 or higher.
Run npm install -g electron, then npm install -g electron-forge. If successful, you can now use electron-forge package in the project directory to build an Electron distributable. electron-forge make should in theory work as well, but no luck so far with Squirrel Winstaller module of electron-forge. It uses electron / windows-installer under the hood.

If not successful due to EPERM errors, try making sure you have npm@5.2, downgrading npm to 4.6.1, turning off antivirus, running npm cache clear, or googling the problem.
