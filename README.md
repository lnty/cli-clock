# CLI Clock

## Description

The CLI Clock is intended to be a simple and reliable digital clock for your Linux shell. The idea to create such a script came after trying to find a simple shell script or python script to do the same thing online. I couldn't find one that I actually liked, and that was easy to customise, so I created my own.

## Requirements

### [PyFiglet](https://pypi.org/project/pyfiglet/)

```bash
$ pip3 install pyfiglet
```

## Usage

- Download the latest release from [here](https://github.com/lnty/cli-clock/releases)
- Extract the downloaded release and run with Python.

```bash
$ python3.7 main.py
```

### Customisation

The variables at the start of the script can all be changed to modify the look and feel of the clock.

| Variable            	| Default                  	| Description                                                                    	| Useful Link(s)                                       	|
|---------------------	|--------------------------	|--------------------------------------------------------------------------------	|------------------------------------------------------	|
| font_name           	|   ``` '3x5'  ```         	| Changes the Figlet font which is rendered                                      	| [Figlet Font DB](http://www.figlet.org/fontdb.cgi)   	|
| padding             	|  ``` [0, 0, 0, 0] ```    	| Applies padding to the top/right/bottom/left of the text                       	|                                                      	|
| custom_char_replace 	|  ``` {'#': '\u2588'} ``` 	| Used to replace the character(s) in the key with the character(s) in the value 	| [Unicode Character Table](https://unicode-table.com) 	|
| time_format         	|  ``` '%H:%M:%S' ```      	| Set the format of the time to be displayed                                     	| [Time Formatting Parameters](http://strftime.org/)   	|

## Planned Features

- Colour customisation.
