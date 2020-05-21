# scripts
Useful free-to-use scripts.

## install-opencv
This script is based on the original code from [milq](https://github.com/milq/milq).
It provides a simple installation of OpenCV from source for Debian and Debian based Linux distributions (e.g. Ubuntu).

It also enables -DOPENCV_ENABLE_NONFREE:BOOL flag in case you want to install the extra contrib modules.

You can change options such as OpenCV version to install and installation of the extra modules in the first lines of the script.

```
# -------------------------------------------------------------------- |
#                       SCRIPT OPTIONS                                 |
# ---------------------------------------------------------------------|
OPENCV_VERSION='3.4.9'       # Version to be installed
OPENCV_CONTRIB='YES'          # Install OpenCV's extra modules (YES/NO)
# -------------------------------------------------------------------- |
```
