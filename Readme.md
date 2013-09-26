This branch is forked from https://npmjs.org/package/soap-js which was branched from https://github.com/milewise/node-soap.

Install:  npm install soap-cascade

This branch makes modifications documented in https://github.com/milewise/node-soap/issues/143 that allow 
the soap-js branch to work with Cascade Server by Hannon Hill.

## Features
* [x] propagate namespace in SOAP Envelope
* [x] correctly encode arrays from JSON arguments
* [ ] reorder arguments to match WSDL before sending (in progress as new feature 9/23/2013)

For examples of use see [Grunt Cascade Examples](https://github.com/jraller/Grunt-Cascade-Examples). This 
resource also has a [wiki](https://github.com/jraller/Grunt-Cascade-Examples/wiki).

To generate JavaScript code from the WSDL see [WSDL to JS](https://github.com/jraller/WSDLtoJS).
