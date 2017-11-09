# Goal

Create an angular web app with webpack and aot integration.

# Setup

## Angular-CLI

Running: 'npm install -g @angular/cli'

## Yarn

Yarn as package manager (https://medium.com/@beeman/using-yarn-with-angular-cli-db2e318e43c5)
Running: 'ng set --global packageManager=yarn'

# Project

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.5.0.
Running: 'ng new' (existing project repository from git)

## Webpack and AOT

Using ng eject from CLI (http://www.dzurico.com/angular-cli-with-the-super-powers)
AOT: Running 'ng eject --aot'
(NO aot: Running: 'ng eject')

# Deploy

Running: 'yarn build'

# Performance tests

AOT vs. not AOT
- 25% faster at loading (Google Chrome DevTools)
- 50% lighter in files (dist folder)
