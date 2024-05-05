# StrobeShield
Submission files from our EurekaHacks 2024 project

This is simply a fork for individual changes/modifications

## My Contributions
- developed and manufactured the mechanical system (SolidWorks 2023, FDM Printing (Bambu X1 Carbon))
- worked on creating a custom algorithm to take instances of "high" and "low" light for every tick in a 60 Hz (second) period, and turn them into usable sums of consistent readings, which are summed in groups of 6 to determine if there is a long enough period of short flahses to be perceived as dangerous
- Tuned the 0.2 second polarization feature (motor time) and added bystander indication using an RGB LED
- Developed the function to send polarization events to a local network db (urequests -> flask)

This was done using Thonny and VSCode, pushing to a Raspberry Pi Pico W(ifi).

## Takeaways
Working with my amazing team to develop this solution to a medical issue allowed me to understand the implications of combining mechanical and electronic systems to make a positive impact. By working on this project, I was able to improve my MicroPython programming skills while also getting an introduction to Pico Wifi network capabilities. The issues we encountered with our detection due to our transfer away from using a testing breadboard provided valuable teachings to improving the process in which we are verifying that the physical changes we make are tested to function. 
