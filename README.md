# batch-image-macros

This is a dumping ground for macros that I have made or adapted from others. They are all for use with image processing in ImageJ. I have primarily used them with Transmission Electron Microscopy (TEM) images collected on FEI and JEOL instruments. 

## Getting Started

These instructions are for a Mac, but relevant menus and installation should be easily adapted for Windows.


### Prerequisites

In order to run these macros, ImageJ or Fiji will need to be installed. I recommend Fiji, which can be found [here](https://fiji.sc/).


### Installing

Macros can be installed from within ImageJ through Plugins -> Macros -> Install. This will allow you to select the .txt file and then run from the macro selection menu under Plugins -> Macros. This will uninstall any previously installed macros though and they will not be available when the program is first opened. 

To have macros available when first opening the program they should be copied from their respective .txt files to the StartupMacros.ijm file which can be found in the macros folder within the package contents of the ImageJ application. The macros copied into the StartupMacros.ijm file will have to be surrounded by the following text where the square bracketed function number will be the short cut to start the program. Be sure to indent all text within the bracketed region once. 

```  
macro "Macro Title [F4]" {
	
}  
```
 

