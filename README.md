# Development setup

### Nodejs

You will need Node.js - Installing it gives you access to NPM. 
If you don't have the latest version, make sure you get it installed. Upgrading already installed Node.js is trough NPM :
 
```
$ sudo npm cache clean -f
$ sudo npm install -g n
$ sudo n stable 
```

If you have not installed Node.js yet then you will simply get the latest version and work from there.


### Gulp

To run the gulpfile.js you will need gulp-cli. Its best to install it globaly. The comand for that is `$ npm install --global gulp-cli`.

### Installing dependences

Run `$ npm install`. This will create `node_modules` folder. Don't worry, it is ignored from the .gitignore file. On windows deleting this would be rather tricky, so you will need another globally installed module named `rimraf`. For linux users its not an issue.

### Running the watch function

`Gulpfile.js` is taking care of the commands for watch, paths and settings. All you need is to run `$ gulp`.

## Note:

The theme is not 100% ready as there are still small changes to be made in the future. Some of the todos are renaming some of the scss files, better js compile/minification and imgming scripts. That is what's on the radar for now, most likley there will be more to be added/changed. If you have any ideas feel free to open an issue !
