// README

// Background
This repository contains a manufacturing drawing, circuit diagram, pictures of the devices I built, and STL files for a remote controlled lid opener designed for use in passive sampling of air contamination.
Passive sampling is a qualitative method of assessment using petri dishes with an agar nutrient medium that is used quite often to assess air contamination, 
but from what I have read, many researchers open and close plates by hand
this could be a potential source of contamination.
I wanted to avoid contamination as much as possible and so this is what I came up with.
As far as I know, only one other device exists for this purpose, the Sed unit, which is not commercially available, and is capable of opening and closing only a single plate at a time.
I built four of these devices for use in my masters project in as part of my MAI degree Mechanical and Manufacturing Engineering at Trinity College Dublin.

// Stands
I built 1 metre tall stands, with 30cm long wooden table tops to accommodate 2 plates. The lids of the plates were secured using M5 bolts,
and the top of the plates can be gently taped to the arms to prevent twisting while opening and closing plates

// Servos
I used servo motors with a 180 degree ROM to enable the opening and closing of the arms, you don't have to use this method however if you would prefer to use a different mechanism.

// WiFi Server
I controlled the servo positions with a simple web server like this one https://dronebotworkshop.com/esp32-servo/

// Power
I powered my ESP32s with portable chargers and the servos with 9V batteries which were attached to each stand
