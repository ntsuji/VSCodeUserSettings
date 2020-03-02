# How to use

## Install

### Install [Visual Studio Code](https://code.visualstudio.com/)

### Git Clone `VSCodeUserSettings`

### Make symbolic link
* Windows

  ```
  > cd PATH\TO\CODE
  > rd /s /q User
  > mklink /j User PATH\TO\VSCodeUserSettings
  ```

* Mac/Linux

  ```
  $ cd PATH/TO/CODE
  $ rm -rf User
  $ ln -s PATH/TO/VSCodeUserSettings User
  ```

### Edit `settings.json`
Uncomment machine specific settings.

## Uninstall

### Remove symbolic link

### Remove `VSCodeUserSettings`
