Entry point for Node CLI apps

## Installation

```shell
npm i vbarbarosh/node-cli
```

## Basic usage

```javascript
#!/usr/bin/env node

import cli from '@vbarbarosh/node-cli';

cli(main);

async function main()
{
    console.log('Hello...');
}
```
