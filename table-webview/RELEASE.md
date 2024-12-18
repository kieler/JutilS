To release a new version:
1. update the version number in the `package.json` manually or use `npm version <major/minor/patch>` and commit.
2. Make sure the lib files are built using `yarn build`.
3. Publish the new version to npm using `npm publish`.