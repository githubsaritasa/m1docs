# MediumOne Microchip IoT Ethernet Development 
##                        Developed by Saritasa 2016

- App Menu and Setup
- IoT Development board installation
- Sensors Click configuration


App Menu and Setup:

1. Download App from Google Play or App Store
2. Configure App to connect the hardware endpoint
3. App User Guide


IoT Development board installation:

1. Embedded Firmware for the Microchip IoT Ethernet board
  https://drive.google.com/file/d/0B5kQERCKKQGWblN1R2NfUURfLTA/view?usp=sharing
2. This is the IoT Ethernet board from Microchip
  https://drive.google.com/file/d/0B5kQERCKKQGWRi10UzZ4U1N2aXc/view?usp=sharing
3. Connect PICKit, ICD3 or Real ICE debugger to the board.
  https://drive.google.com/file/d/0B5kQERCKKQGWcEV2T29lOEI3Y2c/view?usp=sharing
4. Download MPLAB development software from Microchip website.
  http://www.microchip.com/mplab/
5. Click Run to download the code to the board.
  https://drive.google.com/file/d/0B5kQERCKKQGWVkJFbDFFMEtyX0E/view?usp=sharing
6. Download CoolTerm if you have not installed it.
  http://freeware.the-meiers.org
7. Open Coolterm, click connect and hit enter, then jot down the ip address.
  https://drive.google.com/file/d/0B5kQERCKKQGWRE5XWTRxeTUxSVk/view?usp=sharing
8. Enter the ip address to the web browser, then configure the web page with desire credentials.
  https://drive.google.com/file/d/0B5kQERCKKQGWWnRfSUlpUmZVUFE/view?usp=sharing

Sensors Click configuration:

  1. Motion Sensor Click

MOTION click is a motion detector sensitive only to live bodies. It carries PIR500B, a pyroelectric sensor which generates a voltage when exposed to infrared light. The signal is processed by a BIS0001 PIR sensor controller which sends an interrupt to the MCU through the mikroBUS™ INT (out) line. An onboard potentiometer lets you adjust the detecting range of the sensor (up to 4 meters). MOTION click also has a night only mode—resoldering a zero-ohm jumper activates the onboard photo resistor which acts as a light-sensitive switch. You can also switch the sensor ON and OFF by sending a signal from the MCU through the mikroBUS™ RST pin. The board uses a 3.3V power supply only.
http://www.mikroe.com/click/motion/

  2. Air Quality Click

Air quality click carries an MQ-135 sensor for detecting poisonous gases that impact air quality in homes and offices. The gas sensing layer on the sensor unit is made of tin dioxide (SnO2), which has lower conductivity in clean air. The conductivity increases with air pollution. The sensor reacts to ammonia (NH3), nitrogen oxides (NOx), benzene, smoke, CO2 and other harmful gases. To calibrate the sensor for the environment you’ll be using it in, Air quality click has a small potentiometer that allows you to adjust the load resistance of the sensor circuit. Air quality click communicates with the target board through AN (OUT) mikroBUS™ line. It’s designed to use a 5V power supply only.
http://www.mikroe.com/click/air-quality/

  3. Temperature and Humidity Click

Temp&Hum click carries ST’s HTS221 temperature and relative humidity sensor. Its temperature measurement accuracy is ±1°C within a 0-60°C range. The precision is increased to ±0.5°C in a narrower range from 15 to 40°C. The highly sensitive relative humidity measurement range is from 0 to 100% with ±6% accuracy (or ±4.5 in 20-80% range) The measurements are outputted in a 16-bit resolution through the mikroBUS™ I2C interface. The board uses a 3.3V power supply.
http://www.mikroe.com/click/temp-hum/

  4. Pressure and Temperature Click

Pressure Click™ is a compact and easy solution for adding pressure measurement to your design. It features LPS331AP digital output pressure sensor. LPS331AP IC is an ultra compact absolute piezoresistive pressure sensor capable to measure pressure (260-1260 mbar) or temperature (-40°C to 80°C) and provide a digital signal to main board microcontroller. Pressure Click™ communicates with the target board microcontroller via mikroBUS™ SPI (MOSI, MISO, SCK, CS), I2C (SDA, SCL) and INT lines. The board is designed to use 3.3V power supply only.
http://www.mikroe.com/click/pressure/
