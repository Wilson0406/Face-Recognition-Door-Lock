# Face-Recognition-Door-Lock

During the current covid pandemic, it is important to restrict and slow down the spread of virus. There are some devices at our main gate that comes in contact with others as well. This Face Detection & Recognition enabled Door Lock Mechanism which will prevent spread of infection through door knobs, door-bells and also provide stronger security system.

The algorithm is first trained to recognize and store faces in the database. Now, if a person shows up at the main door, the system will scan their face. If that person is authentic, the door lock will open and greet them with a welcome voice, else the door will not open. With its 83% confidence threshold, it is impossible to trick the system by showing image on a phone. This way, our implemented system is much secure and hygienic than traditional locks.

Coming to the technical part, we implemented this on Arduino UNO Microcontroller using OpenCV, Numpy, Pyserial, Pyttsx3, Bitcraze Crazyflie Python Client and TinkerCad for Simulation. 

## Software Required:
* Python 3.9+IDE
* OpenCV
* Numpy
* Pyserial
* Pyttsx3
* Bitcraze Crazyflie Python Client 
* TinkerCad for Simulation

## Hardware Required:
* Arduino UNO Microcontroller
* Jumper wires
* Connecting cable
* Servo Motor
* Door Lock (Lever Typer)
* Camera
