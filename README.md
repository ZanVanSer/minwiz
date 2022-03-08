

# lightweight website under 2 KB based on MinWiz

## Getting started

Make sure you have Node and npm installed. Any version will do.

If you're doing web development you probably already have gulp-cli globally installed (you can test with `gulp -v`). If you don't have it, run `npm install --global gulp-cli`

- clone the repo
- install the dependencies with `npm install`
- build the site (in the _dist_ folder) with `npm run build`
- at this point, the _dist_ folder contains all assets in a minified form, ready to be copied/deployed to your web hosting service

If you want to live edit the site, there is a handy-dandy `gulp dev` command and the Live Server extension for VS Code is configured to open the site from _dist_ folder. Run the command, click _Go Live_ in the status panel of VS Code and you're good to go.
