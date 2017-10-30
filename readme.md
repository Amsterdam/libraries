# Libraries and versions CDN for the City of Amsterdam

This repo serves as a CDN for libraries and dependencies used in City of Amsterdam projects.

## Hosting libraries

The libraries and dependencies can be added to this repo through a pull request.

The folder structure for this repo is `[library-name]/v[version-number]` so that we can support old versions as well as new ones.

If you are using a certain version, please put a `readme.md` file in the folder with a note on where it is used in case future contributors might have any questions.

### Example

Say you are hosting the `x3` library version 0.1, it should go in to folder `x3/v0.1` and will be available from `//amsterdam.github.io/libraries/x3/v0.1/`.