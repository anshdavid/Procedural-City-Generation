# Procedural City Generation

This is fork from [Procedural City Generation](https://github.com/josauder/procedural_city_generation). All credits go to by [josauder](https://github.com/josauder). Documentation can be found [here](http://josauder.github.io/procedural_city_generation).

---

### For active development please switch to development branch !! 

I plan on maintaining this fork. Kindly open issues if you encounter bugs / need fixes.

---


## Dependencies

- pyqt5
- numpy
- matplotlib
- json
- pickle
- PIL
- scipy
- importlib
- pkgutil


## Running the program

> `python3 GUI.py`

![Demo](./doc/videos/procedural-city-generation.gif)

# Changelog

## [0.4.8] - 2020-07-30

### Added

- exception handling in `getBlock.py` to handle out of range indexes when calcaulating 'dead ends' lineno[45, 71]

### Fixed

- Possible fix for **issues #1**

### Todo

- fix blender api calls

## [0.4] - 2020-07-15

### Fixed

- crashes when generating road network

### Todo

- fix blender api calls


## [0.3] - 2020-07-14

### Fixed

- transition pyqt4 -> pyqt5
- temporarily fix blender visualization bugs

### Todo

- fix blender api calls
