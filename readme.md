<img src="https://img.shields.io/badge/Version-1.3.6-green">  <a href="https://forum.hassiohelp.eu/d/503-package-cronotermostato"><img src="https://img.shields.io/badge/Forum-hassiohelp-blue"> </a>
<img src="https://img.shields.io/badge/Update-yes-orange"> <a href="https://www.buymeacoffee.com/mariocandida80"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" width="90" alt="Buy Me A Coffee"> </a>
<br>
If you want the weekly version, you can find it  <a href="https://github.com/mariocandida80/addon_settimanale">here</a>.

<p align="center"/> <b>Cronothermostat Package for Home Assistant.</b> <br> </p>

<p align="center"/><img src="https://github.com/mariocandida80/cronotermostato/blob/master/esempi/principale.png" alt="Immagine cronotermostato"></p>
This package creates a series of entities and automations to make sure that the thermostat works in various modes that can be selected by the user and that it is possible to turn it on at certain times and whether or not you are at home.
Let's see how to install it. <br>
<br>
<a href="#Prerequisiti">Prerequisites</a><br>
<a href=“#Installazione1">Installation with climate entity no pre installated</a><br>
<a href="#Installazione2">Installation with climate entity installated</a><br>
<a href=“#Confcard">Card configuration</a><br>
<a href=“#Funzionamento">How it work</a><br>
<a name="Prerequisiti"><p align="center"/> <b>Prerequisites</b> <br> </p>
To operate, it needs an already installed climate entity or 2 entities: a switch that activates and deactivates the thermostat and a temperature sensor. <br>
To install this package you will need:<br>
1. have configured the packages <br>
2. install  <a href="https://github.com/custom-cards/button-card">button-card</a>, <a href="https://github.com/thomasloven/lovelace-card-mod"> card-mod</a>,  <a href="https://github.com/thomasloven/lovelace-state-switch">state-switch</a> and <a href="https://github.com/pilotak/homeassistant-attributes"> attributes </a> (from HACS)<br><br>

<a name="Installazione1"><p align="center"/><p align="center"/> <b>Installation with climate entity not pre-installed</b> <br> </p>
Download the chronothermostat-master.zip file (clone or download at the top right and then download zip) and unzip the files. <br>
Copy the files in this way:<br>
Pkg_cronotermostato_v1_3_6.yaml in the packages folder<br>
blue.jpg, impostazioni.jpg and fiamma.gif in the folder www/images/lovelace /<br>

Open the file Pkg_cronotermostato_v1_3_6.yaml and make the following changes:<br>
1. replace switch.sonoff_10004b541f with the switch that turns on the thermostat (line 33))<br>
