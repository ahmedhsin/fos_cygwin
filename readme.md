# FOS with VSCode using the Same Environment (Cygwin) Without Affecting the Project Template

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

## To set a shortcut, refer to the [define a shortcut section in readme.md](https://github.com/ahmedhsin/fos_vscode/tree/main).

## Additional Information
Enjoy developing with FOS in the VSCode environment!

**Note:** This version does not include Eclipse, reducing the size to less than 300MB compared to 700MB in the Eclipse version.

Contact: github@ahmedhsin
