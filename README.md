# Hand-Gesture-Control-of-Your-Computer
In this project, we have implemented a simple Arduino based hand gesture control where you can control few functions of your web browser like switching between tabs, scrolling up and down in web pages, shift between tasks (applications), play or pause a video and increase or decrease the volume (in VLC Player) with the help of hand gestures.


**Concept behind the project:**

* The concept behind the project is very simple. We will place two Ultrasonic (US) sensors on top of our monitor and will read the distance between the monitor and our hand using Arduino, based on this value of distance we will perform certain actions. To perform actions on our computer we use Python pyautogui library. 
* The commands from Arduino are sent to the computer through serial port (USB). This data will be then read by python which is running on the computer and based on the read data an action will be performed. 



    ![Control-your-Computer-with-Hand-Gestures-using-Arduino-circuit](https://user-images.githubusercontent.com/93218214/190712582-7cdbff1f-49cb-4dd6-b684-e8c18f450804.png)

Connection of components should be done according to the above figure . And follow the below steps

**Steps : **

* Install Python and Arduino IDE on your computer
* We need to install Python library-"PyAutoGUI" which is essential to give the keyboard commands to the computer 
* To install PyAutoGUI , Go to cmd promt - "python3" --> ENTER , then "pip install pyautogui" --> ENTER
* Import the Arduino code (Provided in this repository) and get the "port number" (Arduino IDE --> Tools --> Port:)
* Import the Python code and update the serial port number as in the arduino port number
* Run the Arduino code and simultaneously run the python code.
* The sensors starts to kick in.... "Voila!!"
* We can control our computer with our hand gestures.
