# A7 – FEA on Bracket

## Objectives:
**-** Use Finite Element Analysis (FEA) to improve the bracket design from previous assignments.

**-** Ensure high stiffness, strength, and lightweight optimization through iterative design.

**-** Conduct multiple FEA simulations, refining geometry based on results.

**-** Perform static stress analysis, including constraints, loading, and meshing selection.

**-** Interpret data by identifying max stress, displacement, and safety factors.

**-** Optimize the design by modifying geometry to enhance performance.

**-** Document the entire process with images, calculations, and insights.

**-** Reflect on key engineering lessons learned and time spent.

## Description:
(directly from assignment) Your task is simply to create a high stiff, high strength, and lightweight component. Use Finite Element analysis to drive your decision making process throughout your design. Each step of the analysis and before you make geometric changes make sure the component’s results (stress/displacement/Safety Factor) converge on a 7% difference. Achieve this by modifying the number of elements. If after three attempts to converge use the stiffness and stress from the finer mesh size use the finest mesh size and proceed through the process.

## Initial Design
I will be using my same bracket design and CAD file from my A6 assignment. Here below I am speficifying my material (ASTM A36 Steel), this is the material that I based all of my calculations on for the previous assignments.
![](applying_material_choice.jpg)


## Design 1
**-** This initial design from A6. I have not modified anything from the previous assignments. 

I double checked that my parametric equations were still applied from last time as well!

![](Design1_parametric_equations.jpg)

### Adding Parameters
First I decided to apply my fixed position to the bottom of the top flanges, this will simulate this bracket being slided onto something with a load of the bottom. 
![](fixed_geometry.jpg)

Here I added the downward force of 275lbf. This is the force I used to make all of my calculations, which comes from the chose force of P=550lbf. My force values came from P=F/2. *Now that I check back on this maybe it was wrong to divide the force, but I will keep it consistent since that's what all my calculations are based on...
![](adding_force.jpg)

After the force was added, I created a mesh of the ENTIRE part. 
At the beginning of this assignment I had a hard time understanding the instructions, so I kept the mesh in the middle of the bar. Later on I figured out that we were supposed to adjust it. 
![](Created_Mesh.jpg)

## Work Flow
For each design I ran the simulations 3 times. I started with a smaller element value and increased each time. I combined a photo of all 3 for each run, just to make things easier to read/observe for viewers. For each design I created a chart showing all values that I obtained from my FEA's. 
Here below is how I adjusted each mesh value. I started with an initial courser value and went finner and finner. For all of the 3rd runs I have the bar all the way to the right indicating the finnest mesh possible. This allows for me to capture the highest percision possible for all of the graphs. 

![](mesh_design1_run2.jpg) 

### Design 1
#### D1-1
![](Design1_Run1_Collage.jpg)
#### D1-2
![](Design1_Run2_Collage.jpg)
#### D1-3
![](Design1_Run3_Collage.jpg)
#### D1-Resulting Data
![](design1_Data.jpg)
#### Discussion about data/changes
For this initial design I had some thoughts of it expericning high stress on the bottom flang, which it did. I figured for my design 2 I could add ribs between the drop down flange. 

### Design 2

![](design2.jpg)

#### D2-1
![](Design2_Run1_Collage.jpg)
#### D2-2
![](Design2_Run2_Collage.jpg)
#### D2-3
![](Design2_Run3_Collage.jpg)
#### D2-Resulting Data
![](design2_data.jpg)
#### Discussion about data/changes
For this design I still have some stress/deformation in the bottom, so the ribs only helped a little. This time I decided to add another structure to help hold the bottom up. 

### Design 3

![](design3.jpg)

#### D3-1
![](design3_run1_collage.jpg)
#### D3-2
![](design3_run2_colllage.jpg)
#### D3-3
![](design3_run3_collage.jpg)
#### D3-Resulting Data
![](design3_data.jpg)
#### Discussion about data/changes
Althought this structure did help, my side walls were very thin, and expirencing alot of stress and deformation. This was already my third design and I had alot of extra time so I decided to go ahead and do a 4th. 

## Additional Changes
### Design 4...
For this design I decided to make the side walls thicker to see if that would affect the results any. 
![](design4.jpg)

#### D4-1
![](design4_Run1_collage.jpg)
#### D4-2
![](design4_run2_collage.jpg)
#### D4-3
![](design4_run3_collage.jpg)
#### D4-Resulting Data
![](design4_data.jpg)
#### Discussion about data/changes
This did help a little, but it made that bottom edge expirence stress...I know if I did a 5th design and maybe added some more ribs it would help alot. This assignment only called for 3 designs.

## Reflections:
Going foward I would pay more attention to the initial design process of the bracket. (Assignment A5) Some things I did wrong could be choosing too much force, making my dimensions too long initially. This assigment allowed me to review more of the details involved with an FEA which is extreamly helpful. I know for a fact that this can help me in industry. I honestly am not happy with my design, and if I had more real world context I could design it better. This shows light on how much those other details really matter! This assignment was intensive in its nature and it took me around 5 hours to complete. 

## 2157 Students only:
-assignment does not clarify what needs to be done here (will update before due date)

## CAD FIles:
[A6 Bracket](A6_Bracket_Design.SLDPRT)
**-** My .CWR files are too large to insert, but you can see my design changes on this cad file! 

