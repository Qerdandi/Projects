# Pill Dispenser

**Revolutionizing Medication Management with a Programmable Pill Dispenser**

<p align="center">
  <img width="720" alt="pill_dispenser_3d" src="https://user-images.githubusercontent.com/73184884/192203932-5c512cc7-36a5-49a6-bf13-b65be91ccfda.png">
</p>

## I. Context

Welcome to the Pill Dispenser project, a remarkable achievement born out of a school endeavor. Our mission was to design a programmable pill dispenser that could effectively manage a patient's medication. To achieve this, we developed an application using Unity in C# to communicate with the pill dispenser powered by Arduino. The application empowers users to set treatment frequency, monitor medication reserves in the dispenser, and activate light and sound alarms to remind patients to take their medication. Additionally, the pill dispenser was meticulously designed in 3D using 3D Experience and brought to life with a 3D printer.

## II. Conception

We embarked on this project from scratch. We began by brainstorming the essential features of the pill dispenser and devising technical solutions to meet those requirements. Afterward, we dimensioned the pill dispenser and created a 3D model using 3D Experience. The physical pill dispenser was then materialized using a 3D printer. Simultaneously, we developed the application and the electrical circuit for the pill dispenser. You can find the source codes for both the pill dispenser and the application in this repository. Below is a sneak peek of the 3D model and the electric circuit of the pill dispenser:

<p align="center">
  <img width="720" alt="pill_dispenser_3d" src="https://user-images.githubusercontent.com/73184884/192203932-5c512cc7-36a5-49a6-bf13-b65be91ccfda.png">
</p>

<p align="center">
  <img width="720" alt="electric_circuit" src="https://user-images.githubusercontent.com/73184884/192292360-7244d05f-bba9-489b-8269-bbe5ee175003.jpg">
</p>

## III. Features

Behold the user-friendly interface of our Unity application:

<p align="center">
  <img width="720" alt="pill_dispenser_app" src="https://user-images.githubusercontent.com/73184884/192194851-119b0d8e-c188-4769-a67e-69cc5139f70b.jpg">
</p>

The application is divided into two main sections:

- **Data Monitoring**: This panel allows you to keep a close eye on humidity and temperature, ensuring optimal pill storage. Values turn red when conditions are unfavorable. It also displays the number of remaining intakes, ensuring you know when it's time to refill the dispenser.

- **Set-up**: These two panels enable you to activate alarms and configure intake schedules for each day. This feature simplifies experimental tests by allowing you to change parameters at intervals.

Once the connection is established between the application and the Arduino microcontroller of the pill dispenser, you can effortlessly send set-up parameters to the pill dispenser, ensuring it operates according to your preferences.

**Transforming Medication Management, One Pill at a Time!**

## IV. Project Status

- [ ] Work in progress
- [X] Work completed