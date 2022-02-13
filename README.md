# Alfred NightShift

[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/shmulvad/alfred-nightshift?sort=semver&style=flat-square)](https://github.com/shmulvad/alfred-nightshift/releases)
[![GitHub downloads](https://img.shields.io/github/downloads/shmulvad/alfred-nightshift/total?style=flat-square)](https://github.com/shmulvad/alfred-nightshift/releases/latest/download/NightShift.alfredworkflow)
[![GitHub issues](https://img.shields.io/github/issues/shmulvad/alfred-nightshift?style=flat-square)](https://github.com/shmulvad/alfred-nightshift/issues)
[![GitHub license](https://img.shields.io/github/license/shmulvad/alfred-nightshift?style=flat-square)](https://github.com/shmulvad/alfred-nightshift/blob/master/LICENSE)

A simple [Alfred][1] workflow for quickly turning on/off Night Shift or setting it to a value between 0-100. No more fiddling with deep settings when you either want to save your eyes or need to work with accurate colors!

⭐ If you find this repo useful, please consider starring it to let me know.

## Installation
1. Install [alfred-nightshift][2] workflow.
2. All further updates are handled automatically.

## Usage
In Alfred, type `night` followed by either `on`, `off` or a number between `0 - 100`. In the workflow, you can also set a custom hotkey for toggling.

<p align="center">
  <img width="1200" height="auto" src="images/night.png?raw=true">
  <img width="1200" height="auto" src="images/night85.png?raw=true">
</p>


## Caveats

Some users on Apple silicon chips have reported that the workflow didn't work out of the box. If the workflow is not working, you can try the following:

1. Manually change permissions in settings to allow it.
2. Install [Rosetta 2][5] if you don't already have it on your system.


## Credits
The workflow makes use of the following:

* [nightlight][3] by smudge as the backend for setting the values.
* [OneUpdater][4] by vitorgalvao for handling automatic updates.

[1]: https://www.alfredapp.com/
[2]: https://github.com/shmulvad/alfred-nightshift/releases/latest/download/NightShift.alfredworkflow
[3]: https://github.com/smudge/nightlight
[4]: https://github.com/vitorgalvao/alfred-workflows/tree/master/OneUpdater
[5]: https://support.apple.com/en-us/HT211861
