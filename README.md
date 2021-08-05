# Library Playlists

A module for [Library](https://github.com/openaudioserver/library) that adds normal and smart playlists.  Smart playlists use rules to filter your content.

### Documentation

- [How to use](#how-to-use)
- [Index data structure](#index-data-structure)
- [Using the API with NodeJS](#using-the-media-index-with-nodejs)

## How to use

First install the module with `NPM`:

    $ npm install @openaudioserver/library-playlists

If you are using [Library](https://github.com/openaudioserver/library) from the command-line include the module name in your arguments:

    $ node scanner.js @openaudioserver/library-playlists /path/to/files

If you are using [Library](https://github.com/openaudioserver/library) with NodeJS include the module name in the parameters:

    const Library = require('@openaudioserver/library')
    await Library.scan(['@openaudioserver/library-playlists'], ['/path/to/files'])

## Index data structure

[Top of page](#documentation)

## Using the API with NodeJS

[Top of page](#documentation)

## License

MIT
