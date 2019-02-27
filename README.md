# Build Infrastructure #

A number of repositories in the OME organization represent
super-projects solely intended to tie together their submodules
for the purposes of building interdependent code. For example:

 - https://github.com/ome/ansible-roles
 - https://github.com/ome/bio-formats-build/
 - https://github.com/ome/omero-build
 - https://github.com/ome/omero-gradle-plugins
 - https://github.com/ome/omero-plugins

 The scripts in this repository represent the common functionality
 needed to make those repositories work.

## Requirements ##

- `pip install scc`

## Usage ##

Participating super-projects should take the following steps:

 - add this repository as a submodule
 - create a `repositories.yml` at the top-level
