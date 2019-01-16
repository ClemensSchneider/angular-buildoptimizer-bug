# BuildOptimizerBug

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.2.9 (and updated to 7.2.1).

## Reproducing the issue

Run `yarn` to install dependencies, then run `yarn build` to build the production build with `buildOptimizer` enabled.
Serve the resulting artifacts in `dist/build-optimizer-bug` with a regular http-server and open the application in the browser. You can see, that it errors out without displaying anything.

Then, turn off `buildOptimizer` in `angular.json` and run `yarn build` again. Open the resulting artifacts in the browser again and see, that everything works as expected.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
