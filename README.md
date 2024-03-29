# DigiSigner API Utility

![alt text](image.png)

DigiSigner API Client is an utility primarily designed as an electronic signature platform, allowing users to sign documents like pdf and XML digitally.
The Signer utility offers integration capabilities with other business applications and systems, allowing users to seamlessly incorporate electronic signature functionality into their existing workflows.

You can Download the DigiSigner API Utiliy at https://repo.caisias.com/downloads/release/

## Demo

https://signerdemo.caisias.com

## API Key

Get free API key from https://digisigner.caisias.com

## Installation Step

Download or clone the project

```powershell
cd signer-demo
npm install
ng generate environments
```

Update Environment Files (environment.ts and environment.development.ts)

```json
export const environment = {
    production: false,
    clientServer: "https://localhost:63108",
    signerApiKey: "eyJhbGciOiJIUzI1NiIsInR5........."
};
```

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts/app will be stored in the `dist/` directory.

## Documentation

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
