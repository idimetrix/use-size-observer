# use-size-observer
A custom React hook that leverages the ResizeObserver API to track and measure the dimensions of an element.

## Installation

To install the package, use npm:

```bash
pnpm add use-size-observer

yarn install use-size-observer

npm install use-size-observer
```

## Usage

```typescript
import { useSizeObserver } from 'use-size-observer';

const [ref, size] = useSizeObserver();

console.log(size);

return <div ref={ref}>...</div>
```

## tsup
Bundle your TypeScript library with no config, powered by esbuild.

https://tsup.egoist.dev/

## How to use this
1. install dependencies
```
# pnpm
$ pnpm install

# yarn
$ yarn install

# npm
$ npm install
```
2. Add your code to `src`
3. Add export statement to `src/index.ts`Message
4. Test build command to build `src`.
Once the command works properly, you will see `dist` folder.

```zsh
# pnpm
$ pnpm run build

# yarn
$ yarn run build

# npm
$ npm run build
```
5. Publish your package

```zsh
$ npm publish
```


## test package
https://www.npmjs.com/package/use-size-observer
