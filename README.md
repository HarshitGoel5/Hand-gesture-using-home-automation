This Experiment is used to integrate python program with arduino using serial communication.

Packages required : opencv, pyserial, cvzone, mediapipe

Steps for doing this Experiment: About main.py:

Open any Python IDE, and use my main.py program.
Install serial package using the following command in terminal "pip install pyserial".
Install openCv package using the following command in terminal "pip install opencv-python".
Install cvzone package using the following command in terminal "pip install cvzone".
Install mediapipe package using the following command in terminal "pip install meidapipe".
In line number 5, we have port='COM_'. for getting the serial port number, goto device manager of your system > ports > check your arduino port number.
py

About LEDs_using_finger_count.ino:

Open arduino IDE and copy paste the program.
select the correct board and COM port and then upload the program.
For Connections:

we require:

4 LEDs
Arduino
some wires
circuit diagram:

py2

First of all Upload the LEDs_using_finger_count.ino program on to the arduino
Next in python IDE, Run the main.py program
Then check for the output
