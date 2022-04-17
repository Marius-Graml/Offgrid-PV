# Off-grid PV
<h2>Monitoring my off-grid photovoltaic system</h2>

The aim of this project is to measure current and voltage of a 700 Wp solar panel continously. The technical strucutre is shown below:
<p><img align="left" src="https://github.com/Marius-Graml/Offgrid-PV/blob/main/pictures/solar_panel.jpg" width="180" height="160"</p>
<p><img align="left" src="https://github.com/Marius-Graml/Offgrid-PV/blob/main/pictures/charge_controller.jpg" width="180" height="160"</p>
<p><img align="left" src="https://github.com/Marius-Graml/Offgrid-PV/blob/main/pictures/batteries.jpg" width="180" height="160"</p>
<p><img align="left" src="https://github.com/Marius-Graml/Offgrid-PV/blob/main/pictures/inverter.jpg" width="180" height="160"</p>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
<h2>Sensors:</h2>
For measuring current and voltage, different sensors and microcontrollers are used: </br> </br>
 - <a href="https://www.digikey.de/de/datasheets/allegromicrosystemsllc/allegro-microsystems-llcacs758datasheetashx"> ACS758</a> -> current measurement </br></br>
 - <a href="https://www.ti.com/lit/ds/symlink/ads1114.pdf?ts=1648959763893&ref_url=https%253A%252F%252Fwww.google.com%252F"> ADS1115</a> -> external ADC to measure output voltage of ACS758 </br></br>
- <a href="https://www.espressif.com/sites/default/files/documentation/esp32_datasheet_en.pdf"> ESP32</a>-> internal ADC to measure voltage of batteries via voltage dividers </br></br>

<p><img align="left" src="https://github.com/Marius-Graml/Offgrid-PV/blob/main/pictures/ESP32_on_platine.jpg" width="320" height="320"</p>

</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
<h2>Infrastructure:</h2>
The data is stored into a MongoDB database by using AWS and a Raspberry Pi as "database pipeline". Finally, the data is callable from the database via a Python script. The whole infrastructure of this concept can be seen here:
<p><img align="left" src="https://github.com/Marius-Graml/Offgrid-PV/blob/main/pictures/concept_of_measurement.jpg" width="750" height="450"</p>
