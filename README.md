# Windows macOS File Cleaner

A simple Windows Batch script (`.bat`) to remove hidden macOS files like `.DS_Store` and `._*` from USB flash drives and other external media.

This is perfect for cleaning a drive before plugging it into a media player (like a Micca player), a car stereo, or any other device that gets confused by these unnecessary files.

## What It Does

This script safely finds and deletes the following:

-   All `.DS_Store` files
-   All `._*` resource fork files (also known as AppleDouble files)
-   Common hidden macOS system folders:
    -   `.Trashes`
    -   `.Spotlight-V100`
    -   `.fseventsd`

## Requirements

-   Any modern version of Windows (XP, Vista, 7, 8, 10, 11, etc.)

That's it! No special software is needed.

## How to Use

1.  Go to the [Releases page](https://github.com/KnowOneActual/AppleCrumbs-Remover-Windows/releases) of this repository.
2.  Download the `CleanDrive.bat` file.
3.  Double-click the `CleanDrive.bat` file to run it.
4.  A command window will open and ask you to enter the drive letter for your flash drive (e.g., `E`).
5.  Type the letter and press **Enter**.
6.  You'll see a final warning. Press any key to confirm and start cleaning.
7.  Once it's done, you'll see a "Cleaning complete!" message. You can now close the window and use your drive.

## ⚠️ Important

This script permanently deletes files and folders from the drive you select. Please double-check that you have entered the correct drive letter before you proceed. We are not responsible for any accidental data loss.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
