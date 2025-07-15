# ztrun
ZTRun is a simple and fast zero-trust runtime that allows projects to be run inside VMs with just one configuration file.

Main features:
- Safety as focus
- Easy to integrate with Docker images
- OS bootstrapping for faster boot times
- VM suspension 
- Ability to disable networking conncetions
- Ability to auto-export files from the VM to the host machine

## How to build

1. Clone the repo
2. Run `cd ztrun && cargo install --release`

## Create & Run a project

1. Run `ztrun create` to create ZTRun.toml
2. Fill the ZTRun.toml configuration file with the relevant informations
3. Run `ztrun run` to launch up an isolated VM with your project running
