# crisp-style

A set of standard styles for use in web-based projects.

## Basic use

You need to import the library using:

```
npm install --save crisp-style
```

Then you need to import the library into your project, preferably in the main.js file:

```
import CrispStyle from 'crisp-style';
```

## Updating in NPM

Since we are already up and running you can add components as necessary into "./components". Make sure to do so in a branch, and then commit and create a PR.

You simply have to run the build script, then publish.

```
npm run build-bundle
```

Once you are ready to publish, bump the version and publish to npm using:

```
npm publish --access public
```
