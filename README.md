# Winterface - WIP
Software - firmware
Winterface started as an Arduino graphical interface that mimics / hopefully it will result to be kind of RTOS universal GUI.
What will / could be added:

- self detected video driver or default dummy video driver with minimal resolution *WIP
- calendar, date, clock kind of widgets
- specs info regarding storage, folders and files
- player for basic music and video files
- program to mimic a word processor app, basic calculation app, presentation app
- emulator/simulator for games that are free
- communication via BLE and Wifi

  # Hardware specs:
  - minimum CPU: 1 x microcontroller ATMega328P or alike (so it will be 1 dedicated CPU + 1 dedicated GPU if you have no dual core system )
  - minimum GPU: 1 x microcontroller ATMega328P or alike
  - minimum RAM 2KB + 2KB video graphical alocated RAM + at least 2KB framebuffer that can be upgraded (let's face it, graphical interfaces are RAM overkill so  )
  - microSD for user storage apps
  - possibility to add plug and play sensors
  - Wifi module or integrated
  - BLE module or integrated
  - screen: VGA output or HDMI for external video, internal monochrome 84 x 48 pixels, color TFT ST7735 or ST7789 or eInk- but not only limited to those, for GUI
  - with custom possibility to use 16x2 or 7 segments or RGB leds or neopixels, or any leds or led matrix - in terminal, but no GUI if no graphical display available
  - TBA later
    
    
