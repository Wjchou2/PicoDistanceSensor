# PicoDistanceSensor
A distance sensor project made with an rpi pico, an ssd1306, an ultrasonic distance sensor and a button.

# Features
- Clean and easy to read data using ssd1306 oled display
- Conversion between CM and INCHES with the click of a button

# Code
The mean code is a while loop, which runs a method called detect_dist(), updates display, and checks for button presses. detect_dist() returns a number representing distance in CM of INCH depending on a variable. The display then updates. Finally, the loop checks for the value of the button. If the button has been pressed, it toggles the CM variable to switch between CM and INCHES. See more in demo link!
<img width="500"  alt="Screenshot 2026-05-02 at 11 51 06 PM" src="https://github.com/user-attachments/assets/2f7e341e-0e1e-41c6-9c82-ddceb9abe580" />


# Demo and Images

<a href="https://wokwi.com/projects/462980776891057153">Try live demo here!</a>  
  

<img width="500"  alt="Screenshot 2026-05-02 at 11 42 17 PM" src="https://github.com/user-attachments/assets/d3dc0611-0585-4299-9121-7b05677eeda0" />

<img width="500"  alt="Screen Recording 2026-05-02 at 11 43 19 PM (1)" src="https://github.com/user-attachments/assets/02f1a01d-a230-4be3-9e03-331538d70f9c" />


