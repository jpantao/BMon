# BMon
BMon - Bonsai Monitor 

Mobile and Pervasive Computing Course Project. The report with a detailed
description can be found [here](report/report.pdf).

#### TODO: add deployment instructions and description to this README

##  Deployment
The deployment of our system is done in 4 steps:

1. Install the libraries for integrating firebase with the esp32
microcontroller (available at BMon-ESP32/libraries_zip).

2. Change the Wi-Fi credencials in the microcontroller code directly
(BMon-ESP32/BMon.ino File). This step and step 3 are inconvinient but 
it was the only way we found to "communicate" with the board while it 
was not connected to the internet.

3. Upload the program to the board and install the unit on the
desired bonsai.

4. TODO Application
