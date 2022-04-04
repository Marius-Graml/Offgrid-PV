# Off-grid PV
Monitoring my off-grid photovoltaic system

the aim of this project is to measure current and voltage of a 700 Wp solar panel continously. The technical strucutre is shown below:
<p><img align="left" src="https://github.com/Marius-Graml/Offgrid-PV/blob/main/pictures/solar_panel.jpg" width="200" height="180"</p>
<p><img align="left" src="https://github.com/Marius-Graml/Offgrid-PV/blob/main/pictures/charge_controller.jpg" width="200" height="180"</p>
<p><img align="left" src="https://github.com/Marius-Graml/Offgrid-PV/blob/main/pictures/batteries.jpg" width="200" height="180"</p>
<p><img align="left" src="https://github.com/Marius-Graml/Offgrid-PV/blob/main/pictures/inverter.jpg" width="200" height="180"</p>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
</br>
For measuring current and voltage different sensors and microcontrollers are used. The data is stored into a MongoDB database by using AWS and a Raspberry Pi as "data pipeline". Finally, the data is callable from the database via a Python script. The whole infrastructure of this concept can be seen here:
<p><img align="left" src="https://github.com/Marius-Graml/Offgrid-PV/blob/main/pictures/concept_of_measurement.jpg" width="250" height="200"</p>

<p><img align="left" src="https://github.com/Marius-Graml/Offgrid-PV/blob/main/pictures/ESP32_on_platine.jpg" width="320" height="320"</p>
