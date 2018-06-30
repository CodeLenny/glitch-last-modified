# Glitch Last Modified

Testing how best to determine the time of last import.

## Usage

It looks like the "modified time" of any file (this repo is using `package.json`, which has never been changed)
will be the time of last import.

Importing from GitHub if there are no changes doesn't seem to modify the "modified time" of files.
