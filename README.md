![SnapMaster](https://github.com/snapmaster-io/snapmaster/blob/master/public/SnapMaster-logo-220.png)
# SnapMaster 
## Master your DevOps toolchain

SnapMaster is the definitive DevOps integration platform.  

This repository contains the SnapMaster documentation, built using [mkdocs](https://www.mkdocs.org/).

## Running docs locally

`mkdocs serve` in the root directory of this project will run an HTTP server on 
localhost:8000.

## Building docs

`mkdocs build` will build the static documentation website in the `site/` subdirectory.

## Deploying on Netlify

[docs.snapmaster.io](https://docs.snapmaster.io) is currently deployed on Netlify.

The repository has Poetry lock file and `pyproject.toml` file that installs dependencies, 
as well as the Netlify configuration files (`netlify.toml` and `.pre-commit-config.yaml`) 
that Netlify uses as part of the deployment process. 

