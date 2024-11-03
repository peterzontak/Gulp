# Simple Gulp Testing Application

This is a simple Gulp-based application that demonstrates how to automate the build process for TypeScript and SCSS files. It includes tasks for compiling TypeScript into JavaScript and SCSS into CSS, along with a watch functionality that automatically recompiles files on changes.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Tasks](#tasks)

## Features

- Compiles TypeScript files to JavaScript
- Compiles SCSS files to CSS
- Automatically watches for changes in source files
- Generates source maps for easier debugging

## Prerequisites

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (version 12.x or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)

## Installation

1. npm install
2. gulp

## Tasks:

1. scripts: Compiles TypeScript files from the src/ts directory into JavaScript and outputs them to dist/js.
2. styles: Compiles SCSS files from the src/scss directory into CSS and outputs them to dist/css.
3. watch: Watches for changes in TypeScript and SCSS files and automatically recompiles them.
4. default: Runs both scripts and styles tasks and starts watching for changes.

