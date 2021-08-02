Entry point for Node CLI apps

## Installation

```shell
npm i @vbarbarosh/node-cli
```

## Basic usage

```javascript
#!/usr/bin/env -S node -r esm

import cli from '@vbarbarosh/node-cli';

cli(main);

async function main()
{
    console.log('Hello...');
}
```

## References

* https://www.npmjs.com/package/@vbarbarosh/node-cli
