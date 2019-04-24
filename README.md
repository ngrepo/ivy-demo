# AngularIvy

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.8 and ivy enabled.

## Clone Repo

Clone this repo to your local `git clone https://github.com/kashin2453/ng-ivy.git `.

## Install NPM modules

Open ng-ivy folder and install modules `npm install`.

## Development server

Run `ng serve --aot` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

<!--  Text
Served without app.module.ts .

Add this to your tsconfig.app.json
  "angularCompilerOptions": {
    "enableIvy": "ngtsc"
  }

Replace maint.ts file to:
    import { AppComponent } from './app/app.component';
    import { ɵrenderComponent as renderComponent } from '@angular/core';

    renderComponent(AppComponent
-->