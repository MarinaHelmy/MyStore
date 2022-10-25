# MyStore

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.25.
The MyStore app is an Ecommerce app. Implemented functionality: 
- Listing all store products
- Add/remove items to/from your cart,
- See a notification badge for new added/deleted item
- Checkout and Place an order

## Install npm packages

Install the `npm` packages described in the `package.json` and verify that it works:

```shell
npm install
```
`npm` is the package manager for the Node JavaScript platform. It puts modules in place so that node can find them, and manages dependency conflicts intelligently.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

Run `ng add <packageName>` to add a new angular package to your project along with apply needed changesm For example: Updating package.json 

Run `npm install <packageNmae>` to install a package and any packages that it depends when `npm` is the package manager for the Node JavaScript platform we installed at the first step


## Included Packages 
 - Angular Materil  
 By running  `ng add @angular/material`
 - Bootstrap 
 By running `npm install --save bootstrap` then update `angular.json` by adding this `"node_modules/bootstrap/dist/css/bootstrap.min.css"` to scripts. 
 - RxJS (BehaviorSubject, Subscription)
 By importing them from RxJS `mport { BehaviorSubject, Subscription } from 'rxjs'`


## Keywords
  `@input`, `@output`, `selector`, `decorator`, `@componet`, `RxJS`, `BehaviorSubject`, `Subscription`, `unsubscribe`, `HttpClient`, `AngularMaterial`, `Forms`, `ReactiveForms`, `pipe`, `directives`, `ng-container`, `navigate`.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.


## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

