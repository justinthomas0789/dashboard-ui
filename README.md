# Mobile device dashboard ui

## Pre-requisites
### Frontend Developers
This are the prerequisites needed to work with the opentrends frontend framework. Further information available ahead
Apache or another HTTP Server with PHP capabilities (like Node.js)
Node.js
Gulp (and all the dependencies)

## Installation

run below command to install all dependencies
```sh
npm i
```
## Gulp
We use Gulp to automatize some boring and repetitive tasks saving us a lot of time migrating code between the frontend and the final platform. 
Those tasks include thigs like theme generation, Angular 1.5.x app generation, Bower main files extraction and so on.
All Gulp dependencies (including Gulp itself) are defined on the package.json of the project, therefore we only need to run from the root of the project:
```sh
npm update
```

To execute 'gulp tasks' run
```sh
gulp
```
or
```sh
gulp watch
```
