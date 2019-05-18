# bash-scripts
All scripts should follow [googles shell style guide](https://google.github.io/styleguide/shell.xml)

## List of scripts
#### imageRename
Renames image files using their exif timestamp within the filename. If
exif timestamp is not availabel the script uses the last modification
timestamp instead. In case of filename collision a counter is added.

#### toggleTouchpad
Script to de-/activate a touchpad on Xubuntu. Each execution toggles
the current touchpad status and displays a notification
