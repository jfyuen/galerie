# Galerie
This script is a slight modification from David Wackler galerie script: http://cker.name/galerie/

## Installation
Just drop the script at the root of a directory, rename it index.php if needed. It will automatically create thumbnails.

## Requirements
Taken from original website:
- PHP >= 4.1.0 - http://www.php.net/
- GD Library ( >= 2.0.1 for good thumbnails) - http://www.boutell.com/gd/
- JPEG software - ftp://ftp.uu.net/graphics/jpeg/
- PHP >= 4.3.0 or GD < 1.6 for GIF support
- libpng for PNG support - http://www.libpng.org/pub/png/

## Configuration
See file header.

## Changes
Changes over the original version include:
- some relative path fixes and changes
- better UTF8 support
- regenerate thumbnail if original image is newer
- Better root display
