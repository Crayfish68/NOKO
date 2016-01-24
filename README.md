# ![NOKO](http://www.nikolairadke.de/NOKO/noko_klein.png) NOKO

The **NOKO Monster**, lovely and naughty, to build on your on. Everyone ist invited to contribute. NOKO is for everyone. 

<table border="0">
  <tr>
    <td><img src="http://www.nikolairadke.de/NOKO/noko_nr2.png" /></td>
    <td>
    NOKO is a multi functional Monster with an Arduino Nano as microcontroller, display, clock, radio, mp3 player,           four buttons as user interface, battery, voice set and  tons of gimmicks, packted in a cuddly monstersuit - sturdy,
    lovely and sometimes a bit mean and annoying. Just the way you want him to be. He, she or it - that is your decision     and only depends on the voice set. In this repository NOKO ist a Lad, a real bloke! A buddy for life and a companion     by day and nicht. All he needs is a litte power every know an then.<br />
    <br>
    <b>NOKO</b> stands for <b>NO</b>ra's and ni<b>KO</b>'s Monster.
    </td> 
  </tr>
</table>

###Hints for english NOKO builders
*Anything sourcode-related, the circut diagrams and comments on how to compile are written in english. Right now, the building documentation and the manual are in german. Feel free to ask me for translation, if you need help. NOKO itself speaks and writes in german. However, someday, he may learn english or other languages... contribute!*

### Prerequisites
NOKO needs [Arduino IDE 1.6.7](https://www.arduino.cc/en/Main/Software) or [Arduino IDE 1.6.6](https://www.arduino.cc/en/Main/OldSoftwareReleases#previous). Put the folder NOKO/src/NOKO/ into your sketch folder. Right now, NOKO.ino won't compile without changing the local "platform.txt". See [howto_compile](https://github.com/NikolaiRadke/NOKO/tree/master/howto_compile) and change the file. Now NOKO.ino should compile.

### Content

```
NOKO/
├── howto_compile/
|   hints and a modified plattform.txt to compile the sketches in your Arduino IDE.
|
├── manual/
|   NOKO manual in PDF format and a template for a packaging desin.
|   ├── scribus/
|       Source documents for Scribus with all illustrations and fonts.
|
├── mp3/
|   Voiceset for NOKO in german. English needed? Contribute!
|          
├── schematics/
|   schematics for the NOKO modules.
|   ├── geda/
|       Source documents for gEDA.
|
├── src/
|   Arduino sketches
|   ├── NOKO/
|   |   Main sourcecode with all the required libraries.
|   ├── NOKO_Disk1/
|   |   Scetch to write the DISK1 textfile to 24LC256-EEPROMs.
|   ├── NOKO_EEPROM_Disk0/
|       Scetch to write NOKO presets to the Arduino EEPROM and the DISK0 textfile to the
|       AH24C32 EEPROM.
|
├── write_EEPROM/
|   Tools to write data through serial connection to the Arduino and the EEPROMs. 
```
###Let's get started!

Interested on NOKO? Great. Start hier
[German wiki](https://github.com/NikolaiRadke/NOKO/wiki).
English wiki will follow...
