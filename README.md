mobile-assets
=============

This repository contains the (binary) assets for the mobile clients. It's a
separate repository so it can be destroyed and recreated when it becomes too
big.

It's organized into themes. The mobile client repositories have a script that
generates the correct (platform-dependent) images from the generic assets in
this repository.

So for example the repository for the iOS client has a script that resizes a
big icon into smaller icons for Spotlight, Settings and the icon for the app
itself.

# Placeholder

The placeholder theme is not meant to be updated. It's special in that the
images are used to generate the placeholders needed to get a bare-bones app
running. The mobile client repositories have these placeholder images checked
in, so that these repositories can be compiled and run after checking out.

# Structure

The theme directories can have any structure you like. The conversion scripts
for iOS need a large (1024x1024 or bigger) app icon that's named app_icon.png.

# License

The license for the artwork depends on the directory. Check the LICENSE file
for more information
