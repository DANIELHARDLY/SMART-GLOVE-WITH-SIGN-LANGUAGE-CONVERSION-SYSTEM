# SMART-GLOVE-WITH-SIGN-LANGUAGE-CONVERSION-SYSTEM
<img src="https://github.com/DANIELHARDLY/SMART-GLOVE-WITH-SIGN-LANGUAGE-CONVERSION-SYSTEM/blob/main/SMART_GLOVE_USING_ARDUINO_WITH_SIGN_LANGUAGE_RECOGNITION_SYSTEM.jpg" alt="Employee data" title="SMART GLOVE">
 In the recent years there has been a rapid increase in the number of hearing impaired and speech disabled victims due to birth defects, oral diseases and accidents.
Deaf and dumb person have their own language to communicate with us; the only thing is that we need to understand their language. 
This project aims to create a smart speaking system that helps mute people in conveying the message to regular people using hand motions or gestures.
It also aims to convert the voice of normal people into text and display the same.

Detecting the hand gestures with the help of flex sensors by analysing voltage according to the angle of bend of each finger.
Mapping the detected hand gesture to the corresponding letter and then to word.
Transmitting the detected word to mobile phone through bluetooth module. The transmitted word is displayed and read out to the normal person through the phone.
The speech signal of normal people is also recognised and displayed through phone.

METHODOLOGY

For each gesture the flex sensor bends at different angles. The flex sensor gives different resistance values depending on the bend of the sensor.

Using a potential divider circuit, a corresponding voltage value of resistance is given to the Arduino.

In Arduino, the voltage value is mapped to a corresponding  angle value using map function.

The angle so obtained is used for map the gesture to corresponding letter.

The letter thus obtained are combined to form a word and it is transmitted to a  mobile phone via bluetooth module.

An app is developed to display and read out the transmitted word within the phone.

The app is also programmed to recognise and convert the speech signal of normal people into text message and display the same.

HARDWARE REQUIREMENTS

ATMEGA328
8 Bit core size
Speed upto 20 Mhz
Ram size of 2k x 8
Flex sensor
Operating voltage of 0-5v
Can operate on low voltages
Power rating of 0.5 Watt,1 Wat
HC-05 (Bluetooth module)
Frequency of 2.4 GHz ISM band
Security : Authentication and encryption    
Modulation :GFSK

