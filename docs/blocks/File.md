---
title: File
description: Documentation for built-in File blocks in Sketchware Pro.
sidebar_position: 6
slug: file
tags:
 - Blocks
 - Built-in 
 - File
---

In Sketchware Pro, File blocks let you read, write, copy, move, and delete files on the device. They also include powerful image editing tools to crop, rotate, resize, and apply effects to pictures saved on the phone.

:::important All File Access Required
On devices running Android 11 or above, you need to ask the user for permission to access the folder you are changing/reading or all file access permission to use most of these blocks. 
:::

# Built-in File Blocks

### read file path []
![read file path](assets/file/read-file-path.png)

Reads the entire text content saved inside a text file at the given file path. Returns the file's contents as a string.

### write String [] to file path []
![write string to file path](assets/file/write-string-to-file-path.png)

Saves a string of text into a file at the specified file path. If the file does not exist, it will be created automatically. If it already exists, its previous content is replaced.

### copy file path [] to path []
![copy file path to path](assets/file/copy-file-path-to-path.png)

Copies a single file from its current path to a new destination path. The original file remains untouched.

### copy dir path [] to path []
![copy dir path to path](assets/file/copy-dir-path-to-path.png)

Copies an entire folder (directory) and all the files inside it into another destination folder.

### move file path [] to path []
![move file path to path](assets/file/move-file-path-to-path.png)

Moves a file from one folder to another. This removes the file from its old location and places it in the new one.

### delete file path []
![delete file path](assets/file/delete-file-path.png)

Permanently removes/deletes a file or directory at the specified path.

### rename file path [] to []
![rename file path to](assets/file/rename-file-path-to.png)

Renames an existing file or folder to a new name.

### is exist file path []
![is exist file path](assets/file/is-exist-file-path.png)

Checks if a file or directory actually exists on the phone at the given path. Returns `true` if it exists, otherwise `false`.

### make directory path []
![make directory path](assets/file/make-directory-path.png)

Creates a brand-new folder (directory) on the phone's storage.

### file list in path [] to List String: [list]
![file list in path to list string](assets/file/file-list-in-path-to-list-string.png)

Scans a folder and automatically adds the file paths of all files found inside it into a List String variable.

### path [] is directory
![path is directory](assets/file/path-is-directory.png)

Checks whether the given path points to a folder (directory). Returns `true` if it is a directory, otherwise `false`.

### path [] is file
![path is file](assets/file/path-is-file.png)

Checks whether the given path points to a regular file (rather than a folder). Returns `true` if it is a file, otherwise `false`.

### get length of path []
![get length of path](assets/file/get-length-of-path.png)

Returns the size of a file in bytes. Useful for checking file download sizes or file weights.

### starts with []
![starts with](assets/file/starts-with.png)

Checks if a file path or text starts with a specific prefix string. Returns `true` or `false`.

### ends with []
![ends with](assets/file/ends-with.png)

Checks if a file path ends with a specific file extension (like `".png"` or `".txt"`). Returns `true` or `false`.

### get last segment path of []
![get last segment path of](assets/file/get-last-segment-path-of.png)

Extracts just the file name (or the last folder name) from a full file path. For example, for `/sdcard/Download/song.mp3`, it returns `"song.mp3"`.

### get external storage directory
![get external storage directory](assets/file/get-external-storage-directory.png)

Returns the primary path to the user's external device storage (usually `/storage/emulated/0` or `/sdcard`).

### get package data directory
![get package data directory](assets/file/get-package-data-directory.png)

Returns the private internal storage path belonging specifically to your app (`/data/user/0/<your.package.name>/files`).

### get public directory type directoryType: [type]
![get public directory type](assets/file/get-public-directory-type.png)

Returns the standard system path to common public user folders on Android, such as Downloads, Music, DCIM (Photos), or Documents.

### resize image retain ratio from path [] to path [] max ()
![resize image retain ratio](assets/file/resize-image-retain-ratio.png)

Resizes an image while preserving its original aspect ratio (shape) so the picture doesn't get stretched or distorted.

### resize image to square from path [] to path [] max ()
![resize image to square](assets/file/resize-image-to-square.png)

Resizes an image into a perfect square of the chosen maximum pixel size.

### resize image to circle from path [] to path []
![resize image to circle](assets/file/resize-image-to-circle.png)

Crops and masks an image into a clean circle shape. Great for making circular user profile avatars.

### resize image rounded from path [] to path [] round ()
![resize image rounded](assets/file/resize-image-rounded.png)

Gives an image smooth, rounded corners based on the chosen corner radius number.

### crop image center from path [] to path [] width () height ()
![crop image center](assets/file/crop-image-center.png)

Crops an image starting directly from its center point using the specified width and height.

### rotate image from path [] to path [] angle ()
![rotate image](assets/file/rotate-image.png)

Rotates an image by a chosen angle in degrees (e.g., `90°`, `180°`, `270°`).

### scale image from path [] to path []
![scale image](assets/file/scale-image.png)

Scales the dimensions of an image up or down.

### skew image from path [] to path []
![skew image](assets/file/skew-image.png)

Slants or skews an image along its X and Y axes for stylized perspective effects.

### set image color filter from path [] to path [] color ()
![set image color filter](assets/file/set-image-color-filter.png)

Applies a colored tint or filter over an image file.

### set image brightness from path [] to path [] value ()
![set image brightness](assets/file/set-image-brightness.png)

Adjusts how bright or dark an image file looks.

### set image contrast from path [] to path [] value ()
![set image contrast](assets/file/set-image-contrast.png)

Adjusts the contrast (the difference between light and dark areas) of an image file.

### get jpeg rotate from file path []
![get jpeg rotate](assets/file/get-jpeg-rotate.png)

Reads the camera orientation (EXIF metadata) of a JPEG photo to find out how many degrees it needs to be rotated to display right-side up.

## Bottom line
That was the explanation for every built-in File block in Sketchware Pro. If you think some info is wrong or doesn't exist, please let us know in our discord server or simply open a Pull Request in our website's GitHub repository.
