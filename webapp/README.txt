
Prerequisites: VS code, node.js, git 

If browsersync not installed: npm install -g browser-sync

Download OpenUI5 runtime .zip from http://openui5.org/download.html
Unzip OpenUI5 runtime in webapp folder (will create resources folder); do not overwrite any files, delete the new index.htm file if extracted

To get the tutotrial app running in VS code:

Change src for sap-ui-bootstrap to /resources/sap-ui-core.js (in MockServer.html, unitTests.qunit.html, opaTests.qunit.html)
In test.html links need to be prefixed with test/

*********************************************************************************

To start localhost running test.html entry page: open cmd, cd to webapp folder:

browser-sync start --server --index test/test.html --files "**/*"

