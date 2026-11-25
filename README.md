# EX.No.2.1  CREATE A 3D SOLID MODEL FROM ISOMETRIC DRAWING
## Date:

## AIM
To create a 3Dmodel from the given isometric drawing using fusion 360 tool. 

## REQUIREMENTS
Software: Autodesk Fusion 360
System Requirements:
o Operaüng System: Windows 10/11 (64-bit) or macOS
o Processor: 64-bit x86-based processor (Intel/AMD) or Apple Silicon
o RAM: 4 GB minimum (8 GB or more recommended)
Intemet Connection: Required for licensing and cloud services
Reference Specifications (from drawing):
- Main Body Dimensions: Width = 100 mm, Height = 50 mm (depth can be
derived or set based on standard proportions, e.g., 35 mm based on top-view
depth indicators).
- Main Lens: Diameter (4) 50 mm, Extrude/Length 20 mm.
- Top Central PrismfViewfinder Housing: Width 30 mm, height/angle details
(450 bevels).
- Top Right Button: Diameter W) = 20 mm, Height = 5 mm, offset by 15 mm and
15 mm from edges
- Top Left Square Button: 15 mmx15 mm, Height 5 mm.

## PROCEDURE
 
Step 1: Creating the Main Body
• Objective: Create the primary rectangular housing of the camera.
1. Create Sketch: Click on Create Sketch and select the Front Plane (XY plane).
2. Draw Rectangle: Select the Two-point Rectangle tod from the sketch palette. Click
on the origin (0,0), drag outwards, and set dimensions:
o Width: 100 mm
o Height: 50mm

<img width="890" height="612" alt="image" src="https://github.com/user-attachments/assets/b031ca16-ceb1-472c-8309-23340d14e12a" />

3.Finish Sketch: Click Finish Sketch in the top right toolbar.

4.Extrude 1 Details:

Press E (or go to Create > Extrude).
Select the rectangular profile.
Direction: One-side
Distance: 35 mm (Depth of the main camera body based on the top-view
layout dimensions).
Operation: New Body
Click 0K.


<img width="561" height="702" alt="image" src="https://github.com/user-attachments/assets/b9a96a59-c825-4527-909d-efa88b4b51b9" />


<img width="1007" height="786" alt="image" src="https://github.com/user-attachments/assets/16f1c63f-9b1c-46be-8ad4-6563ebbfbd5a" />




Step 2: Creating the Main Camera Lens

Objective: Model the prominent circular lens protruding from the front Of the camera

- Create Sketch: Click Create Sketch and select the Front Face of the main camera
body as your sketch plane

- Draw Circle: Select the Center Diameter Circle tool (C).
o Locate the center point by snapping to the vertical centerline of the front face
o Draw a circle with a diameter Of $50 mm.
Add dimension constralnts to position it centrally if necessary

<img width="907" height="617" alt="image" src="https://github.com/user-attachments/assets/915ae8ea-68e8-45b8-a225-d5d809a801bf" />

3.Finish Sketch: Click Finish Sketch

4.Extrude 2 Details:
- Press E to open the Extrude dialog box
- Select the circular profile of the lens
- Direction: One-side
- Distance: 20 mm (as specified for the lens protrusion depth in the drawing).
- Operation: Join (so it merges smoothly with the main body).
- CliCk 0K.

<img width="625" height="632" alt="image" src="https://github.com/user-attachments/assets/f1ff4db4-ee5a-4b59-8a77-1884d41ad7c3" />

<img width="911" height="726" alt="image" src="https://github.com/user-attachments/assets/e6262986-1853-4ceb-8adb-4007f6fc834c" />

Step 3: Creating the Top-Right Circular Button

2.Objective: Model the cylindrical control button located on the top right surface

- Create Sketch: Click Create Sketch and select the Top Face of the main camera
- Draw Circle:
- o Use the Center Diameter Circle tool (c).
- Position the cirde using sketch dimensions: 15 mm from the right edge and
15 mm from the back edge (referencing the layout dimensions).
Set the diameter to mm

<img width="640" height="757" alt="image" src="https://github.com/user-attachments/assets/3b895c06-8866-4009-8994-e7ec2499f4a7" />

3.Finish Sketch: Click Finish Sketch

4. Extrude 4 Details:
o Press E and select the circular profile.
Distance: 5 mm (height Of the button protrusion).
Operation: Join.
Click 0K.
- EXTRUDE
Type
Profiles
Start
Direction
Extent Type
Distance
Taper Angle
Operation
O
2 selected 

<img width="501" height="590" alt="image" src="https://github.com/user-attachments/assets/5184f8c0-b031-42c1-840a-b01c6f64f7d0" />

![Uploading image.png

STEP 5: Creating the Top Central Prism I Viewfinder Housing (Extrude &
Chamfer)
• Objective: Model the raised central housing block on top of the camera and shape
its front profile with a 45 bevel.
1. Sketching and Extruding the Housing Block
• Select Sketch Plane: Click Create Sketch in the top toolbar and select the Top
Face of the main camera body.
• Draw Profile: Select the Two-Point Rectangle tod, draw the footprint on the top
face, and apply dimensions based on the drawing:
Width: 30mm
o Depth/Length• 30mm
o
Position: Offset 10mm forward from the rear edge of the camera body and
horizontally centered
•
Finish Sketch: Click Finish Sketch
Extrude: Press E, select the rectangular profile, set the Direction to One-side, enter
a Distance of 10mm (housing height), set the Operation to Join, and dick 0K.
2. Applying the 45 • Chamfer
Access Tool GO to the top menu and select Modify > Chamfer.
Select Edge: Click on the top-front horizontal edge of the newly extruded housin


<img width="532" height="377" alt="image" src="https://github.com/user-attachments/assets/4db5f9f0-4db2-484a-9ae5-03e16bccb69c" />

2. Applying the 45 • Chamfer
- Access Tool GO to the top menu and select Modify > Chamfer.
- Select Edge: Click on the top-front horizontal edge of the newly extruded housing
dock
- Configure Settings: Set the chamfer type to Distance and Angle, and enter an
angle of 45 • to match the drawing's specified bevel.
- Finalize: Review the preview to ensure the slanted prism shape is correct, then clic


<img width="387" height="737" alt="image" src="https://github.com/user-attachments/assets/fcf5a54e-8aeb-40ef-9b57-7e29c3b2aeae" />

<img width="575" height="437" alt="image" src="https://github.com/user-attachments/assets/85a1da02-04b8-4bd3-a189-2114ebf541b5" />
<img width="677" height="437" alt="image" src="https://github.com/user-attachments/assets/0d0a3497-d5ce-4928-b6be-81b40a24ec73" />



## OUTPUT

<img width="702" height="512" alt="image" src="https://github.com/user-attachments/assets/ed57448c-6244-46b4-9989-a638053cb96d" />


<img width="1025" height="720" alt="image" src="https://github.com/user-attachments/assets/cbb21efc-4576-4136-8c3c-e5a7138d1d58" />

## RESULT: 
 Thus, the 3D model is created from given isometric drawing.
