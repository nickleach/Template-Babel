## Welcome to My Angular Project

> I am your Readme.md file, you should probably update me.


## Usage

This template contains some simple `gulp` tasks. They are as follows:

- `gulp watch`: This will launch a Node Server and start the standard `watchlist` task
- `gulp bower`: This will move the bower components into their proper location. This will run during the `watch` task, but you may need to run it manually once in a while


## Babel

This template is set up to make use of ES2015 (ES6) and using Babel as a transpiler. Since we are not using `wiredep` or other tool, you'll need to manually specify your scripts in the order you want them concatenated in the `scripts.json` file. Also, because of this, you will no longer need to add any scripts to your `index.html` file other than your vendor files, which should never be transpiled.

```json
{
  "scripts" : [
    "app/js/main.js",
    "app/js/views/mainView.js",
    "app/js/controllers/mainCtrl.js"
  ]
}
```

## Lastly

There are many more tasks, and you really should read through the `gulpfile.js`, but the ones above will take care of you in most cases.
