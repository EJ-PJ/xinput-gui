# xinput-gui
A simple GUI for Xorg's Xinput tool.

| ![](https://user-images.githubusercontent.com/1174413/61573693-78d29000-aaa2-11e9-834c-2d7f35c765e3.png) | ![](https://user-images.githubusercontent.com/1174413/61573694-78d29000-aaa2-11e9-902f-7c5989cc43f8.png) |
| --- | --- |

xinput allows you to edit properties of devices like keyboards, mice, and touchpads. This GUI wraps around the xinput command to make editing them faster and more user-friendly.

## Installation

xinput-gui depends on Python 3.12+, GTK+ 3.20+, PyGObject, and xinput.

### Manual install
Clone this repository, then use one of the following commands:
 * #### uv
  Install it whit uv: `uv pip install .`
 * #### pip
  Install it whit pip: `pip install .`

### Other installs
At the moment I dont have any plans to port the installation to other distros or package managers since this branch (or repo) it s just for personal use. But you're totally free to port it or adapt it whatever you like.

## Usage

Just run `xinput-gui`. Selecting a device will list all of it's properties. When editing them, changes will be applied immediately.

For detailed usage instructions, information on development and contributing, and more, see the [documentation](docs/overview.md).
