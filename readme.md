

# FOS with VSCode Using the Same Environment (Cygwin) Without Affecting the Project Template
## Downloading the Archives from GitHub

Ensure you download the required archives by following these steps:

1. Navigate to the respective files on GitHub.
2. Click on the file you want to download.
3. Look for the "Download" button on the top right or bottom right of the file preview.
4. Click the "Download" button to download the file to your local machine.

Ensure `fos_cygwin` is directly located in `C:/`.

## Features

- Seamless integration with VSCode in the Cygwin environment.
- Minimal impact on the project template.
- Removal of unnecessary files.
- Integration of QEMU for a faster and smoother experience (Bochs still works!).
- Improved build speed with parallel processing using `make -j`.

## Configuration

To set up your project, follow these steps:

1. Place `fos_cygwin` directly in `C:/`.
2. Open the `.vscode` folder.
3. In each file, update all occurrences of '2023' to the current year.
4. Run using RunVSCode.bat
## Running FOS on Linux

To run FOS on Linux, download `fos_cygwin.rar` and navigate to the `fos_linux` directory for configuration options.

## To Set a Shortcut

Refer to the [define a shortcut section in readme.md](https://github.com/ahmedhsin/fos_vscode/tree/main).

## Additional Information
Enjoy developing with FOS in the VSCode environment!

**Note:** This version does not include Eclipse, reducing the size to less than 300MB compared to 700MB in the Eclipse version.

Contact: github@ahmedhsin
