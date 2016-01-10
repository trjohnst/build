# Build
## Usage
`node ./path/to/build/build.js`

## Troubleshooting
Currently the build only works with a very distinct file structure. Future builds will export the build functionality as a JavaScript object with the ability to pass in a configuration specifying project structure.
```
|-src
| |-assets
|   |-css
|   |-js
|-dist
  |-assets
    |-css
    |-js
```

This has only been run and tested with node at `v5.2.0` but feel free to try it with other versions.

## Backlog
* Have build export itself and be configurable to be used with different project schemas
* Make a better watcher
* refactor build to be glob based instead of distinct files

