[![Coverage Status](https://coveralls.io/repos/github/metavurt/weo3-base-angular/badge.svg?branch=master)](https://coveralls.io/github/metavurt/weo3-base-angular?branch=master)

# weo3 - mars rover app

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installing](#installing)
- [Running](#running)
- [Running tests](#running-tests)
- [Roadmap](#roadmap)
- [License](#license)

This project was generated with [Angular CLI](https://github.com/angular/angular-cli)

## Notes


## Requirements

Node >=v6.5.0 and npm >=3.10.3

npm-check-updates for optional below

Typescript 2.6.2 or later; some manual node management may be necessary

## Installing

```bash
$ git clone --depth 1 https://github.com/metavurt/mars-rover-app.git [your-new-app-name-goes-here]
$ cd [your-new-app-name-goes-here]

# install dependencies
$ npm install

# optional, but suggested
# check how current dependencies and dev dependencies are, just in case
$ npm outdated
# based on feedback and your personal knowledge, either update all or specific modules
# if you have npm-check-updates installed, run it and see what it says as well
$ ncu
# if the feedback looks too unstable, then update with
$ ncu -u
# afterward, re-run npm install and re-confirm with npm outdated
# disregard obvious misalignments (such as pinned modules based on necessary previous testing) unless large errors are discovered
# then please alert me at https://github.com/metavurt/weo3-base/issues
```

## Running
Run `ng serve` for a dev server. Navigate to `https://localhost:4200/`. The app will automatically reload if you change any of the source files.


## Build
Run `ng build -prod` to build the project. The build artifacts will be stored in the `dist/` directory. You need only specify `-prod` for production build, as AOT is a default attribute of production builds in angular-cli.


## Running Tests
(Before running the tests make sure you are serving the app via `ng serve`.)

Use `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).
Use `ng e2e` to execute the end-to-end tests via [Protractor](https://www.protractortest.org/).

## NOT INCLUDED
NASA API key

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).


# License

MIT
