# Deploying to Linux

## Krom

- Create a new preset in `Armory Exporter` and select `Linux (Krom)` target.
- Press `Publish`.
- That's it! Press `Triangle - Open Folder` to view exported files.

## Native (C++)

For the C++ compilation to succeed you might need to install some additional packages - read more at [Kha/Wiki](https://github.com/Kode/Kha/wiki/Linux).

Create a new preset in *Properties - Render - Armory Exporter* and select Linux target. Hit *Publish* to export build files.

Afterwards, you can compile the project using the generated makefile in *blend_file_location/build_projectname/linux-build/Release* or using the [Code::Blocks](http://codeblocks.org) project located at *blend_file_location/build_projectname/linux-build*.

In order for the resources to load correctly you will need to copy the executable into the folder with all the game's resources.

To do this simply copy the executable from *blend_file_location/build_projectname/linux-build/Release* into *blend_file_location/build_projectname/linux*.

![](/platforms/img/linux/1.png)

You can now run and package your game!
