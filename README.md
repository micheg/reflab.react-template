# Basic React Template

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### bin/install

create the node virtual environment and install the dependencies

### bin/build

create the minified js ready to be deployed

### bin/deploy

create dist folder and related files

### to start from here

fork the project and adjust the relative configurations in profiles/env, the packages in package.json and the relative proxy

    vim package.json
    vim profiles/env/env.dev.local
    ln -s profiles/env/env.dev.local .env.development.local
    ln -s profiles/env/env.build.dev_server .env.production
