# pgs2srt

Uses [pgsreader](https://github.com/EzraBC/pgsreader) and [pyteseract](https://pypi.org/project/pytesseract/) to convert image based pgs subtitles files (.sup) to text based subrip (.srt) files.

## Requirements
Python3 and pip3

## Installation
* Run ```git clone https://github.com/PimvanderLoos/pgs2srt.git```
* Inside the repo folder, run ```pip3 install -r requirements.txt```
* In your .bashrc or .zshrc add ```alias pgs2srt='<absolute path to repo>/pgs2srt.py'```

## How to run

    pgs2srt <pgs filename>.sup

## Todo

* Error logging

## Caveats

This is in no way a perfect converter, and tesseract will make incorrect interpretations of characters. Extremely alpha, issues, pull requests and suggestions welcome!
