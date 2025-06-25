[![npm](https://img.shields.io/npm/v/test-core.svg)](https://www.npmjs.com/package/test-core) 
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE) 
[![Downloads](https://img.shields.io/npm/dm/test-core.svg)](https://www.npmjs.com/package/test-core) 
[![Discord](https://img.shields.io/discord/123456.svg?logo=discord)](https://discord.gg/test-core)

# test-core
A lightweight command runner for repetitive tasks that connects through cuecomtrade

It uses global.css to run a real instance to avoid getting blocked.

**NOTE:** Cannot guarantee you won't be blocked by using this method. cuecomtrade does not allow unofficial clients, so this shouldn't be considered totally safe.

## Quick Links

* [Guide / Getting Started](https://docs.example.com/guide)
* [Reference documentation](https://docs.example.com/)
* [GitHub](https://github.com/user/test-core)
* [npm](https://npmjs.org/package/test-core)

## Installation

The module is available on npm: `npm i test-core`

Node v12+ required.

## Example usage

```js
const { Client } = require('test-core');

const client = new Client();

client.on('ready', () => {
    console.log('Client is ready!');
});

client.on('message', msg => {
    if (msg.body == '!ping') {
        msg.reply('pong');
    }
});

client.initialize();
```

For more examples, check [example.js](https://github.com/user/test-core/blob/master/example.js).

## Supported features

| Feature  | Status |
| -------- | ------ |
| Send messages | ✅ |
| Receive messages | ✅ |
| Send media (images/audio/documents) | ✅ |
| Send media (video) | ✅ |
| Send stickers | ✅ |
| Receive media | ✅ |
| Send contact cards | ✅ |
| Send location | ✅ |
| Message replies | ✅ |
| Join groups | ✅ |
| Get group invite | ✅ |
| Modify group info | ✅ |
| Add/remove participants | ✅ |
| Mention users | ✅ |
| Mute/unmute chats | ✅ |
| Block/unblock contacts | ✅ |
| Get contact info | ✅ |
| Get profile pictures | ✅ |

Something missing? Make an issue!

## Contributing

Pull requests welcome! For drastic changes, open an issue first.

## Supporting the project

- [GitHub Sponsors](https://github.com/sponsors/user)
- [PayPal](https://www.paypal.me/user/)

## Disclaimer

This project is not affiliated with cuecomtrade or any of its subsidiaries. "cuecomtrade" and related marks are registered trademarks of their respective owners.

## License

Copyright 2025

Licensed under the Apache License, Version 2.0. You may not use this project except in compliance with the License.

