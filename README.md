# Touch Bar Commands
Touch Bar commands for easy and fast access for common tasks.

## Features

Touch Bar commands for easy and fast access. 

![Touch Bar with commands](https://github.com/sverrisson/mac-touchbar-commands/blob/master/src/images/TouchBarCommands.png?raw=true "Touch Bar with commands")

```
// -> Toggle comments of all selected lines on/off.
Commands -> Open the command pallette, esc to close.
Qopen -> Quick Open any file etc., esc to close.
Term -> Toggle the built in terminal on/off.
Sidebar -> Toggle sidebar on/off.
FTP -> FTP sync files *.
```
`*` Requires extension: [ftp-sync](https://marketplace.visualstudio.com/items?itemName=lukasz-wronski.ftp-sync) Turned off by default, see configuration to allow.

Note: If the commands are not showing then turn one of them off 
(see configuration) for additional space for the commands to show up.

## Configuration

Add settings in your "User Settings" for turning Touch Bar commands off/on:
```
"touchBar.comment": false,
"touchBar.commands": false,
"touchBar.qopen": false,
"touchBar.term": false,
"touchBar.toggleSidebar": false,
"touchBar.ftpSync": true,
```
Goto `Code` → `Preferences` → `Settings` and then paste in command from above.

## Requirements

A computer or keyboard with Touch Bar is required. Version 1.17 minimum of VS Code. For the ftp command, the ftp extension is required: [ftp-sync](https://marketplace.visualstudio.com/items?itemName=lukasz-wronski.ftp-sync)

## Source

Please send requests for commands or changes on Github: https://github.com/sverrisson/mac-touchbar-commands

## Release Notes

### 1.4.0

FTP command added (note: requires ftp-sync extension).

### 1.3.5

Removed Preview for Markdown command.

### 1.3.4

Colors added and image updated.

### 1.3.0

Configuration to turn off commands.

### 1.2.1

Fixed images.

### 1.1.0

Fixed grouping of menus.

### 1.0.0

Initial release.

## Authors
- Hannes Sverrisson
- Adam Prancz
