# Angular 11.2.11, NgRx and Angular Material Starter

by [@aurelido](https://twitter.com/aurelido)

[![license](https://img.shields.io/github/license/aurelido/angular-base-project)](https://github.com/aurelido/angular-base-project/blob/main/LICENSE) 
![Travis (.com)](https://img.shields.io/travis/com/aurelido/angular-base-project)

## Getting started

```bash
git clone https://github.com/aurelido/angular-base-project.git new-project
cd new-project
npm install
npm start
```

## Useful Commands

- `npm start` - for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
- `npm run start:prod` - runs full prod build and serves prod bundle
- `npm run test` - runs lint and tests
- `npm run watch` - runs tests in watch mode
- `npm run prettier` - runs prettier to format whole code base (`.ts` and `.scss`)
- `npm run analyze` - runs full prod build and `webpack-bundle-analyzer` to visualize how much code is shipped (dependencies & application)

![analzye](https://raw.githubusercontent.com/tomastrajan/angular-ngrx-material-starter/master/meta-assets/analyze.png)

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



## Webpack Bundle Analyzer
Use webpack Bundle Analyzer with Angular to help visualize where code in the final bundle comes from.

`npm run anylize` and the analisys will start at http://127.0.0.1:8888

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.