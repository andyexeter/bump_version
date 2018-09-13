Bash script to increment version numbers in multiple files

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
