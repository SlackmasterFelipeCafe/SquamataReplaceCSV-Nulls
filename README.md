# SquamataReplaceCSV-Nulls

**Squamata** is the largest order of reptiles, comprising lizards, snakes and amphisbaenians (worm lizards), which are collectively known as squamates or scaled reptiles.

**SquamataReplaceCSV-Nulls** is a Jupyter notebook used to create metadata files for USGS Aeromagnetic data releases to ScienceBase.

*"Birthing the tail that feeds it..."* 

![Squamata - birthing the tale that feeds it](https://github.com/pbrown-usgs/SquamataAssemblyAMT/blob/master/SquamataLemniscateOuroboros.png)

### Version 1.0

This Jupyter Notebook performs the following operations:
- Loads a CSV file.
- Determins Null Values
- Changes Null values to a value defined by the user
- Output to a new CSV file


### To execute a function/command select a cell and Hold-Shift + Press-Enter

**The 'r' signifies a string literal. Use for paths.**

- v1.0: Read csv File into pandas, Create Array of csv column headers, assign header array of channel descriptions and units.
