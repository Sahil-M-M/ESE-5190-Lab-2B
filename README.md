# Lab-2B-Submission-Dashboard

## Blinking the LED ##

## 1.   Gif of my breadboard LED in action.

As you can see here we are using a Breadboard, Adafruit QT Py RP2040, one resistor, RED LED, and Jumper wires. They are connected as shown in the picture below: <br>

<p align = "center">

<img width="466" alt="23435" src="https://user-images.githubusercontent.com/114259992/197166327-e9269731-d65f-478a-b7ae-c55757e642a2.png">

</p>

<br>

*LED Circuit*
<br>

After running our LED code with the same procedure as mentioned in the setup guide for Hello World <br>

https://github.com/AkshayaBhati/ESE-519-Lab-2-Setup-Guide/blob/main/README.md <br>

We can see the LED Blinking <br>

<p align = "center">

![LED Blinking (1)](https://user-images.githubusercontent.com/114259992/197149426-1547e072-1e63-4e48-97d8-a94ba02519f4.gif)

</p>

## Lab 2B Proposal ##

Here we are using a Push Button to on and off the LEDs operation. <br>

![Push Button GIF](https://user-images.githubusercontent.com/114259992/200097343-c4a57d90-a3b3-448c-83c6-eda3447c35b2.gif)

Then we are using a slider button. If it's in the right direction, then the right arrow will glow and similarly left arrow will glow for left direction. <br>

![Slider Button GIF](https://user-images.githubusercontent.com/114259992/200097311-2f6c758d-8df1-47ec-a82e-45455a65f793.gif)

The LED will glow in the shape of an arrow in the direction the slider button is moved. If in the right direction then 8 LEDs will glow, making a pattern of an arrow in the right direction and similarly for the left. It resembles the car's rear indicators. <br>

https://user-images.githubusercontent.com/114259992/200098455-5a24a71c-7320-4264-82a9-03bc9482b5e8.mp4

Block Diagram: <br>
<p align = "center">

<img width="328" alt="Block Diagram" src="https://user-images.githubusercontent.com/114259992/200098293-33d66632-55d5-4839-a8c8-d1333058cfc8.png">  

</p>


##	2.  An outline of what you plan to build, and why you think it’s cool.

o	What are we going to do: We are planning to use LEDs arranged in specific patterns to indicate in which direction a car is going to take turn (left or right).

o	Why do we want to do this: This idea has practical application and would be fun implementing.

![image](https://user-images.githubusercontent.com/73771085/197131422-b4575105-7297-4df1-a12e-76cf7cce27b1.png)

##	3.  Components requested from Detkin (after confirming availability):

o	2 Push Buttons

o	10 LEDs

o	10 330 ohms resistors for the LEDs

o	2 10 kilo-ohms resistors acting as pull up resistors for the push buttons

o	Protoboard

o	Breadboard and Jumper Wires

##	4. Proposal:

We have implemented the proposed circuit.

There are two buttons on the board: a slide switch and a push button. The push button enables the LEDs.

When the push button is pressed, depending upon the position of the slider switch, the LEDs in the shape of an arrow pointing in the direction selected turn on. When the button is released, no matter what the position of the slider switch is, no LED will turn on.

![Lab-2B-Proposal](https://user-images.githubusercontent.com/73771085/200074548-9859a580-284c-4cc2-bce4-f13ee1390a39.gif)

![Protoboard Front - Copy](https://user-images.githubusercontent.com/73771085/200075264-20a71a41-8a5f-45ec-86c7-24c38faa097a.jpeg)

![Protoboard Back - Copy](https://user-images.githubusercontent.com/73771085/200075266-6cbc3c12-737a-4f62-92c1-74f03048d18f.jpeg)




