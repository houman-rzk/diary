# diary

A simple script for easily managing a diary.

It uses text-files with time-stamps for each entry.


## Installation
Copy `diary` to some directory in your PATH (i.e: ~/.local/bin/).


## Usage
`diary`

Running `diary` and leaving the file untouched will not add the entry (nor the time-stamp) to the corresponding daily-entry-file.


## Details
Your $XDG_DATA_HOME variable must be set (it is usually set to ~/.local/share) for the script to work by default.

The script uses the following directory structure in your $XDG_DATA_HOME directory:
```
diary
  |
  |-YYYY1
  |   |
  |   |-MM1
  |   |   |
  |   |   |-dd1
  |   |   |-dd2
  |   |   |-...
  |   |
  |   |-MM2
  |      |
  |      |-dd1
  |      |-dd2
  |      |-...
  |
  |-YYYY2
      ...
```
