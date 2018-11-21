## Learning React.js 

[Lynda's React.js Essential Training](https://www.lynda.com/React-js-tutorials/React-js-Essential-Training/496905-2.html)


### Commands to remember

* `npm init` to create package.json

### Webpack

* create a `webpack.config.js` that will define everything that will be done to streamline the transpiling of all JS files in your project. In this file you will have a specified `entry`, `output`, `devServer` == enables hot reloading, `module` and embedded `loaders`
* `npm install webpack@1.13.3 --save-dev` 
* `npm install -g webpack@1.13.3` to  be able to run `webpack` command
* `npm install webpack-dev-server@1.16.2 --save-dev` 

#### Loading json with webpack

* `npm install json-loader@$relevantRelease --save-dev`

#### Loading css with webpack

*  `style-loader!css-loader!autoprefixer-loader`
*  `npm install autoprefixer-loader@$relevantRelease --save-dev`
*  `npm install css-loader@$relevantRelease --save-dev`
*  `npm install style-loader@$relevantRelease --save-dev`

#### Loading scss to css with webpack

*  `style-loader!css-loader!autoprefixer-loader!sass-loader`
*  `npm install sass-loader@$relevantRelease --save-dev`
*  `npm install autoprefixer-loader@$relevantRelease --save-dev`
*  `npm install css-loader@$relevantRelease --save-dev`
*  `npm install style-loader@$relevantRelease --save-dev`

### Babel

* `<script type="text/javascript" src="bundle.js"></script>` included in main html file, `index.html` to access browser ready files
* `npm install babel-cli@6.18.0 --save-dev` to install babel cli in the project so that pre-production build of jsx can occur. Prep of files for the browser 
* .babelrc file must include presets 
* `npm  install babel-preset-react@6.16.0 --save-dev` Babel presets/dependencies 
* `babel $source/file.js --out-file $destination/bundle.js` to transpile for the browser

#### Webpack 1

* `npm install babel-loader@6.2.5 --save-dev`
* `npm  install babel-preset-latest@6.16.0 --save-dev` Babel presets/dependencies 
* `npm  install babel-preset-stage-0@6.16.0 --save-dev` Babel presets/dependencies 

#### Webpack 3

* [Webpack 3 configuration](https://www.lynda.com/React-js-tutorials/Migrating-webpack-3/496905/663728-4.html?autoplay=true)
* create a `webpack.config.js` specfic for webpack 3 that will define everything that will be done to streamline the transpiling of all JS files in your project. In this file you will have a specified `entry`, `output`, `module` and embedded `rules`
* `.babelrc` presets are `env` and `react`
* `npm install babel-loader@6.2.5 --save-dev`

### React and ReactDOM Dependencies 

* `npm install react@15.3.2 --save` and `npm install react-dom@15.3.2 --save` which will enable you to not have to include the cdnjs scripts in your main `index.html` file


### React + Firebase

[A Firebase in React Tutorial for Beginners](https://www.robinwieruch.de/complete-firebase-authentication-react-tutorial/)