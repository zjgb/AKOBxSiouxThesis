# Translating Laban Movement Efforts into Real-Time Swarm Behavior
Sioux and AKOB thesis internship 

We have proposed a framework of mapping Laban Effort parameters on Particle Swarm movement.

SYSTEM OVERVIEW:
<img width="914" alt="particles-overview2" src="https://github.com/user-attachments/assets/7938c7a8-362b-4392-a63f-a7fa8ae65187" />

Implementation was done in TouchDesigner. Every frame, particle coordinates were updated with a Python script (Fig. 4.B). It took the input of slider values representing four Laban Effort parameters, as well as random noise over three channels (Fig. 4.A). Sliders were interactive and the value was chosen on the range between 0 and 1, with both extremes representing the opposite poles of the respective Laban parameter. The positions were stored in a table (Fig. 4.C) that was directly connected to the rendering logic (Fig. 4.D) where particle representation was handled. Sliders accepting real time input were overlaid with the responsive swarm to create an interactive window (Fig. 4.E).

INSTALLATION GUIDE:
1. Install Touchdesigner:
   You can download the free non commercial version here: https://derivative.ca/product/touchdesigner-non-commercial/77

2. Once you get TouchDesigner, Open the laban2swarm.toe file
3. If you wish to interact with the mapping you can simply manipulate the sliders in frame A above. Alternatively you can open frame E as a seperate Window (make sure Viewer active is unchecked, right click on the frame and choose "Open as Seperate Window") and interact with the sliders in bottom left corner. 

This is all, have fun.  

Example usage of this framework in an interactive system: https://github.com/zjgb/AKOB-movement-system
