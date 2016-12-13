# Ambient Popup Box using Particle Photon

The Ambient Popup Box is an Ambient display for your desk which tells you which country is being talked about (in this case USA and India) frequently in twitter during that time. This is a working prototype which is very easy to make and customizable.

## Getting Started

These instructions will help you get the project up and running on your local machine for development and testing purposes. See instructable for detailed step by step process of how to make it and notes on how to deploy the project on your system.

### Prerequisites

Things you will need to get this to work:

1. Particle Photon Micro-controller
2. Servo-motors (2)
3. Wires, Acrylic Glue, and a Glue Gun
4. Wood and Acrylic for laser cutting
5. Spandex or some sort of stretchable fabric
6. Illustrator files included with this project for laser cutting.

### Circuit Diagram

![circuit diagram](https://cloud.githubusercontent.com/assets/6739924/20318448/4ee76e80-ab38-11e6-9851-c9e40aab4cf8.jpg)

### Installing

1. Connect the OLED Display and the flora color sensor as shown in the circuit diagram.
2. Contain the Circuit in the enclosure (Enclosure made after laser cutting and 3D Printing). 
3. Flash the code from the saishColorSensor.ino to the photon either using the particle cloud IDE or locally.
4. Power up the photon and wait for it to connect to the internet.
5. Once it is connected to the internet, the rgb values will be displayed on the oled display.
6. For the input visualization open the saishColorSensorInputVisualization.html file on your web browser and notice the change in color of the bouncing ball.
7. That's all!


## Running the tests

Once the photon is powered up, open the terminal and type in "particle serial monitor" without the quotes.
 - If you are getting the values in the form (eg: 77, 79, 90), your color sensor input is working fine.
 - If you are gettig the values in the range 100 - 3000, the proximity sensor is working.
 - If you are getting "data: 77, 79, 90", your subscription to the cloud is working fine.
 - If you are getting the output on the OLED display in the form - "rgb(77, 79, 9)", then everything is working fine.

### Break down into end to end tests

The above tests are used to make sure that the input and output are working fine in collaboration.

## Deployment

No additional requirements are necessary except that you should flash the code to the photon and then open the "InputVisualization.html" file to view the visualization - the color of the bouncing ball changes.

## Built With

* Particle Photon Maker Kit - [https://store.particle.io/]
* Visualization is done using d3.js - [https://d3js.org/]
* Bouncing beach ball visualization got from "datavizclub.tumble.com" = [http://datavizclub.tumblr.com/post/119132679558/make-a-bouncing-beach-ball-with-d3]
* Lulzbot Taz 4 3D Printer
* Laser Cutter

## Images

![image-front](https://cloud.githubusercontent.com/assets/6739924/20318273/96d553c0-ab37-11e6-9217-719c6d854952.jpg)

![image-back](https://cloud.githubusercontent.com/assets/6739924/20318281/9debf79a-ab37-11e6-9f69-e3a6af9dc572.jpg)

## Authors

* Saish Menon - RIT
* Sangram Pawar - RIT

## License

Open Licence

## Acknowledgments

* Pubnub.com, particle.io
* Chandan Mahapatra
* Valerie Okpoko
* Eric Wang
