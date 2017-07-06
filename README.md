# phidgets-sensors-utilities

This is data logging scripts for [Phidgets](cvent.com/events/the-11th-international-conference-on-sensing-technology/event-summary-ad2e1df275924f409efbf3291c7101ac.aspx) sensors.

## Description

This is a examples for phidegts sensors.
And a [PhidgetBridge 4-Input](https://www.phidgets.com/?tier=3&catid=2&pcid=1&prodid=35) is used for measuring the output from a load cell.
For the API for using this board, please refer to the [official site](https://www.phidgets.com/?tier=3&catid=2&pcid=1&prodid=35).

## Features

- Easy to use for logging various sensor data
- Visualize sensing data

## Installation/Requirement

### Setup Phidgets22 API

Please set according to [Quick Downloads here](https://www.phidgets.com/docs/Language_-_Python#Quick_Downloads)

 `$ ./pso`

However, with the above command, it was impossible to build the module, so you should use the pip package management system as below.

[References](https://stackoverflow.com/questions/8295644/pypi-userwarning-unknown-distribution-option-install-requires)

 `$ Python setup.py sdist`
 `$ Cd dist`
 `$ Pip install Phidget 22-1.0.0.tar.gz`

### [S Type Load Cell(0 ~ 100kg)](https://www.phidgets.com/?tier=3&catid=9&pcid=7&prodid=229)

- python
	$ git clone git@github.com:takuya-ki/phidgets-sensors-utilities.git
	$ cd phidgets-sensors-utilities/s-type-load-cell-100kg/(LANGUAGE)

- jupyter notebook4.1.0 or above(recommended)
- python3.0 or above

## Usage

- python
 `$ jupyter notebook (script name).py`

## Author/Contributors

qiita: [@takuya-ki](http://qiita.com/takuya-ki)

## License

This software is released under the MIT License, see LICENSE.txt.
