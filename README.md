# Google Docs to Markdown

This is a very minimal webapp for converting a Google Doc to Markdown. It uses [Remark](https://github.com/remarkjs/remark) and [Rehype](https://github.com/rehypejs/rehype) (both part of [Unified](https://unifiedjs.github.io)) to do the conversion.


## Live Demo

- https://bafybeiedsxa72m2id3iykq6vii3p4bxq6mavkntlfxxi3t2rbkb4k7pwia.ipfs.dweb.link/
- https://mr0grog.github.io/google-docs-to-markdown/

(Both are built from [5197803](https://github.com/Mr0grog/google-docs-to-markdown/commit/5197803fd8b444be5dc51666a6470a8c4fdecf48).)


## Install & Build

First make sure you have Node.js installed. Then:

1. In the directory where you have cloned this repository, run `npm install`:

    ```sh
    > cd /path/to/cloned/repo
    > npm install
    ```

2. For a one-time build, run:

    ```sh
    > npm run build
    ```
    
    …and the built output will be in the `dist` folder.
    
    To start a server with live rebuilding, run:
    
    ```sh
    > npm start
    ```
    
    Then point your browser to `http://localhost:9000` to see the site. It will automatically rebuild whenever you change any files.


## Contributors

This project is open source, and gets better with the hard work and collaboration of multiple people. Thanks to the following for their contributions:

<!-- ALL-CONTRIBUTORS-LIST:START -->
| Contributions | Name |
| ----: | :---- |
| [🚧](# "Maintenance") [💻](# "Code") [🚇](# "Infrastructure") [📖](# "Documentation") [👀](# "Reviewer") | [Rob Brackett](https://github.com/Mr0grog) |
| [💻](# "Code")  | [Peter Law](https://github.com/PeterJCLaw) |
| [📖](# "Documentation") [🚇](# "Infrastructure") | [Marcin Rataj](https://github.com/lidel) |
<!-- ALL-CONTRIBUTORS-LIST:END -->

(For a key to the contribution emoji or more info on this format, check out [“All Contributors.”](https://allcontributors.org/docs/en/emoji-key))


## License

GDoc2MD is open source software. It is (c) 2018-2021 Rob Brackett and licensed under the BSD license. The full license text is in the LICENSE file.
