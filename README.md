# typed-octicons

`typed-octicons` is a typed wrapper of [GitHub Octicons](https://www.npmjs.com/package/octicons) for TypeScript.

## Install

```
$ npm install typed-octicons --save
```

## How to use

```typescript
import octicons from "typed-octicons";

const svg = octicons["bell"].toSVG();
```

## How to build

requires: [Node.js](https://nodejs.org/), [TypeScript Compiler](https://www.npmjs.com/package/typescript)

`tsc -P .` or `tsc -P . -w`

### In VS Code

You can use automatic build. Run `Tasks: Allow Automatic Tasks in Folder` command from command palette ( Mac: <kbd>F1</kbd> or <kbd>Shift</kbd>+<kbd>Command</kbd>+<kbd>P</kbd>, Windows and Linux: <kbd>F1</kbd> or <kbd>Shift</kbd>+<kbd>Ctrl</kbd>+<kbd>P</kbd>), and restart VS Code.

## License

[Boost Software License](./LICENSE_1_0.txt)
