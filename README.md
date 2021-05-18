# Ranger & z
This plugin integrates [Z](https://github.com/rupa/z) with [ranger](https://github.com/ranger/ranger). The plugin uses `.z` file to jump around, watch [screencast](https://youtu.be/ciHHbFtz4N8).

## Installation
```
* cd "${XDG_CONFIG_HOME:-$HOME/.config}"/ranger/plugins
* git clone https://github.com/ask1234560/ranger-zjumper.git
* echo "map cz console z%space" >> "${XDG_CONFIG_HOME:-$HOME/.config}"/ranger/rc.conf
* restart ranger
```

## Usage
* Type `:z dir` to go to `.*/dir` or `:z dir1 dir2 ... dirn` to go to `.*/dir1.*/dir2....*/dirn`
* Or press c followed by z, followed by `dir` or `dir1 dir2 ... dirn`
* Dir is case insensitive
