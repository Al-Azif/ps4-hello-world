# Hello World!

This is a repo to demonstrate the [Open Orbis Toolchain Action](https://github.com/OpenOrbis/toolchain-action). This means you can add a few lines to a Github workflow file to use components from the toolchain on Github Actions, no need to install anything locally on your machine. This can be used to test pulls, build releases, etc.

You can view the example workflow file [here](https://github.com/Al-Azif/ps4-hello-world/blob/main/.github/workflows/build.yml) and view the completed actions with their output [here](https://github.com/Al-Azif/ps4-hello-world/actions).

There is a `devcontainer.json` for use in the VS Code [Remote Container Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) located [here](https://github.com/Al-Azif/ps4-hello-world/blob/main/.devcontainer/devcontainer.json). This allows for opening the workspace to automatically start a Docker container and setup a remote development environment just by opening the workspace/folder in VS Code. This can have it's own separate extensions and setting from your system-wide VS Code install. Basically it's a complete IDE and toolchain in it's own compartmentalized container separate from the rest of your stuff. As an example it installs/uses clang-format and changes some settings.

Also include is a `tasks.json` file to add "Build to PKG" as a 1-click (Or key combo) compilation in VS Code located [here](https://github.com/Al-Azif/ps4-hello-world/blob/main/.vscode/tasks.json).
