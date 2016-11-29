# EE3-Final-Project

By Adrienne Mok, Ashwin Narkar, and Charlotte McGinn

Video Demo: https://youtu.be/_X1ppX7fblk

This project was part of the coursework for EE3 (Introduction to Electrical Engineering). The objectives of this course include: basic circuits techniques with application to explanation of electrical engineering inventions such as telecommunications, electrical grid, automatic computing and control, and enabling device technology; research frontiers of electrical engineering; and introduction to measurement and design of electrical circuits.

Our project:

Keyboard HEERO, a slight twist to the classic Guitar Hero game, allows players to channel their inner pianist and jam out to their favorite songs. As a stream of notes flows down, the player must hit the corresponding “piano keys” in time with the beat of the music. We chose this project because we thought it would be a fun way to demonstrate some of the fundamental electrical engineering concepts we learned this quarter. Through this project, we aimed to successfully design, build, and test the hardware and software of a game similar to Guitar Hero. In order to do so, we needed to design an appropriate circuit, integrate components with a microcontroller, and process and interpret signals.

Our project comprises of a microcontroller (Teensy 3.2), several pushbuttons, LED strips, a speaker, and a four digit seven-segment display. The LED strips give the player a visual representation of the notes as they fall down and the pushbuttons represent the keys of the piano. A speaker plays our game’s 8-bit song. The four digit seven-segment display shows the player’s score. Since the LED strips require a voltage of 5V to operate, we connected them to a DC power supply. Our microcontroller allows us to read different inputs, such as the current state of the pushbuttons, and send out different outputs, such as the light emitted by the LED strips. A bulk of this project involved programming the microcontroller to allow us to control the system in an appropriate manner.
