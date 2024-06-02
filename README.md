# Ionic MovieDB with Angular 17 & Standalone Components

This project demonstrates how to use Angular 17 features with the latest versions of [Ionic Framework](https://ionicframework.com) and [Capacitor](https://capacitorjs.com) to build a cross-platform app.

## Features

- Ionic UI Components as Standalone Components
- Angular 17 Control Flow
- Route Parameter Binding
- Signals
- Inline Overlays
- ESBuild

## Getting started for developers

### Install and update the frameworks

- [Install NodeJS](https://nodejs.org/). Hint: eventually install and use [nvm](https://medium.com/@Joachim8675309/installing-node-js-with-nvm-4dc469c977d9) for easy installing and/or switching between node versions
- [Angular CLI](https://www.npmjs.com/package/@angular/cli): `npm i -g @angular/cli`
- [Ionic CLI](https://www.npmjs.com/package/@ionic/cli): `npm i -g @ionic/cli`
- [Capacitor CLI](https://www.npmjs.com/package/@capacitor/cli): `npm i -g @capacitor/cli`


### Run the app

This app uses [The Movie Database](https://www.themoviedb.org/) API to load data.

You can sign up to get an API key [here](https://www.themoviedb.org/settings/api).

Once you have your API key, edit the `environment.ts` in the `src/environments` and insert your API key!

Install the dependencies and run the app in the browser:

```bash
npm install
ionic serve
```

## Disclaimer

This repository was created with Angular 17.0.2

## Preview

```bash
<div style="display: flex; flex-direction: 'row';">
<img src="./screenshots/1.png" width="45%">
<img src="./screenshots/2.png" width="45%">
</div>
```

### Angular and upgrading

This app is on Angular 17. Update to latest Angular 18 can be done with:
`ng update @angular/cli@18 @angular/core@18`
