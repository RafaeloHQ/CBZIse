# CBZIse
An automation script to turn a directory of images into a single .cbz archive

---
# Script Setup
To make the script usable universally in your system, do the following procedure:

- Give permission to the scripts
> sudo chmod +x CBZise \
> sudo chmod +x BatchCBZ

 - Move the scripts to a directory accessible via Environmental Variables, such as /usr/bin
> mv CBZise /usr/bin/CBZise \
> mv BatchCBZ /usr/bin/BatchCBZ


---
# Usage

- CBZise
> CBZise `<directory>`

where **`<directory>`** only contains images and no subdirectory. If it does contain subdirectories, it will be ignored by the script.

- BatchCBZ
> BatchCBZ `<directory>`

where **`<directory>`** must contain subdirectories with images. This batch script uses CBZise, so make sure it is accessible globally.

---
# Development purposes
This script can be used to quickly convert a bunch of directories with manga/comic panels into a packed CBZ archive for easy of organization. This was developed as a coding exercise as well, where no external assistance was used besides trying to find what Bash command retrieves only the file name from a realpath directory. Happy to say, I'm satisfied.
