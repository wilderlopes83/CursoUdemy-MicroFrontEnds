#instalação do webpack
In the upcoming lecture, we will be installing our dependencies. We will need to install a slightly different version of webpack-cli and html-webpack-plugin to avoid some errors:

npm install webpack@5.4.0 webpack-cli@4.5.0 webpack-dev-server@3.11.0 faker@5.1.0 html-webpack-plugin@5.1.0

If you have already installed an older version and get an error like this:

Class constructor ServeCommand cannot be invoked without 'new'

or

TypeError: cli.isValidationError is not a function

You will need to update the webpack-cli and html-webpack-plugin versions in your package.json:

    "webpack-cli": "^4.5.0",

    "html-webpack-plugin": "^5.1.0",

Then, delete your node_modules and package-lock.json files and run a new npm install


#######