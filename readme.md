## _Title_
	Epicodus- JavaScript - Journal
	
#### _Creator_
	Lilo Onwuzu 
	
#### _Date_
	05.23.2016

#### _Description_
	This site allows you to make journal entries 
	It is built with a html & js.
	The js back-end is written in an object oriented form with journal as the object/construct.
	All js code (band-end and front-end) is built in a modular form for simplicity during development.
	We will need some dependendencies - programs that will concatenate all our js code and package it into one file.
	A tool, Node Package Manager(npm) will help us install our back-end dependencies (e.g moment).
	Npm installs them into a new node_modules folder which is git ignored.
	Another tool, Bower Package Manager will help us manage our front-end dependencies (e.g JQuery and Bootstrap).
	Bower installs them into a new bower_modules folder which is git ignored.
	Another tool Gulp will help us automate these tasks (concatenating, minifying etc).
	Gulp will perform these tasks depending on the mode (development or production).
	The final js script will be save it in a new 'build' folder in a file 'app.js' (ignored in git) that is linked in our index.html file.
	We also use a gulp task to automate a development server (basically re-lauches the index.html in a browser) whenever there are changes in the development process for faster development time.
	
#### _Setup/Installation Requirements_
	Clone this repository
	Install npm (Node Package Manager)
	Install gulp (Task Manager)
	Install bower (Task Manager)
	In terminal in project root directory:
		Run 'npm install' to install all the back-end dependencies
		Run 'bower install' to install all the back-end dependencies
		Run 'gulp build' to run tasks in development environment
		Run 'gulp build --production' to run tasks in production environment

#### _Known Bugs_
 	None

#### _Support and contact details_
	lpr422@gmail.com
	
#### _Technologies Used_
	HTML, Object-Oriented Javascript, Node js, Node Package Manager(npm), Bower Package Manager, Gulp Task Manager, 
	Development Server

#### _License_
	This software is licensed under the MIT license
	Copyright (c) 2016 IPONWUZU


