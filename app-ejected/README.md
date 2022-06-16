# App with ejected configuration

The react app in this example imports a component from a common folder outside of src.

The app has CRA ejected and manually changed the webpack confugration to allow the import.

Specifically, these webpack configurations have to be changed in webpack.config.js:

- add common to the ModuleScopePlugin to allow the import
- add common as an alias in resolve.alias
- add common to the babel plugin  
