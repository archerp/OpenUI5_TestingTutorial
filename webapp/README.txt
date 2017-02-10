
Download OpenUI5 runtime .zip from http://openui5.org/download.html

Unzip OpenUI5 runtime in webapp folder (will create resources folder) then delete the index.htm file

To start localhost in cmd running mockServer.html:

browser-sync start --server --index test/mockServer.html --files "**/*"