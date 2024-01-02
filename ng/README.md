# Velzon

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.1.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ##
## ## Common Steps ##
## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ##

## COMMON COMMAND
1) npm install
2) ng build
3) npx kill-port 4200 (if port alredy in use need to destroy)
4) ng serve --o
5) ng version 

## Open Git bash Terminal use command step by step

Step 0: Create a Module With routing
( ng g m pages/{zentixs-lims} --routing )

Step 0.1: Create a Module Without routing
( ng g m pages/{zentixs-lims} )

Step 1: Create a Component
( ng g c pages/zentixs-lims/{ComponentName}} )

Step 2 : Create a Model
( ng g class pages/zentixs-lims/{ComponentName}/model/{ComponentName} --type=model )

Step 3 : Create a directive if needed
( ng g d pages/zentixs-lims/{ComponentName}/directive/{ComponentName}.directive )

Step 4: Create a project Services 
( ng g s pages/zentixs-lims/{ComponentName}/services/{ComponentName}-service/{ComponentName} )

Step 5 : Create a API service if needed
( ng g s pages/zentixs-lims/{ComponentName}/services/api-service/api-{ComponentName} )

Step 6 : Create a Class
( ng g class pages/zentixs-lims/{ComponentName}/model/{ComponentName} )

## Angular Codding Steps

Step 1 : Create Component, Model and Services
Step 2 : Coding In Model ( Common Below Structure )
Step 3 : Coding in API Service ( Common Below Structure )
Step 4 : HTML Design In CSHTML Page
Step 5 : Coding In Component ( Common Below Structure )

## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ##

spect Filse false regarding
ng g {componentname} --spec=false
