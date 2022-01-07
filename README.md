# Ticket Maestro

Ui for a Ticketsystem

Receaving Tickets

Adding a ticket

Managing tickets

project features and functionality based on https://angular.io/tutorial

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.1.2.

---------------------------------------------------------------

## concepts

### modules and submodules

a module in angular are containers for a cohesive block of code dedicated to an application task
every angular project has a root module in `app`
submodules are seperate containers which hold there own logic 
all submodules need to be imported to the root module 

--> added `ticket-entry-point` directory 
contains `ticket-entry-point.mdoule` which is a submodule of app  
delegates all logic within that module 

https://github.com/Erwin-Feld/ticket-maestro/tree/generating-and-using-a-submodule


---------------------------------------------------------------


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
