# Read me
This is an Angular/Sass boilerplate based on Angular 1.4 version, it uses Gulp as a build tool, it's still a work in progress and is based on this [Angular boilerplate] and will probably be subjected to change over time.

## About the boilerplate
The boilerplate has no predefined style/way of usage. It's uses the following tools:
- Gulp
- Browserify
- ESLint
- SASS
- Autoprefixer
- LiveReload

## Installation and usage
To install and start the live server use the following commands:
```sh
git clone https://github.com/davorbadrov/angular-boilerplate.git [project dir]
cd [project dir]
npm install
gulp # after running gulp you can access the app on localhost:5000
```
The Gulp configuration works by watching and building all the views, scripts and styles, and copying them into the dist folder which is server over Express/LiveReload, default address is localhost:5000 but can be changed in the *gulpfile.js*.

# License
[ISC license]

[angular boilerplate]:https://github.com/Hyra/angular-gulp-browserify-livereload-boilerplate
[ISC license]:http://opensource.org/licenses/ISC
