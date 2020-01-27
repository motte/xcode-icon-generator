# xcode-icon-generator
This bash script generates all app icon sizes required for iOS, MacOS, and WatchOS.

## How To Use:
```
cd xcode-icon-generator
./generate-icons.sh [input-image] [output-directory]
```

## Example:
```
cd xcode-icon-generator
./generate-icons.sh ~/Downloads/app-iconx2048.png ~/Downloads/app-directory
```

### Requirements
* Apple requires app icons to have the **.png* file format.
* Please ensure your input image is larger than 1024x1024.


### Notes
* If you would like to adjust the sizes or names generated, navigate to the "sizes" directory and edit the names (on the left) and sizes (in pixels, on the right).  Each image size file must occupy its own line.
* If the output directory does not exist, it will auto-create it.

## Credits
* Credit to smallmuou (smallmuou@<i></i>163.com) for work on the original script, ios-icon-generator.
