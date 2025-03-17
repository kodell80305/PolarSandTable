
I'm keeping this for my own use, but I'm going to start over with "3-in-1 robot" project and develop a fully parameterized rotational platform.

**Sand Table V2: Quick & Dirty Summary**

![image](https://github.com/user-attachments/assets/59cb72d1-698b-4071-9657-963adc26ed64)


* **What is it?** Build notes for version 2 of a sand table project. Think of it as a robotic Etch-a-Sketch but with sand\!  
* **Table Base:**  
  * Built cheap-ish using MDF, a pine circle, and PVC.  
  * Leveling with threaded rods (oops, should've used a finer thread).  
  * Rim and glass from a repurposed coffee table.  
  * Budget: Around $150-$175 for the base alone.  
* **Display:**  
  * 8-inch tablet mounted with a car headrest holder. Simple, but it works\!  
* **Rim/LED:**  
  * 3D-printed parts hold everything together: LEDs, glass sand surface, and a top glass layer.  
  * LEDs: Translucent PLA for now, but thinking of switching to silicone diffusers for a nicer look.  
  * Magnets for arm movement, with a bit of give (packing foam trick\!).  
  * Glass top: Need to source a new one, around 38-39 inches.  
* **Robot Controller:**  
  * DLC32 controller with a Raspberry Pi 2w to run the web interface (got it for a steal at Microcenter\!).  
  * Powering the Pi with a buck converter for now.  
  * Uses TMC2209 stepper drivers (don't forget to set that Vref\!).  
* **Robot Design:**  
  * Inspired by Tuan Nguyen's work (Dune Weaver project).  
  * 6-inch lazy susan as the base (surprisingly effective).  
  * Carbon fiber rods for the arm (strong and slippery\!).  
  * Optical sensor for rotation, Hall effect sensor for radial movement.  
  * Two stepper motors: one for each axis.  
* **Software:**  
  * Fluidnc for the DLC32.  
  * WLED for LED control (might try running the LEDs directly from the Pi later).  
  * Dune Weaver project software for the front end.  
  * All open source, which is awesome\!  
* **Things to Improve:**  
  * BOM (Bill of Materials) needs some love – costs are a bit underestimated.  
  * Hall effect sensor placement needs tweaking.  
  * Maybe make the tablet mount a bit prettier.

**In a nutshell:** It's a DIY sand table robot, built with a mix of new parts, repurposed items, and 3D-printed components. Lots of open-source software is involved, and there's still room for improvement\!

