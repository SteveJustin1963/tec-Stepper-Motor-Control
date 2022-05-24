# Stepper motors 
are diverse in their uses, but some of the most common include:
- 3D printing equipment.
- Textile machines.
- Printing presses.
- Gaming machines.
- Medical imaging machinery.
- Small robotics.
- CNC milling machines.
- Welding equipment.

My use will be to start with telescope control project in https://github.com/SteveJustin1963/tec-SCOPE as well as dc motors.
Next will be the https://github.com/SteveJustin1963/tec-Plot-PCB for making PCB tracks for etching.
The https://github.com/SteveJustin1963/tec-T800 will use servo motors and there control is completely different

### There are three basic types of stepper motors:

- Permanent Magnet Stepper. PM steppers have rotors that are constructed with permanent magnets, which interact with the electromagnets of the stator to create rotation and torque. ...
- Variable Reluctance Stepper.
- Hybrid Syncronous Stepper.
### or 
- Active rotor: permanent magnet step motor(PM)
- Reactive rotor: variable reluctance stepper motor(VR)
- Combination of VR and PM: Hybrid stepper motor (HY)

### Internals
- 4 pole
- 
![4-Phase-2-Pole-Stepper-motor-1](https://user-images.githubusercontent.com/58069246/169805899-64fd7d8c-22e7-4a66-b5e3-192cf447f756.png)


-6 pole

![3-s2 0-B9780128104910000114-f11-13-9780128104910](https://user-images.githubusercontent.com/58069246/169805536-7e0c8743-c56a-4ff5-a674-7aeb7645298b.jpg)

- 8 pole

![download](https://user-images.githubusercontent.com/58069246/169805646-be953efc-18c6-4e1f-9bf7-01ef2bdb0282.jpg)



### Wiring

![1](https://user-images.githubusercontent.com/58069246/169805317-22342ba9-7034-463e-9bbe-cfdbfc88d985.png)


### controller A4988

![mkmmprqskomonjmtkrrorttpqtsmsqntqmulFLCa](https://user-images.githubusercontent.com/58069246/169950912-ad9e476b-ac5d-4c3c-a0f2-931428dc3909.jpg)
![8688bdce6a8a958f6ddadffbchfbafhcbeg7rxou](https://user-images.githubusercontent.com/58069246/169950942-ea9a7659-74fd-472f-99cc-f6114c631746.jpg)
![dbddgihjbfdfeadkbiifikkghkglleklhgfcwCtv](https://user-images.githubusercontent.com/58069246/169950950-c8c92372-4900-4b52-af9a-1c3144217924.jpg)

### Key Features:
```
This product can operate bipolar stepper motors in full, half, 1/4, 1/8 and 1/16 step modes
Output drive performance up to 35 V and 2A
The A4988 includes a fixed off-time current regulator that operates in slow or mixed decay modes
The converter is the key to the easy implementation of the A4988. Just enter a pulse in the "step" 
input to drive the motor to generate microsteps
No need for phase sequence table, high frequency control line or complicated interface programming
The A4988 interface is ideal for applications where complex microprocessors are unavailable or overloaded.

Electrical Specifications:
Suitable for driving step motors below 8V ~ 35V 2A;
Simple step and direction control interface;
Five different step modes: full, half, 1/4, 1/8 and 1/16;
Adjustable potentiometer can adjust the maximum current output, so as to obtain a higher step rate;
Automatic current attenuation mode detection / selection;
Over-temperature shutdown circuit, under-voltage lockout, cross-current protection;
Short-to-ground protection and short-to-load protection
3.3V and 5V compatible logic current
Driving current algorithm: I = V * 0.8, the potentiometer has three pins. Use a multimeter to 
test the voltage between the pin facing 4988 and GND. The current can be adjusted by the potentiometer. 
Clockwise is to increase the current.Counterclockwise is to increase the current.
```


### Iterate

### Ref
- https://en.wikipedia.org/wiki/Stepper_motor
- 
