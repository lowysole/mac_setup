# MAC setup for development

Run the installer:

`sudo bash setup.sh`

## Group of roles

Everything is grouped in the following roles:

* Utility: Collection of daily used programs.
* Development: Everything related to my development workflow; editor, configs, libraries, database clients,
  profilers, etc.

## Customization

* `group_vars/all`: Specify the binary versions, repositories and local username.
* `vars/roles`: Select which roles will be installed.

