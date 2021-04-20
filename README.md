# ECC608-Simple-Connection-Test-idf42-2

This communicates ATECC608A secure chip from ESP32 and get infos (serial number, revision number, and current config data),
it helps to make sure the connection between them.
This app supported by espressif32@3.1.0(esp-idf4.2) and cryptoauthlib@3.3.0 on esp-idf.  
for the reference, please also check platformio implementation, as follows.  
https://github.com/kmwebnet/ECC608-simple-Connection-Test-idf42  

# Requirements

  esp-idf4.2 with VS Code environment.  

# Environment reference
  
  Espressif ESP32-DevkitC  
  this project initialize both of I2C 0,1 port, and the device on I2C port 0 is absent.  
  pin assined as below:  


      I2C 0 SDA GPIO_NUM_18
      I2C 0 SCL GPIO_NUM_19

      I2C 1 SDA GPIO_NUM_21
      I2C 1 SCL GPIO_NUM_22
          
  Microchip ATECC608A(on I2C port 1)  

# Usage

"git clone --recursive " on your target directory.  
you need to change a serial port number which actually connected to ESP32.     

# Run this project

just execute "Flash" on esp-idf.   

# License

This software is released under the MIT License, see LICENSE.  
