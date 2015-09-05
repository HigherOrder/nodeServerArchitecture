API
===

API server providing endpoints to our clients.
Modular architechture ensures maximum code maintainability.

All code is unit tested using Sinon, Mocha.

We try to have more than 97% code coverage for our service layer.

We use GULP for automation and code coverage reports

## Release History

* 0.1 Initial release, API skeleton.

1. Available Gulp tasks:

   >```gulp```: Start local server.
   >
   >
   >```gulp test```: Run unit tests with coverage report.
   >
   >
   >```gulp t```: Run unit tests without coverage report.
   >
   > mocha schema/todo_test.js --reporter spec
   > gulp test# nodeServerArchitecture
   
