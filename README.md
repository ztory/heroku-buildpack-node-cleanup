# heroku-buildpack-node-cleanup

Deletes the node_modules folder to decrease slug size.

## Usage

    $ heroku buildpacks:set https://github.com/ztory/heroku-buildpack-node-cleanup.git

Or add it to the .buildpacks file if using [heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi):

    $ cat .buildpacks
    ...
    https://github.com/ztory/heroku-buildpack-node-cleanup.git
