# Translating Laban Movement Efforts into Real-Time Swarm Behaviour
Sioux and AKOB thesis internship 

We have proposed a framework for mapping Laban Effort parameters on Particle Swarm movement.

## SYSTEM OVERVIEW:
<img width="914" alt="particles-overview2" src="https://github.com/user-attachments/assets/7938c7a8-362b-4392-a63f-a7fa8ae65187" />

Implementation was done in TouchDesigner. Every frame, particle coordinates are updated with a Python script (Fig. 4.B). It takes the input of slider values representing four Laban Effort parameters, as well as random noise over three channels (Fig. 4.A). Sliders are interactive, and the values are chosen in the range between 0 and 1, with both extremes representing the opposite poles of the respective Laban parameter. The positions are stored in a table (Fig. 4.C) that is directly connected to the rendering logic (Fig. 4.D) where the representation of particles is handled. Sliders accepting real-time input were overlaid with the responsive swarm to create an interactive window (Fig. 4.E).

## INSTALLATION GUIDE:
1. Install Touchdesigner:
   You can download the free non-commercial version here: https://derivative.ca/product/touchdesigner-non-commercial/77

2. Once you get TouchDesigner, open the laban2swarm.toe file
3. If you wish to interact with the mapping, you can simply manipulate the sliders in frame A above. Alternatively, you can open frame E as a separate Window (make sure Viewer active is unchecked, right click on the frame and choose "Open as Separate Window") and interact with the sliders in the bottom left corner. 

This is all, have fun.  

Example usage of this framework in an interactive system: https://github.com/zjgb/AKOB-movement-system
