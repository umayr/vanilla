# Vanilla
> vanilla javascript sandbox with webpack, eslint, sass and babel.


Sometimes you need to test a few things in browser, or write a web app without any frameworks or libraries (if you 
prefer), this could be a starting point. 

It comes with a minimal webpack configuration with support for babel, eslint and sass.

To get it running:
```bash
    # clone the repository
    λ git clone git@github.com:umayr/vanilla.git
    # change current directory
    λ cd vanilla
    # remove .git folder (in case you don't want to this repository's commits)
    λ rm -rf .git
    # install dependencies
    λ yarn install
```

There are only two project commands that could be executed with either `yarn` or `npm`:

```bash
    # build - creates a new webpack build
    webpack --mode=production
    # start - runs the webpack dev server with HMR
    webpack-dev-server --inline --progress --mode=development
```

And that's it. 