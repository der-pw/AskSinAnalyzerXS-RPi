# AskSinAnalyzerXS-Rpi     ![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)
Raspberry Pi Addon PCB für den [AskSinAnalyzerXS](https://github.com/psi-4ward/AskSinAnalyzerXS).  
Dieser wird einfach auf die GPIO-Leist gesteckt.  
Es kann der Standard Sketch aus dem [AskSinAnalyzer](https://github.com/jp112sdl/AskSinAnalyzer) Repo von Jérôme geflashed werden.  

![Draufsicht](https://raw.githubusercontent.com/der-pw/AskSinAnalyzerXS-RPi/main/img/top.jpg)

Im Prinzip kann der AskSinAnalyzerXS-RPi nach dem Zusammenbau mit einem Programmer (FTDI) verbunden und geflashed werden.
Der 3V Jumper kann berückt werden, damit die Stromversorgung vom FTDI erfolgt. DTR kann ebenfalls gebrückt werden und Reset auszulösen.
Der 0.1uF in der DTR Strecke ist nicht auf dem PCB vorhanden und sollte ins Verbindungskabel integriert werden. Alterntaiv kann auch Reset im richtigen Moment kurz gegen GND gebrpckt werden.  

![Unterseite](https://raw.githubusercontent.com/der-pw/AskSinAnalyzerXS-RPi/main/img/Belegung.jpg)  

Folgender Tipp ist möglicherweise hilfreich, bei Verwendung der seriellen Schnittstellen auf dem RPi.  
https://homematic-forum.de/forum/viewtopic.php?f=76&t=56395&start=70#p569429 

[![Creative Commons Lizenzvertrag](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)  
Dieses Werk ist lizenziert unter einer [Creative Commons Namensnennung - Nicht-kommerziell - Weitergabe unter gleichen Bedingungen 4.0 International Lizenz](http://creativecommons.org/licenses/by-nc-sa/4.0/).
