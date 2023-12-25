## What is this

A simple cjs wrapper to the [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) module

## Why make a wrapper ?

Since version 5 of escape-string-regexp, the module [only supports esm import](https://github.com/sindresorhus/escape-string-regexp/commit/aebb6e8e5cc904e7f8db20445ff0879c40d34db0).
In order to continue using this module conveniently I decided to wrap it in [fix-esm](https://www.npmjs.com/package/fix-esm).

## Why declare escape-string-regexp as a peer dependency ?

Doing this allows you to decide the version of escape-string-regexp in your project.
