# Stackblitz

This directory contains the source files for generating the individual framework targets for a playground examples. The contents of the files will be loaded and injected into the Stackblitz example that is opened from the Playground.

## Angular

| File               | Description                                            |
| ------------------ | ------------------------------------------------------ |
| `angular.json`     | Main configuration file for any Angular application.   |
| `app.component.ts` | Primary component class/entry point.                   |
| `app.module.ts`    | Primary `AppModule`. Specifies required `IonicModule`. |
| `main.ts`          | Responsive for bootstrapping the main `AppModule`.     |
| `styles.css`       | Ionic default styles                                   |

## HTML

| File         | Description                                                       |
| ------------ | ----------------------------------------------------------------- |
| `index.html` | Main template file with CDN link to latest `@ionic/core` release. |
| `index.ts`   | Defines the Stencil hydrated bundle for Ionic.                    |

## React

| File       | Description                                                                                  |
| ---------- | -------------------------------------------------------------------------------------------- |
| `app.tsx`  | Imports required Ionic styles and `setupIonicReact()` function to initialize web components. |
| `index.js` | Boilerplate to render a React app.                                                           |

## Vue

- Coming soon