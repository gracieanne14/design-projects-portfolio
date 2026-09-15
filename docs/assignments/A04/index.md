# **A4 – Motor Mount**

## **Objective**
**-** For this assignment, I was tasked with designing a motor mount to support the given motor of choice. In the image below I am providing the details of the assignment. We were given a link (which will be posted below), and a set of drawings. All design specifications on the image were taken directly from the website. 

https://www.omc-stepperonline.com/brushed-24v-dc-gear-motor-3-6kg-cm-46rpm-w-99-5-1-planetary-gearbox-pa28-28245800-g100 

![Intro to the assignment](intro_assignment.jpeg)

## **Material**
Before I started on any designing, I decided to do some research on my material selection, for this assignment I choose to use PLA. Below in the image provided is some basic information. Understanding your material you are using is essential to understand the manufacturing process that needs to proceed!

![material_properties](material_properties.jpeg)

## **Feature 1:**
For feature one, I started by identifying which piece of my mount was actually feature 1. From there I listed all of my knowns and unknowns. This allows me to develop a baseline for the assignment, for this feature. 
![knowns and unknows for f1](know_unknowns.jpeg)

Once I established those I decided to create an sheet of Feature 1. This sheet included the equations from class on designing a feature for stiffness and strength. I will design for **BOTH** features using these equations! 
![knowns and unknows for f1](feature_1_intro.jpeg)

From there I sketched an FBD of feature 1, and solved it for the moment. The moment is one essential piece we will need for our equations given to us from class...
![f1FBD](feature1_FBD.jpeg)
After solving the forces, I found my Max normal stress so I can apply it to my equations from class. From there I used all my known values from my previous tables to solve "B". I solved first for b under stress, which is also known as the "Strength". From there I also solved for b under deflection. Also known as "Stiffness". Once I had both values, I set up a comparison for both values. Since my strength value was larger than my stiffness value, the final B1 value is **4.577mm**. 

**NOTE** - all my values are in mm. I decided to keep them since the values from the drawing of the motor is in millimeters ( and the fact inches for this assignment was a reach). 

## **Feature: 2**
For feature 2, I essentially repeated the workflow. I first listed all my knowns and unknowns.
![f2intro](feature_2_intro.jpeg)

Next (like F1) I drew my FBD. For solving the forces on this one you had to pay CLOSE attention. As you can see from the note on my drawing, the bottom end was free to bend. This means it was not attached. I also decided to make my holes a 2mm offset from the bottom and side walls. I just randomly choose this value. Solving for the moment was a formula I had to remember from statics! From there, just like F1 I had to solve my max normal stress so I could apply it to my equations. Once solving both strength and stiffness I compared my values (just like F1) and found that my strength value was larger than my stiffness value. So, my final B2 value is **2.167mm**. 
![f2FBD](feature_2_FBD.jpeg) 

## **Motor Mount Inspiration**
Linked here is some inspiration for my mount I researched.
https://www.aliexpress.com/item/1005005721086783.html
https://www.dhgate.com/product/steel-42-stepper-motor-mount-bracket-nema17/996764543.html
-also the one from class
## **Isometric Drawing:**
Once I was finished with solving all of my values I drew a isometric sketch of my part, that way I can use it as a reference in SolidWorks!
![isosketch](iso_sketch.jpeg) 

## **SolidWorks Model of Motor Mount:**
For this model I used my knowledge of the parametric equations, I entered some of the values I calculated and used them when modeling. 
![parametric](Parametric_equations.jpg) 

From there I used these equations to draw my initial sketches and define dimensions when extruding. 
![parametric](initial_base_sketch.jpg) 

![b1extrusion](b1_extrusion.jpg)
I extruded using my B1 calculated value, from the parametric equation table
![addingb2](adding_b2_dim.jpg)
Here I did the same for B2
![screwhole_ref](screwhole_datumreference.jpg)
For the screw holes, I added lines to verify my dimensions were correct. Once I knew I deleted them. 
![screwholes](screw_holes.jpg)
I extruded all of the screw holes here. 
![motordivit](initail_divit.png)
I added my large divit into the base using my diameter value from the part specifications. 
![insidehole](inside_hole.png)
I also added the inside hole.
![sidesupp](sidesupports.jpg)
To prevent any added deflection, I added two side supports. 
![partFinal](final_parts.jpg)


## **2157 Students Only:**
For this section, I was asked to create a drawing for my part...
![Partdrawing](drawing.jpg)
I made sure to add my material specification and all deminsions needed to recreate this part. I also toggled on my hidden lines so you could see everything you need to. 

## **CAD Files:**
[A4 Motor Mount PART](A4_Motor_Mount.SLDPRT)
[A4 Motor Mount DRAWING](A4_Motor_Mount_drawing.SLDDRW)
[A4 Motor Mount DRAWING PDF](A4_Motor_Mount_drawing.pdf)

## **Lesson Learned:**
For this assignment I decided to complete the work before uploading, that way I would not have to keep going back and making so many changes. It makes the workflow much more simpler doing it this way. I also got to learn more about solid mechanics, which is a class I'm currently in so I'm in the process of learning! Initially I made the mistake of only solving for Stiffness on one beam and then solving for strength on another, but I quickly caught my mistake after reading the instructions again...before I started cading anything (close call there!) 

## **Time...?**
This assignment took me around 4 hours to complete!
