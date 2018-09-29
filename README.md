# seek

### Find files by regex with optional .gitignore consideration

### Usage

$> seek [-p Path to base search folder] [-r Regex-String] [-g -- optional gitignore consideration]

### Dependencies

* find
* git
* git check-ignore
* grep
* sed
* xsel
* peco

### Install

Put the script file into your local bin-folder (that is in your $PATH).

Standard installations probably don't have xsel and peco installed.
Xsel is a cli-clipboard tool ...
Peco is a cli-Combobox-Select tool ...
