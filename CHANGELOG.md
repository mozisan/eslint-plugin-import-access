## Changelog

### 1.1.1

- Removed check against imports from inside `node_modules`. (#6)

### 1.1.0

- Added a `defaultImportability` option with which you can use `@package` or `@private` as default importability of all exports in the project. (#5)

### 1.0.2

- Fix a bug that `export default` is not checked. (#2)
- Extend the file name pattern to consider as an index file. Previously only `index.ts` and `index.tsx` were considered as an index file. Now `index.js`, `index.mts`, etc. are also considered.

### 1.0.1

- Upgrade TypeScript to 4.5 (https://github.com/uhyo/eslint-plugin-import-access/pull/1)

### 1.0.0

No change from 1.0.0-beta.

### 1.0.0-beta

Initial release.
