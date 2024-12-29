# RenuAngularSandbox

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.6.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

# used commands for project creation ##### 25-12-2024
node -v => v22.9.0
npm -v => 10.8.3
ng new renu-angular-sandbox

# commands used to upload project in github
create a new repo in github
git init
git add *
git commit -m "my first commit"
git remote add origin https://github.com/renukaamujuru/renu-angular-sandbox-.git
git push --set-upstream origin master

# host website
Rename repo name to renu-angular-sandbox.github.io
In local machine - git clone https://github.com/renukaamujuru/renu-angular-sandbox.github.io
ng add angular-cli-ghpages
>ng deploy --base-href=https://github.com/renukaamujuru/renu-angular-sandbox.github.io --name=renukaamujuru --email=renukaamujuru@gmail.com

chanage outputPath in angular.json
"outputPath": "dist/renu-angular-sandbox.github.io",
ng build --base-href "https://renukaamujuru.github.io/renu-angular-sandbox.github.io/"
ng build --configuration production --base-href "https://renukaamujuru.github.io/renu-angular-sandbox.github.io/"

npx angular-cli-ghpages --dir=dist/renu-angular-sandbox