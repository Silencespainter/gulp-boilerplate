# :zap: Gulp Boilerplate

## Instructions for the boilerplate

* Clone the repository.

* Use this command to install all dependencies for the project:

```bash
# Uses package.json "devDependencies" to install dependencies
npm install
```

* Start `gulp` by running:

```bash
npm start
```

## Folder structure

* `statics` - The converted files that are linked via `index.html`. You don't have to touch these files
    - Converted `js`-file - script.min.js
    - Converted `css`-file - style.min.css
* `js` - This is where your development-files are. All unconverted `js`-files
* `scss` - This is where your development-files are. All unconverted `scss`-files
* `Gulpfile.js` - This config file must be in the root-folder
* `index.html` - The index must be in the root-folder
* `package.json` - All the dependencies and config for the project


## Dependencies used in this boilerplate

* [gulp](https://www.npmjs.com/package/gulp)
* [gulp-sass](https://www.npmjs.com/package/gulp-sass)
* [gulp-rename](https://www.npmjs.com/package/gulp-rename)
* [browser-sync](https://www.npmjs.com/package/browser-sync)
* [gulp-postcss](https://www.npmjs.com/package/gulp-postcss)
* [autoprefixer](https://www.npmjs.com/package/autoprefixer)
* [gulp-babel](https://www.npmjs.com/package/gulp-babel)
* [babel-preset-env](https://www.npmjs.com/package/babel-preset-env)
* [browserify](https://www.npmjs.com/package/browserify)
* [babelify](https://www.npmjs.com/package/babelify)
* [gulp-util](https://www.npmjs.com/package/gulp-util)
* [vinyl-source-stream](https://www.npmjs.com/package/vinyl-source-stream)