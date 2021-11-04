# npm prepare test repo

This repo is for testing a dependency installed directly from git to ensure that `npm prepare` is run automatically during installation. To test try installing this package using any of the following commands:

- `npm install DesignByOnyx/npm-prepare-test`
- `npm install https://github.com/DesignByOnyx/npm-prepare-test/tarball/main`

The thing you want to look for is to make sure a `dist` folder was created inside `node_modules/npm-prepare-test`.
