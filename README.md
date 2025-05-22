# sioux-thesis
Sioux thesis project - Translating Laban Movement Efforts into Real-Time Swarm Behavior

This will be an interactive real-time framework developed to explore the mapping of Laban Effort parameters onto a particle swarm. The system will human motion as input, extract LMA (Laban movement analysis) effort parameters like Space, Time, Weight and Effort and generates responsive swarm behavior in real time, supporting the goal of dance company AKOB to create a particle cloud that mimics the movement dynamics of a human dancer.

At this moment, I have handled input and managed to extract Laban effort parameters. There is a mediapipe screen showing input stream on the left and a table with laban effort parameters and their values on the right.

![image](https://github.com/user-attachments/assets/101a7d26-25c4-4a06-b15a-a9c4865b32d0)

INSTALLATION GUIDE:
1. Install Touchdesigner
  Touchdesigner is a visualisation platform I am using the get input, handle all logic and visualise output of my project. You can download the free non commercial version here: https://derivative.ca/product/touchdesigner-non-commercial/77

3. Get Mediapipe plugin
   To get the medipipe plugin for touchdesigner follow this tutorial: https://github.com/torinmb/mediapipe-touchdesigner

4. It will download a folder called release. In that Folder, there is a TouchDesigner project file called MediaPipe TouchDesigner. Delete it and replace it with the MediaPipe TouchDesigner file in this repository.

6. If there is a problem with importing libraries check this video: https://www.youtube.com/watch?v=jUouJcGDRPk&t=1s

This is all. Now just open the MediaPipe TouchDesigner project and set medipipe operator Webcam to your computer's webcam (in case it's not yet) and observe the extracted Laban Effort Parameters from your video stream. 

