# BlacKnight V0.2 (GIT EM CONSTRUCAO) EMBREVE

Impressora 3D Continua 

# Hardware & Motheboard

1xRamps

1XAduino

1XRaspberry pi 3 // TESTES no RPI zero e RPI W


Frame:

barra quadrada aco 



#Manual de montagem e Firmware & Calibracao

Kit disponivel no site

Video de instalacao https://www.youtube.com/channel/UC1kUSBEEiYkj-MVS2Klydqg

CAD/CAM hospedado na pagina https://www.thingiverse.com/thing:3545725/files

Arduino CLI

Marlin

KLIPPER

OctoPrint

Blackbelt

GrassHopper(WINDOWS)

## Arduino CLI
  Primeiro vamos fazer o download e instalacao da IDE Aduino
  
         sudo apt-get install mono-xbuild 
         sudo apt-get install automake 
         sudo apt-get install autoconf 
         sudo apt-get install libmono-cairo2.0-cil 
         sudo apt-get install gtk-sharp2
         sudo apt-get install golang
         
         
         $GOPATH/bin/arduino-cli-0.3.6-alpha.preview-linuxarm
         $GOPATH/bin/arduino
         
         sudo arduino-cli
         sudo wget github.com/arduino/arduino-cli
         sudo apt-get install arduino-cli-0.3.6-alpha.preview-linuxarm
         sudo make install arduino-cli-0.3.6-alpha.preview-linuxarm

## Marlin
 Configuracao da Firmware IMPORTANTE

       
         #define HOMING_FEEDRATE {50*60, 50*60, 50*60, 50*60}  

// default settings

       #define DEFAULT_AXIS_STEPS_PER_UNIT   {80,93,53,122}    //X, Y, Z, E  
       #define DEFAULT_MAX_FEEDRATE          {128,128,128,64}  // (mm/sec)
       #define DEFAULT_MAX_ACCELERATION      {32,32,32,32}     // maximum start speed for accelerated moves. E default values are good for Skeinforge 40+, for older versions raise them a lot.

       #define DEFAULT_ACCELERATION          64    // X, Y, Z and E acceleration in mm/s^2 for printing moves
       #define DEFAULT_RETRACT_ACCELERATION  32    // E acceleration in mm/s^2 for retracts
       #define DEFAULT_TRAVEL_ACCELERATION   32    // X, Y, Z acceleration in mm/s^2 for travel (non printing) moves




 Atencao instalar U8glib na IDE ARDUINO na library folder: http://code.google.com/p/u8glib/wiki/u8glib

##KLIPPER


##OctoPrint

        sudo 
        ./OctoPrint/venv/bin/octoprint


##Blackbelt

Fatiador Blackbelt
https://blackbelt-3d.com/software


##GrassHopper

https://www.grasshopper3d.com/page/download-1








