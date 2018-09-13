Bash script to increment version numbers in multiple files

This script was initially a [Gist](https://gist.github.com/andyexeter/da932c9644d832e3be6706d20d539ff7) I had created but has been
converted a full repo so it can be cloned and used as a submodule for different projects.

## Installation

Copy `bump_files.sh.dist` to `bump_files.sh` and edit files to bump in the newly created file.

## Usage 

Increment a semver version part by one:

```
$ ./bump_version.sh <major|minor|patch>
``` 

Fine grained control:

```
$ ./bump_version.sh <version-from> <version-to>
``` 

## License

Released under the [MIT license](LICENSE)
