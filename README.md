# 8-bit-Computer
An attempt to make...
# Components & Materials

- Two parallel lines of bread-board, Jumpers, Switch-SPST
- Li-ion battery 3S: ~12V(_preferred_)  or Alkaline battery: 9V

# Working Idea
## Stage 1
## Stage 2
# Code (Arduino)
Written on Arduino. There are two version: 
- Casewise/Conditional high-lows (_Used in NIRMAN-2.0_)  
    Codes: v0 and v3   
- PID (_Used in Wissenaire-23_)  
    Codes: v20,v21,v22,v32,v4
    v4 being the latest.  
    _Note_  that v4 code has an `speed(255,255)` in `//sharp left` case. This was a deliberate change to account for the multiple left turns in the track. This also helped in escaping a right loop(where normally it should have gone straight,into the loop); hence significantly reducing lap time.
# Circuit
Generic Design for motors with 5 sensors to arduino.
# Wirings

# Design
- 17cm (height) X 14cm (width) body.
- Front panel to stick IR sensors
- Cover panel to sandwich and hold the motors.

Since the cut was made on 5mm acrylic, the front panel was not required in the final setup. _Note_ that using the front panel keeps all the sensors one line, as in a generic setup. _Otherwise_ it stays in an inverted V shape which can give some strategical advantage (like detecting crosses better).
### Irregularities/Errors 
The top screw holes might be a bit off in the design, which was made to screw in the motor drivers.
# Members
Pritipriya Dasbehera (Mentor, Project head) - Idea
Someone - Code, Algorithm, Working Idea  
[Girija S. Ray](https://github.com/Alpha3125) (Mentor) - Code, Track Design, Circuit  
