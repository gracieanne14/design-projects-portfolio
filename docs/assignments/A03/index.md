# A3 – Parametric and FEA

## Objectives: 
Objectives:
-Use axial deflection modeling to design its dimensions
-Use parametric design to determine a bars length
-Introduce you to FEA (Finite Element Analysis)
-Introduce you to linking dimensions to appropriate parameters in CAD.
-Compare and contrast the different analysis

### Part 1 - Beam Design 
**a.)& b.)** For the initial workflow for this assignment, I wrote down the certain parameters given to me and as well as my unknowns so I could see my playing field! 
I decided to choose 3oolbf for my force value, and o.25 for my diameter value. Using the direct tension elongation equation from the Machinerys handbook from the class, I calculated my required length for my beam. My Youngs Modulus value came from the additional MatWeb material Property data link given to us on this assignment. 
![Initial Calculations](IMG_0286.jpeg)

I opened up the equations tab in solid works on the left hand bar tab and inserted all of my values. 
![Equation list from SW](Screenshot_2026-09-08_120247.jpg)

**C.)** Once all my equation values were completed I sketched a simple circle. I toggled on smart dimensions and when it was time to enter the dimension I wanted, I pressed the equal (=) sign on my computer and assigned the value to my diameter value from my equation sheet. I know that my dimension comes from the equation sheet by seeing the summation symbol beside the value! 
![Circle Sketch](Screenshot_2026-09-08_120358.jpg)

From there I did an extrusion, and same as the dimesnions go, I set my extrustion length to be the calculated length from my equation list. 
**Note** - putting all of your individual values in and then writing simple code to compute the formula makes this task easier in the sence of going in and changing values. That way if you wanted to change something all you have to change is that one value and it will do the computaition for you. 
![Extrusion Length](Screenshot_2026-09-08_120419.jpg)

## Material
For the material, I took the aluminum data sheet provided in the assignment and inserted those parameters into Solid Works as a new material. This was my calculations will line up with my FEA. 
![Alt text describing image](Screenshot_2026-09-08_121556.jpg)
## Part 2 - FEA Analysis

From there I noted that from my parameters list given that one of the sides of the bar must be fixed, so I added a fixed position in Solid Works. From there, I added my force on the other side, making sure that the force was pointing in the right direction is imperative to this assignment. 
![Fixted Feature]()
![Force in direction](IMG_0287.jpeg)


Once my fixed position was set and my force was applied, I made a mesh of my beam. 
![Mesh](Screenshot_2026-09-08_120644.jpg)
Once the mesh was generated I could press run, and run my simulation. 

![stress and safety factor calculation](IMG_0288.jpeg)
I calculated my max stress allowed as well as my safety factor based on calculated values and graph values from the FEA. 


## 3. Design Reflection
### A. My axial deflection ended up right on the tolerance edge for the assignment, which is okay! 
![Deflection calcs](IMG_0289.jpeg)
**i.)** There is not a absolute huge meaningful descrepency, yet I still would like to point it out. My theoretical calculations are larger than my values for the FEA analysis and I think I would like it to stay there. 
**ii.)** Although my calculated values and FEA values are extreamly simliar, I think they are agreeing over the fact that I inputed the exact material properties. If I was to use a similar material the calculations would be off, yet still applying the same principles.
**iii.)*** I trust my hand calculated values more than Solid Works. Although I am a young enginener, software can always have hidden problems. I'm not exactly sure when this version of solid works was released. 
### B.
![Pin Work](IMG_0290.jpeg)

## 2157 Students Only - Modify Design Parameters 




