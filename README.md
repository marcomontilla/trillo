[![github.com/marcomontilla](https://avatars2.githubusercontent.com/u/25273655?v=4&s=120)](https://github.com/marcomontilla/)

# Trillo
This repo contains the source code for the front-end for **Trillo**, to see the live demo go [here - Trillo](https://marcomontilla.github.io/trillo/)


### Getting Started

There are two methods for getting started with this repo.

#### Familiar with Git?
Checkout this repo, install dependencies, then start with the following:

```sh
> git clone https://github.com/marcomontilla/trillo.git
> cd trillo
> npm install
> npm run build:css
> google-chrome index.html
```

#### Not Familiar with Git?
Then download the .zip file.  Extract the contents of the zip file, then open your terminal, change to the project directory, and:

```sh
> npm install
> npm run build:css
> google-chrome index.html
```

#### Scripts
* watch:sass -> Compile all SASS Code to CSS and keeps watching modifications
* devserver -> Runs on localhost:8080
* start -> Runs on localhost:8080 and keeps watching modifications
* compile:sass -> Compile all SASS Code to CSS
* prefix:css -> Adds the CSS prefixes
* compress:css -> Minify the CSS file
* build:css -> Production Build

#### Are there old dependecies?
npm-check-updates is a command-line tool that allows you to upgrade your package.json or bower.json dependencies to the latest versions, regardless of existing version constraints. 
#### github: https://github.com/tjunnone/npm-check-updates

```sh
> sudo npm install -g npm-check-updates

 express           4.12.x  →   4.13.x
 multer            ^0.1.8  →   ^1.0.1
 react-bootstrap  ^0.22.6  →  ^0.24.0
 react-a11y        ^0.1.1  →   ^0.2.6
 webpack          ~1.9.10  →  ~1.10.5

Run with -u to upgrade your package.json

> ncu -u
```
