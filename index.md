# Hexapod
<!---Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!-->

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Arunabh T | Monta Vista High School | Aerospace Engineering | Incoming Senior

<!---**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)-->
  
# Final Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/BjwcGSSZ8Yg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my second milestone, I finished assembling the rest of the legs of the hexapod. I was able to accomplish this rather quickly because I had assembled the parts of all six legs while working towards getting to my first milestone. This made it so that I only needed to screw together the componenets of each leg for them to be mechanically finished. However, the wires of the 18 servos on the robot were quite messy and would touch the floor, and so I used the provided cable tidy to keep the wires together and take up less space. 

After this, I calibrated the servos. This was a process where I moved each legtip to a specific spot marked on a callibration paper, and the positions of the servos were saved onto the robot controller. This ensured that every time the robot started up, it would be able to start at a fixed position. With the hexapod callibrated, I moved on to testing it with the functions in the Processing app. The robot was able to walk, turn, move up and down, and perform several other functions. 

Now that I'm done with my second milestone, I will work on getting to my third. This involves getting the robot to perform all of these functions with the controller, and I also want to add a mount to the top of the robot for the battery to sit on.

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/CvkdEz7TmwI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Here is my first milestone for my main project. I chose the hexapod since it looked fairly complex as well as customizable, and it had components of mechanical, electrical, and software engineering in it. The robot is made of several acryllic parts, a robot controller that runs on Arduino code, as well as 18 servos that move the six legs of the robot. While the final project will run with a remote control, it can also move while connected to my computer with the inputs fed through the Processing application. So far, I have built the entire base of the hexapod and also created all components of the six legs. I have gotten one of these legs fully assembled onto my robot, and it fully functions with the commands on Processing.

The biggest challenge so far has been getting the leg to work with the basic code. Although I did manage to get the servos running first try, the default position seemed to face completely upwards. I tried various solutions to fix this, but nothing seemed to work. After doing a little bit of research, I found out that the servos needed to be powered while I assembled the leg, so that it could default to a position closer to what I wanted. 

My plan now is to continue assembling the legs of the robot. Once they are assembled, I will callibrate the hexapod and test them with the provided code through Processing. At that point, I hope that it is able to walk and turn with no issues whatsoever.

# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Hexapod | What the item is used for | $126.95 | <a href="https://www.amazon.com/Freenove-Raspberry-Crawling-Detailed-Tutorial/dp/B07FLVZ2DN/"> Link </a> |
| Camera | What the item is used for | $25.99 | <a href="https://www.amazon.com/Arducam-Module-Megapixels-Arduino-Mega2560/dp/B012UXNDOY"> Link </a> |
| Bluetooth module | What the item is used for | $10.99 | <a href="https://www.amazon.com/DSD-TECH-Bluetooth-iBeacon-Arduino/dp/B06WGZB2N4/"> Link </a> |
| Arduino Mega 2560 | What the item is used for | $48.90 | <a href="https://www.amazon.com/ARDUINO-MEGA-2560-REV3-A000067/dp/B0046AMGW0/"> Link </a> |

# Starter Project - Arduino

<iframe width="560" height="315" src="https://www.youtube.com/embed/97nzk2poyUE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Here is my starter project. It is an arduino board with a proto shield on top of it as well as a breadboard on the side. This proto shield allows me to wire several components on top of the arduino. I also used a breadboard to wire a button to the arduino. I have wired two LEDs onto the proto shield, and they are both controlled by the button. I coded them such that the red LED only turns on while the button is pressed, and the green LED is turned on and off whenever the button gets pressed.

One of the biggest challenges I faced was with getting the button to work. I originally wanted to have the button soldered onto the proto shield, but after testing code with this setup, I found out that it was not a stable input source. After doing a little bit of research into wiring buttons, I learned that I needed a constant power source and resistor at the ground source, and so I made the decision to switch to wiring the button on my breadboard instead.

My starter taught me several basics of arduino code, such as how to initalize inputs and outputs, and I also learned how to use a breadboard. It also helped me refine my soldering skills, and I have become much more precise with soldering smaller wires together.

## Starter Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Arduino UNO | Deploys the code and provides power to all components | $15.19 | <a href="https://www.elegoo.com/products/elegoo-uno-r3-board"> Link </a> |
| Breadboard | Allows for free wiring of buttons, sensors, and other components | $6.75 | <a href="https://www.amazon.com/BB400-Solderless-Plug-BreadBoard-tie-points/dp/B0040Z1ERO"> Link </a> |
| Proto Shield for Arduino | Allows for soldering of several components, and also provides custom space for buttons, LEDs, and capacitors that come with the shield. It also has extensions of several arduino ports.| $9.95 | <a href="https://www.adafruit.com/product/2077"> Link </a> |

## Starter Code
```c++
int buttonPin = 13;
int redLedPin = 8;
int greenLedPin = 9;
int buttonState = 0;
int buttonStore = 0;
int pressed = 0;

void setup() {
  pinMode(redLedPin, OUTPUT);
  pinMode(greenLedPin, OUTPUT);
  pinMode(buttonPin, INPUT);
}

void loop() {
  buttonState = digitalRead(buttonPin);
  if(buttonState == HIGH){
    digitalWrite(redLedPin, HIGH);
    if(pressed == 0){
      pressed = 1;
      if(buttonStore == 0){
        buttonStore = 1;
      }
      else{
        buttonStore = 0;
      }
    }
  }
  else{
    digitalWrite(redLedPin, LOW);
    if(pressed == 1){
      pressed = 0;
      if(buttonStore == 0){
        digitalWrite(greenLedPin, LOW);
      }
      else{
        digitalWrite(greenLedPin, HIGH);
      }
    }
  }
}
```

<!---# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.-->
