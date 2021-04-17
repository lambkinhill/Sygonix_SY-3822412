# Sygonix_SY-3822412
* Sygonix SY-3822412 WiFi switch
* settings for platformio and arduino  

## for your source code
```
// power consumption:
// 1,5W on relay
// 0,8W off relay
//
// Relay is on GPIO4 = ON=1, OFF=0
#define RELAYPIN 4
// LED Red is on GPIO 13 ON=1, OFF=0
#define LEDREDPIN 13
// LED Blue is on GPIO 15 ON=0, OFF=1
#define LEDBLUEPIN 15
// button on GPIO 12 pressed = 0, button released = 1 
#define BUTTONPIN 12
```

## for platformio.ini
```
[env:esp01_1m]
platform = espressif8266
board = esp01_1m
framework = arduino
board_build.flash_mode = dout
```

## hardware details
* pin headers added
![Sygonix SY-3822412](https://github.com/lambkinhill/Sygonix_SY-3822412/blob/main/Sygonix_SY-3822412.png)
