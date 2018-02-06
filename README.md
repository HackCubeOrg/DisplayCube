# Display Cube
[![Gitter](https://img.shields.io/gitter/room/nwjs/nw.js.svg)](https://gitter.im/HackCubeOrg/General?utm_source=share-link&utm_medium=link&utm_campaign=share-link)

![Build](https://travis-ci.org/HackCubeOrg/DisplayCube.svg?branch=master)

Device based on LCM1602 display and Arduino. You can use it to display information in the easiest way. To set text you must just call API on Cube Cloud and in POST message send text.

```
{
 "CubeId": "aBf34",
 "Content": {
     Row1: "Some text"
 }
}
```

Or send directly by socket or MQTT or RF24

`aBf34|1|0|SomeText`


![temp_ver0.1](http://sebcza.pl/wp-content/uploads/2018/02/displaycube_foto.jpg)
Version 0.1



![temp_ver1.0](http://sebcza.pl/wp-content/uploads/2018/02/27785662_1847990895271045_35937696_o.jpg)
Version 1.0

## Features

 - Set text on row
 - Turn on/off backlight


## Build Device


## Upload firmware

## Run and Configuration
