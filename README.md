# 
This project is created using _`Gulp, Gulp SASS and Browsersync`_. 

To run the code on your local dev environment, use **`$gulp`** command when in the project folder.

## Prerequisites of running the code on your local dev environment are as below

1. NodeJS
2. Gulp
3. Browser-sync

### To install gulp, gulp-sass and browser-sync, use the following command in your Node CLI

**`npm install gulp gulp-sass browser-sync --save-dev`**

>The above command will update you package.json with dependencies in your dev environment.

## Project Hierarchy

* _`src`_ folder contains all the images, stylesheets and script files
* For SCSS, there are two folder that contains Base SCSS and Module SCSS 
* Global colors are defined in _`variables.scss`_ partial
* _`main.scss`_ imports all the modules for easy debugging and maintenance