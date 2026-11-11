# PFAS-LEACH Education Edition

PFAS-LEACH Tier 3 & 4 is a desktop app for estimating how PFAS in soil leaches
to groundwater. It comes from the Guo Lab at the University of Arizona. This
Education Edition is simplified for classroom use.

## Download

Download from the
[Releases page](https://github.com/GuoSFPLab/PFAS-LEACH-High-School/releases/latest),
under **Assets**. Download only the file for your computer:

| Your computer | Direct download |
|---|---|
| Mac with Apple Silicon (M1 or newer), macOS 14 (Sonoma) or later | [PFAS-LEACH-Education-macOS-AppleSilicon.zip](https://github.com/GuoSFPLab/PFAS-LEACH-High-School/releases/latest/download/PFAS-LEACH-Education-macOS-AppleSilicon.zip) |
| Windows 10 or 11 (64-bit) | [PFAS-LEACH-Education-Windows-x64.zip](https://github.com/GuoSFPLab/PFAS-LEACH-High-School/releases/latest/download/PFAS-LEACH-Education-Windows-x64.zip) |

> You do **not** need "Source code (zip)" or "Source code (tar.gz)". GitHub
> adds those automatically, and they contain only this README.

No Python installation or internet connection is needed. The Mac version does
not run on Intel Macs or on macOS 13 and earlier.

## Install on Mac

1. Double-click the downloaded zip to unzip it. In the folder
   `PFAS-LEACH-Education-macOS-AppleSilicon`, open `PFAS-LEACH-macOS-arm64.dmg`.
2. Drag `PFAS-LEACH.app` into the **Applications** folder.
3. Double-click `PFAS-LEACH.app`.

The app is not Apple-notarized, so macOS blocks the first launch. Allow it
once:

- **macOS 15 or later:** click **Done** in the warning. Then go to
  **System Settings > Privacy & Security**, click **Open Anyway** next to
  PFAS-LEACH, and confirm.
- **macOS 14:** right-click `PFAS-LEACH.app`, choose **Open**, then click
  **Open** again.

## Install on Windows

1. Right-click the downloaded zip and choose **Extract All**. Do not run the
   app from inside the zip.
2. In the extracted files, open the folder
   `PFAS-LEACH-Education-Windows-x64`, then `PFAS-LEACH`, and double-click
   `PFAS-LEACH.exe`:
   `PFAS-LEACH-Education-Windows-x64\PFAS-LEACH\PFAS-LEACH.exe`
3. If Windows shows "Windows protected your PC", click **More info**, then
   **Run anyway**. This happens because the app is not code-signed.

Keep all extracted files together. The app needs every file in that folder.

## Using the app

The app opens PFAS-LEACH in your web browser and runs entirely on your own
computer. Click **User Guide** on the Overview page for the full manual.
Closing the last PFAS-LEACH browser tab stops the app after a short delay
(under a minute).
