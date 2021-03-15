# Microservice for uploading files to firebase storage

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
  <a href="https://firebase.google.com/?hl=es" target="blank"><img src="https://www.gstatic.com/devrel-devsite/prod/vfae72444d3bdc8ae13b8cc5631b2eafccb5edbf6e3dc3e733b21af239a5c570e/firebase/images/lockup.png" width="320" alt="Firebase Logo" /></a>
</p>

## Description

Allows uploading any type of file to firebase google storage. In turn, it stores meta data in the database.

## Installation
Install yarn
```bash
$ npm install --global yarn
```

Install firebase-tools
```bash
$ yarn global add firebase-tools
```

Install dependencies
```bash
# yarn install
$ yarn 
```

## Running the app

```bash
# Build code
$ yarn build

# Run firebase emulator
$ firebase emulators:start
```

## Additional documentation
Firebase emulator [documentation](https://firebase.google.com/docs/functions/local-emulator).
Cloud Storage con Cloud Functions [documentation](https://firebase.google.com/docs/storage/extend-with-functions?hl=es).
