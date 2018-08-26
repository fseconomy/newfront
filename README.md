# New FSEconomy Web Frontend

The purpose of this project is to develop a new web frontend for the FSEconomy Game World.
We're seeking to achieve the following design goals:

* Improved responsiveness
* Enhanced accessibility
* Improved user experience on touch screen devices
* Improved visualisation and navigation of data
* Improved technical maintainability

## Online Preview

The static website built from this repository is publicly accessible [on Heroku](https://fse-front.herokuapp.com/).
This preview represents the state of the blessed repository's
[master](https://github.com/fseconomy/newfront/tree/master) branch, using continuous deployment.

## Development

Working on this project follows a specific workflow, relying on automation tools such as
[gulp](https://gulpjs.com/). Follow the steps described below to get up and running:

### Prerequisites

* [node.js](https://nodejs.org/en/) (8.x recommended)
* [npm](https://www.npmjs.com/get-npm) (5.7 or newer recommended)
* [gulp 4](https://gulpjs.com/) installed globally (`npm install -g gulp@^4.0`)

### Build Process

* Run `npm install` to retrieve all dependencies
* Use `gulp` to build the website (result in `./public`)
* Use `gulp dev` to build website dynamically, run it in browser and monitor files for changes.

The second option is what you want most of the time when working on the source code of this project.

### Contributing

We gladly accept contributions, fixes and improvements. To submit them, fork the repository, commit your changes
to a feature branch within your fork, and create a pull request.
