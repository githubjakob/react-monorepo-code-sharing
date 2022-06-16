# App with react-app-rewired

The react app in this example imports a component from a common folder outside of src.

This is possible because the create-react-app configuration is changed using react-app-rewired 
together with react-app-rewire-alias.

## react-app-rewire-alias configuration

In order to change the configuration, these steps are needed:

1. Install react-app-rewired  & react-app-rewire-alias 
2. Change scripts in package.json to use react-app-rewired 
3. Add the configuration according to the docs in the files config-overrides.js, jsconfig.json & jsconfig.paths.json

Note that config-overrides.js uses `aliasDangerous` in order to import from outside src.

Also note that