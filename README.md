# HPM-Killer-Drone-
Design a high power killer drone , that radiates High power Microwave in the range of 30 Ghz to 60 Ghz

* First step is to start by designing the Antenna that radiates the HPM , so i went with vivaldi Antenna as my killer.
* The goal of my project is to create a drone that can shoot down enemy drones silently through using a High power Microwaves, effectively frying the motherboards of the enemy drones while also ensuring that the communication antenna of it's drone remians safe



*Below is the image of the Vivaldi Antenna that was designed for the drone , the design was created in Ansys's HFSS software :


<img width="1296" height="545" alt="Image" src="https://github.com/user-attachments/assets/ccd8a1e5-7495-4434-8bd5-b0e0be0a69de" /> 


*The below is the S-parameter graph obtained which shows the antenna radiating in 5 frequencies , each below return loss of -10, effectively acting as a UWB Antenna : 


<img width="1620" height="550" alt="Image" src="https://github.com/user-attachments/assets/c30a6e82-9757-4fb5-a2a0-fb75f6373fe1" />


*The below is the gain plot obtained , which shows the max gain of 5.46 Dbi , a little below than the intended gain of 8 and above to acta as a killer antenna , however , it is to be noted that , the Mesh settings of all the materials were set to 'Coarse' to keep the mesh cells below the limit of the student version (50 k) of HFSS. so the results might vary if the mesh were set to  "fine".


<img width="1613" height="539" alt="Image" src="https://github.com/user-attachments/assets/ead5a923-cb44-4e0c-a6c1-83f0051858cf" />

*Below is the Radiation efficieny obtained when the transmission line was taken as 50 ohms:


<img width="1619" height="551" alt="Image" src="https://github.com/user-attachments/assets/585562ce-f285-4e69-a24c-17c1119504e5" />


* The Smith Chart , which shows the frequencies curving around the centre of the 50 ohm line of resistance , however , the frequencies below the centre indicates the antenna is capacitive , the radial stub is too big so adjustments are needed to get more accurate results :

<img width="1616" height="546" alt="Image" src="https://github.com/user-attachments/assets/59a70ed1-ed2e-4e09-9008-c42a68688c7c" />



  
