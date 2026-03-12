## To make a new release of this package

- Update the version in package.json,
- Make your changes,
- Make a PR and have it merged to main on https://github.com/session-foundation/session-react-contexify,
- Once merged, draft a new release on https://github.com/session-foundation/session-react-contexify/releases,

Run those:

```sh
yarn build && npm pack
```

This should build a `.tgz` file, this is what you need to upload to the release on github.
