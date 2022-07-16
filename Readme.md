# AETHER
Addressable LED controller powered by WLED. Sound reactive capable with IR receiver. Due to ESP32 is capable to produce FFT effects.
Designed as replacement electronics for SP511e. So it fits the same case.

### Features and components
- Compatible with 12V and 5V strips
- Built-on digital microphone (INMP411) 
    - Works with Sound reactive fork
    - Support FFT effects
- IR receiver for remote control
- Bootloader jumper
- 3 buttons for manual control

### SP511e replacement
This project is designed as replacement for SP511e electronics which is based on ESP8266 which is not capable of FFT effect and can only driver one line of LED strips.
You don't need to have SP511e controller but some part are salvageable. You can 3D print your own case.
Microphone is also replaced with digital omni-directional which has better results.

Some parts are salvageable from original board:
- Cables for LEDs
- IR receiver with cable
- Buttons
- Input power jack
- Case
