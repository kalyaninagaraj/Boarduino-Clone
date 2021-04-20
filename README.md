# Boarduino Clone 
<a href="https://github.com/kalyaninagaraj/Boarduino-Clone/blob/main/Images/topview.png"><img src="Images/topview.png?raw=true" width="400px"></a>&nbsp;&nbsp; <a href="https://github.com/kalyaninagaraj/Boarduino-Clone/blob/main/Images/bottomview.png"><img src="Images/bottomview.png?raw=true" width="400px"></a><br />
This clone-of-a-clone is an adaption of the breadboard and through-hole parts-friendly [Arduino Uno](https://store.arduino.cc/usa/arduino-uno-rev3), a.k.a. [Boarduino by Lady Ada](https://learn.adafruit.com/boarduino-kits). 

The orginal Boarduino was designed with a ceramic resonator in mind, which isn't available at my local electronics stores. So I redesigned the layout in [Autodesk EAGLE](https://www.autodesk.com/products/eagle) to make space for the more readily available crystal oscillator. 

## Final Product
Check out this [blinking LED demo](https://youtu.be/2WAObtuopfo) for a look at the final (manufactured and assembled) board. 

### A Note On The Microcontroller 
I could only manage to get my hands on a [ATMEGA328-PU](https://www.microchip.com/wwwproducts/en/ATMEGA328), and not the Arduino-supported [ATMEGA328P-PU](https://www.microchip.com/wwwproducts/en/ATMEGA328P), which means bootloading troubles! Of the handful of workarounds that I found on the web, [this one](http://www.crash-bang.com/resource/bootload-atmega328/) helped the most.  

## Resources
Here are links to the original Boarduino, other Boarduino-like products, and some related resources. 
1. [DC and USB Boarduino kits and assembly tutorial by Lada Ada, Adafruit Industries](https://learn.adafruit.com/boarduino-kits). 
2. [Really Bare Bones Board (RBBB) by Modern Device](https://moderndevice.com/product/rbbb-kit/). Their [document on assembly instructions](https://cdn.shopify.com/s/files/1/0038/9582/files/RBBB_Instructions_06.pdf?1260749296) includes a great how-to section for soldering novices.
3. If the purple PCB in the video wasn't enough of a hint, I got the boards fabricated from [OSH Park](https://oshpark.com/)! 


## Hardware License
The design files are made available under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).

## Tags
#Open-Source Hardware #Arduino Uno Clone # Boarduino Clone #Adafruit
