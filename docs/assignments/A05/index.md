# A5 – Bracket Design

## Objective's:
**-** Conduct stress analysis to determine appropriate dimensions for structural features.

**-** Generate free body diagrams (FBDs) to visualize forces and constraints for each feature.\

**-** Identify and document known and unknown variables, assumptions, and algebraic models for stress calculations.

**-** Perform stiffness analysis to establish minimum required dimensions based on deflection constraints.

**-** Compare stress and stiffness analyses to ensure structural integrity and compliance with given constraints.

**-** Create detailed multiview sketches illustrating dimensions derived from both stress and stiffness analyses.

**-** Reflect on and document key engineering lessons learned throughout the process.

## Initial Design
![Intro to the assignment](initial_Assignment.jpeg)
For this Assignmet, I was tasked with creating a mounting bracket for this piece. 
There were some basic guidelines to follow with the dimensioning, as well as some choices made up to me about this assingment. 
**Design Load:** My chosen force is 550lbf, so my p=f/2 value would be 275lbf. 

**Safety Factor:** 4

**Max Deflection:** 0.005 in.

*Assume no failure due to direct shear stress!* - for designing... 

## Material Choice
For this assignment I am choosing to use ASTM A36 Steel. There was no particular reason I picked this material at all. 
Some important information about the A36 I will use later on:
**E(Elastic Modulus)** = 29,000,000 Psi

**σy(Yield Strenght)** = 36,000 Psi

**σ_allowble** = Yield Stenght Divided by the Safety Facotr (4)... this comes out to be 9,000 Psi

## Feature A
### Initial Information:
I started by listing my knowns and unknowns. This has become a routine step in ALL of my assignments. This helps keep everything organized and easy to follow along with. 
![a analysis](A_Analysis.jpeg)

### A-Stress & Stiffness Analysis
After I gathered all of my information I calculated a stress and stiffness analysis on feature A using all of my previous information gathered. 
![a work](A_work.jpeg)

### A-Conclusion
After solving both algebraically and numerically, I found that the stress value was larger than the stiffness value so we could go with that one. From there I made the decision to round up to 1in. for my nominal dimension. Using the calculated dimension I double checked my work to make sure the value would withstand my requirments.
![a conclusion](A_Conclusion.jpeg)

## Feature B
### Initial Information:
For feature B we were told to treat it like an axial loaded bar. For this feature I used my values from feature A to carry on, I did this for all of my features foward in this assignment. 
![b analysis](B_Analysis.jpeg)

### B-Stress & Stiffness Analysis
![bwork](B_Works.jpeg)

### B-Conclusion
After conducting my analysis exactly like feature a, my stress value also governed for this feature. I decided to round my nomial dimesnion up to 0.250in. 
![bconclusion](B_Conclusion.jpeg)

## Feature C
### Initial Information: 
![c analysis](C_analysis.jpeg)

### C-Stress & Stiffness Analysis
![c analysis](C_Work.jpeg)

### C-Conclusion
![c conclusion](C_conclusion.jpeg)

## Feature D
### Initial Information:
![d analysis](D_analysis.jpeg)

### D-Stress & Stiffness Analysis
![d work](D_work.jpeg)

### D-Conclusion
![d conclusion](D_Conclsion.jpeg)

## Feature E
### Initial Information:
![e analysis](E_Analysis.jpeg)

### E-Stress & Stiffness Analysis
![e work](E_Work.jpeg)

### E-Conclusion
![e conclusion](E_Conclusion.jpeg)

## Drawings
### Stress
![stress](stress.jpg)

### Stiffness
![stiffness](stiffness.jpg)

I would like to note: These dimensions may be wrong. I am currently in the process of confusing myself so I may need to go back in and revise these drawings some :)

## Lessons Learned
For this assignment I learned how to apply my solid mechanics knowledge. With midterms approaching very fast (as in the next two weeks).. I am getting a little frustrated with these assignments, but I am taking it as an oppertunity to put in play all of this information I am learning, and turning it into a tool to study with. 

### Governing Failure Mode:
For every single feature, stress governed the dimensions. 

### Error propagation:
The forces became loading forces for all of the other features, they just built on one another. I am not sure if what I did for the force/2 was correct, maybe for feature A I should have kept it the same since it was a distributed load. This would change my dimesnions for A, which I think would've changed everything else. 

### Assumption Sensitivity:
For the material assumption. I think one important missing piece is the enviorment conditons. For the sake of this assignment they were left out to keep it simple. Yet in certain enviorments you want to chose material based on conditions, thermal expansion, how much sunlight it's getting, etc. I think maybe a different material would be choosen based on those. Just a small food for thought I like to consider. 

## 2157 Students Only - Fits
**1.**
![fits](fits.jpeg)

**2.** 
a. For this section of the assignment I used my Machinery's Hankbook Volume 32
This feature was desigated to be a Running/Sliding fit. From my calculation I am choosing a Class RC 4 Fit. With tolerances from the H8 hole. These charts are from page 645 in the book. 

![clearnece](clearencetype.jpeg)

b. 
![tolerance grades](tolerance_grades.jpg)

for this feature I will choose the reaming or boring manufacturing process. 

**3.**
a. For the 1 in shaft I am choosing the FN 1 class fit, with the tolerances of Hole H7. 

b. for this feature I will choose the reaming process. 


