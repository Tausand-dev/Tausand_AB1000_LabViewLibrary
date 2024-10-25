# Tausand_AB1000_LabViewLibrary

Library and examples to use Tausand Abacus AB1000 and AB2000 devices with LabVIEW 2015 or later.

This is a Plug and Play (project-style) library for LabVIEW. To use it:
* Download the library.
* Extract the contents of the .zip file to a subdirectory of your LabVIEW folder, `<National Instruments>\LabVIEW\instr.lib`.
* Navigate to and open the .lvproj file. You can browse the examples included in the project to get started taking measurements with your instrument.
  
Help to use this library is found at National Instruments' tutorial: [Third Party Instrument Driver Missing in LabVIEW After Installation](https://knowledge.ni.com/KnowledgeArticleDetails?id=kA00Z000000P8THSA0)

## About Tausand Abacus AB1000 and AB2000

These are a family of coincidence counters, ideal to measure temporal correlations in particle detection and quantum optics experiments.

To learn more about them, visit our website www.tausand.com

To obtain a Tausand's Abacus coincidence counter, visit our [online shop](http://www.tausand.com/shop) or contact us at sales@tausand.com

## Tausand Abacus AB1000 Instrument Driver Readme

### 1. Overview
Instrument Driver Technology: LabVIEW Plug and Play (project-style)<br/>
Manufacturer: Tausand <br/>
Supported Language(s): LabVIEW <br/>
Supported Model(s): AB1002, AB1004, AB1502, AB1504, AB2002, AB2004, AB2502, AB2504<br/>
Model(s) Tested: AB1002, AB1004, AB1502, AB1504, AB2502, AB2504<br/>
Interface(s): USB

Driver Revision: 1.5<br/>
Original Release Date: 05/16/2019 (mm/dd/yyyy)<br/>
Current Revision Date: 10/23/2023

### 2. Required Software
Some software components need to be installed before using this instrument driver. The minimum versions of these components are listed below, and can be downloaded from the Download Site.
* NI-VISA 15.0.1 or later
* LabVIEW 2015 or later

### 3. Known Issues
To report issues or provide feedback about this instrument driver, please send an email to support@tausand.com.

### 4. Revision History
The latest version of this and other Tausand instrument drivers can be downloaded at [Tausand downloads website](http://www.tausand.com/downloads/).

* REV 1.0, 05/16/2019<br/>
Created by: David Guzmán, dguzman@tausand.com, Bogota, Colombia.<br/>
Original release.


* REV 1.1, 07/10/2019<br/>
Updated by: David Guzmán, dguzman@tausand.com, Bogota, Colombia.<br/>
Update on _Wait for Acquisition Complete_ VI. Now it returns a warning instead of an error when max timeout is reached.


* REV 1.2, 06/02/2020<br/>
Updated by: David Guzmán, dguzman@tausand.com, Bogota, Colombia.<br/>
New supported models: AB1502, AB1504 (2ns resolution), AB1902 and AB1904 (1ns resolution).


* REV 1.3, 08/15/2022<br/>
Updated by: David Guzmán, dguzman@tausand.com, Bogota, Colombia.<br/>
New supported models: AB2004 (5ns resolution) and AB2504 (2ns resolution).<br/>
New low-level read data functions, to read a limited set of registers in less time.<br/>
Self recovery method on _Read Mesurements_ VI. Now it reconnects device (close/open) when communication fails.


* REV 1.4, 01/18/2023<br/>
Updated by: David Guzmán, dguzman@tausand.com, Bogota, Colombia.<br/>
New supported models: AB2002 (5ns resolution) and AB2502 (2ns resolution).<br/>
New _Get Resolution_ and _Get Channels_ VIs.


* REV 1.5, 10/23/2023<br/>
Updated by: David Guzmán, dguzman@tausand.com, Bogota, Colombia.<br/>
New _Time-correlated single photon counting (TCSPC)_ examples.

