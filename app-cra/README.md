# App created with create-react-app

The react app in this example does not work, since it tries to import from outside src
and the create-react-app configuration prevents it.

When you try to start the app with `yarn start` it will fail with this error:

```
Module not found: Error: You attempted to import ../../common/src/Shared which falls outside of the project src/ directory. Relative imports outside of src/ are not supported.
You can either move it inside src/, or add a symlink to it from project's node_modules/.
```

## Learning

Create-react-app prevents you from importing code from outside src.