+-----------------------------------------------------------------------------+
| README.txt  (third prototype)                                               |
|                                                                             |
| Author: Alexander Bliem abliem.itsb-m2012@fh-salzburg.ac.at                 | 
| Author: Stefan Auer sauer.itsb-m2012@fh-salzburg.ac.at                      |
| Author: Pierre Raufast pierre.raufast@gmail.com (thinkrpi.wordpress.com)    |
|                                                                             |
| Date   01.06.2013                                                           |
| Version 1.0                                                                 |
|                                                                             |
| This folder contains the files required for the third prototype for         |
| JPEG-Encryption.                                                            |
|                                                                             |
| Date   01.06.2013                                                           |
| Version 1.0                                                                 |
|                                                                             |
| This folder contains the files required for the second prototype for        |
| JPEG-Encryption.                                                            |
|                                                                             |
| Required:                                                                   |
| 1) connected Raspberry Pi Camera (CSI port)                                 |
| 2) WebServer (e.g. apache up and running)                                   |
| 3) A folder that is accessible through HTTP (/var/www/JPEG.Encryption/)     |
| 4) OpenCV 2.x.x in the folder ../../OpenCV-2.x.x/                           |
| 5) JPEG.Encryption files in                                                 |
|               ../JPEG.Encryption/JPEG.Encryption.C/JPEG.Encryption.Core     |
|                                                                             |
| Build prototype:                                                            |
| 1) cmake .                                                                  |
| 2) make                                                                     |
|                                                                             |
| start prototype:                                                            |
| 1) start prototype with "./camcv"                                           |
| 2) start prototype with "./camcvTiming"                                     |
|                                                                             |
| Remarks:                                                                    |
| This is the third prototype of the project. It uses pics from the Raspberry |
| Pi Camera module. The image is downsized to 320x240 pixel before face       |
| detection is executed (OpenCV).                                             |
|                                                                             |
+-----------------------------------------------------------------------------+
