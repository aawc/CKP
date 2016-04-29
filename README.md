# CKP
Chrome extension for interacting with KeePass password file.

## Development process

### Tools needed

* [Node.Js](http://nodejs.org/) - prerequisite for other dev tools
* [Grunt.js](gruntjs.com) - for less/css processing, packaging, and copying libs to the lib folder
* [Bower](http://bower.io/) - for dependencies (libraries)

### How to build
1. Clone the codebase
2. ```cd ckp```
3. ```bower install``` to install the dependencies.  
4. ```grunt updatelib``` to copy the dependencies to their lib location.  
5. If you are editing ```.less``` files then run ```grunt watch``` to compile them when they change.

### To install the code in Chrome

1. Open ```More Tools``` > ```Extensions```, check the ```Developer mode``` checkbox.
2. Click ```Load unpacked extension``` and browse to the folder where you cloned the code.
3. You may find the [Chrome Apps & Extensions Developer Tool](https://chrome.google.com/webstore/detail/chrome-apps-extensions-de/ohmmkhmmmpcnpikjeljgnaoabkaalbgc) to be helpful when debugging the background page.


## Installing from Chrome WebStore

1. [Original extension](https://chrome.google.com/webstore/detail/lnfepbjehgokldcaljagbmchhnaaogpc)