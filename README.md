# Ansys_Static_CloseGripHandle
PROBLEM STATEMENT: Close-grip handles used in strength-training equipment are subjected to significant cyclic tensile and bending loads during use. Improper geometric design or insufficient material strength can lead to excessive stress concentrations, premature yielding, or fatigue failure—posing both safety risks to users and durability issues for manufacturers. The objective of this project is to evaluate the structural integrity of a close-grip handle using Finite Element Analysis (FEA) under realistic loading and boundary conditions.
GEOMETRY: The geometry was created using the SoldidWorks 2025 software. The design of the handle is an alternate variant of the common close grip handle used for lat pulldown or cable rows. The geometry was designed as a single part. The geometry can be subdivided into 3 subparts:  
a) Rounded triangular plate: consisting of a hole onto which the hook to connect to the cable of the equipment attaches.  
b) Connecting rods: 4 connecting rods at an angle of 55 degrees are attached to the plate.  
c) Handles: 2 rounded handles provided where the user applies force.  
Assumptions/Simplifications:  
a) Knurling (important for grip) is ignored as it does not affect FEA much and can cause excessive computation to mesh.  
b) Welds (all sharp edges are instead filleted with suitable radius to allow smoother stress concentrations.  
c) All bonds are rigid  
<img width="300" height="250" alt="image" src="https://github.com/user-attachments/assets/1332c1cf-796c-4971-b798-9b62bb916feb" />
<img width="300" height="250" alt="image" src="https://github.com/user-attachments/assets/f945ba8a-4611-44df-a8f2-e0ae3fac2fa6" />
<img width="300" height="250" alt="image" src="https://github.com/user-attachments/assets/4d95df59-7a5c-420e-918b-3e64a0376160" />

MESHING: Transition=Slow  
Mesh 1:
<img width="400" height="370" alt="image" src="https://github.com/user-attachments/assets/13b1f43c-1f60-4151-a189-4bb820de8040" />  
 Resolution=1  Span Angle Center=Coarse  Nodes= Elements=18300
