# Slyshow

> `$ slyshow file...`

Simple bash tool and script for creating a minimal slideshow.
It will only allow you to show 4 lines of centered text.

["How To Speak by Patrick Winston"][1] inspired me to make this tool.

[![How To Speak by Patrick Winston
Video](https://img.youtube.com/vi/Unzc731iCUY/0.jpg)][1]

## Features

- Supports ANSI text input.
- Centers all the text.
- Written in Bash.
- Promotes minimal slideshows.

## Requirements

Requires **bash** because it is written for it, Perl for stripping ANSI
formatting, **less** for displaying the generated text and **tput** to
determine width, height, bold and normal text.

These tools tend to be installed on Linux systems by default.

## Installation

Place the slyshow file in a directory that is on your PATH and make sure it is
executable.

## Usage

```sh
slyshow ./README.md
```

## Known Issues

- Manually tested only on my Ubuntu system.
- No tests.
- No help page.

## License

GNU General Public License 3.0

[1]:https://www.youtube.com/watch?v=Unzc731iCUY
