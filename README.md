![image](http://www.4dsystems.com.au/imagenes/header.png)

ViSi-Genie-Library - NEW VERSION - Updated 20-JULY-2014
==============================================================
Adapted for Spark

Spark Library for 4D Systems ViSi-Genie Environment

This library adds support for 2+ displays connected to a single Spark, and adds a new Demo to illustrate how that is achieved

## Information

This library provides high level functions for the Spark, to ease communication with 4D Systems modules when using the module configured with ViSi-Genie.
Please refer to the 4D Systems website, namingly the Workshop 4 Product Page, for documentation regarding Workshop 4, and its environments.


## Example Sketch

Inside the library are 2 example sketches, to assist with getting started using this library. Inside is also a ViSi-Genie Workshop4 project, which can be used on a range of 4D Systems displays (designed on a uLCD-32PTU however can be changed via Workshop4 menu). It illustrates how to use some of the commands in the library include Read Object, Write Object, Reported Messages, Write Contrast and Write String.

## Tested with

This library has been tested on the Spark Core, Duemilanove, Uno, Mega 1280, Mega 2560, Leonardo, Chipkit Max32, Due and new Intel Galileo. Any problems discovered with this library, please contact technical support so fixes can be put in place, or seek support from our forum.

## Compatible 4D Systems Display Modules

This library will work with all 4D Systems Modules which are capable of using the ViSi-Genie environment. This is therefore all Picaso and Diablo16 Display Modules.
The demo included with this library was made for the uLCD-32PTU however can easily be adapted to other size displays.

```
////////////////////////// GenieArduino 20/07/2014 /////////////////////////
//
//      Library to utilise the 4D Systems Genie interface to displays
//      that have been created using the Visi-Genie creator platform.
//      This is intended to be used with the Arduino platform.
//
//		Improvements/Updates by
//		4D Systems Engineering, July 2014, www.4dsystems.com.au
//      Clinton Keith, March 2014, www.clintonkeith.com
//		Clinton Keith, January 2014, www.clintonkeith.com		
//		4D Systems Engineering, January 2014, www.4dsystems.com.au
//		4D Systems Engineering, September 2013, www.4dsystems.com.au
//		Written by
//		Rob Gray (GRAYnomad), June 2013, www.robgray.com
//      Based on code by
//		Gordon Henderson, February 2013, <projects@drogon.net>
//
//      Copyright (c) 2012-2014 4D Systems Pty Ltd, Sydney, Australia
//		Adapted for Spark Core by Paul Kourany, July 2014
/*********************************************************************
 * This file is part of genieArduino:
 *    genieArduino is free software: you can redistribute it and/or modify
 *    it under the terms of the GNU Lesser General Public License as
 *    published by the Free Software Foundation, either version 3 of the
 *    License, or (at your option) any later version.
 *
 *    genieArduino is distributed in the hope that it will be useful,
 *    but WITHOUT ANY WARRANTY; without even the implied warranty of
 *    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 *    GNU Lesser General Public License for more details.
 *
 *    You should have received a copy of the GNU Lesser General Public
 *    License along with genieArduino.
 *    If not, see <http://www.gnu.org/licenses/>.
 *********************************************************************/
```

## Notes

This library is a version of 4D Systems ViSi-Genie-Arduino library adapted for the Spark.  The library is designed to use any (hardware) Serial port.  On the Spark, this would  be Serial1 or Serial2 (when it is released).
 
The genieSpark_Demo program requires that the 4D display be connected to Serial1 and that the  display be pre-programmed with the sample 4DWorkshop file and setup to run at 115,200 baud.
 
The genieSpark_Demo_MultiScreen program requires two 4D displays, one connected to Serial1 and the other to Serial2, each pre-programmed with the sample 4DWorkshop file and setup to run at 115,200 baud.
 
 
