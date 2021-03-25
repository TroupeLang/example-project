# Troupe development container example

## Summary

*This is an example project that uses VS Code development containers for executing Troupe code.*

## Using this project

Just follow these steps:

1. Follow the [getting started steps](https://aka.ms/vscode-remote/containers/getting-started) to set up your machine.
1. Clone this repository.
1. Open this project in VS Code.
1. Press <kbd>F1</kbd> and run **Remote-Containers: Reopen in Container** to open this folder in a docker container with Troupe installed
1. The terminal in VS Code is now set up such that `$TROUPE` points to the Troupe installation and the path contains the scripts `local.sh` and `network.sh`.
    You can therefore run the examples provided here by typing e.g `local.sh helloworld.trp` or `network.sh helloworld.trp` in the VS Code terminal.
