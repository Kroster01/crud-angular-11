# Contact

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.7.

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


# NOTAS:
1.- ng s --hmr
    * Hot Module Replacement -> recargar solo la sección que se modifica.

# PASOS.
1.- creación del proyceto
2.- creación modulo pages/home
    * ng g m pages/home --module app --route home
    * ng g m pages/contact --module app --route contact
    * ng g c shared/components/header --module app
    * ng g m shared/components/header --module app

# Dependencias.
1.- ng add @angular/fire
    * Seleccionar el proyecto de firebase