## FEA - Gracie Steelmon

For this assignment I started by taking Kelseys calculations for the mounting bracket and designing it in Solidworks. Once I had that completed I opened up our previous CAD model from A10 and started to assemble. 

<img width="2101" height="2043" alt="<img width="767" height="322" alt="Screenshot 2026-11-17 105937" src="https://github.com/user-attachments/assets/a1085504-8fa4-4a4e-b3ba-a5e19ddcca66" />

Once I had the bracket on I then needed to decide on screws and nuts to use. The diameter of the hole was 6.6mm which is roughly 0.259843 inches. The screw I selected was a M4 x 0.7mm. This screw seemed more fit for a 6.6mm hole. Especially if this was the minimum diameter. For the length I added the thickness of the motor mount and the thickness of the cross head to become around 2.07 inches. From there I selected the 70mm long screw. This was the excess left over on the bottom can ensure that the nut will have enough length to fit and any vibrations will not cause things to fall apart. These are made out of 18-8 stainless steel. 

<img width="886" height="388" alt="image" src="https://github.com/user-attachments/assets/1571c766-708f-41bd-84e3-2383c41fd2ae" />
<img width="751" height="310" alt="image" src="https://github.com/user-attachments/assets/3fbd0ece-8c9d-4f42-b50b-8665ed00ff3d" />
<img width="793" height="380" alt="Screenshot 2026-11-17 105946" src="https://github.com/user-attachments/assets/755ec001-5631-436f-96a5-6d5318dd7a6d" />



### Fixed Geometry and Loads
For the fixed geometry I fixed the bottom of the entire bracket down. I did two loads of 1kN each down on the leadscrews. I also applied a torque going the same direction into the holes where the motor will sit at. This torque applied was 24.857 N-M. 
<img width="1242" height="729" alt="Screenshot 2026-11-17 125500 (1)" src="https://github.com/user-attachments/assets/1f53a527-4558-45c3-95c4-e20c1afe05c6" />
<img width="1632" height="885" alt="Screenshot 2026-11-17 130717" src="https://github.com/user-attachments/assets/335c16fd-3642-4dca-b334-5ea432f82544" />

<img width="1465" height="931" alt="Screenshot 2026-11-17 124428 (1)" src="https://github.com/user-attachments/assets/46b9834c-2a4f-4a5f-bfaf-96e327b5e141" />

### Mesh
For the mesh I ran into several problems. I initially tried to create it doing a medium sized mesh and it did not generate correctly other than blowing my computer up. Next I tried the course ones, this did not work either. So I went back to medium size and it worked that time. 

### Results
#### - Von Misses
<img width="1648" height="862" alt="Screenshot 2026-11-17 132749" src="https://github.com/user-attachments/assets/2d898f73-c823-4d27-ada1-fb55e13b7eb8" />

#### - FOS
<img width="1658" height="838" alt="Screenshot 2026-11-17 133239" src="https://github.com/user-attachments/assets/3d213265-15a0-4a0c-88ba-adc5180b6d2d" />

#### - Strain
<img width="1670" height="854" alt="Screenshot 2026-11-17 133032" src="https://github.com/user-attachments/assets/bbbaa978-45cc-4060-aa4f-eca9d73241d7" />


### Alternate Design Suggestions
This FEA did not turn out as bad as I thought. Some design aterations could be to change the material to be stronger. the torque had more effect than the 1kN load did. 

### CAD Files
<p><a href="C:\Users\gstee\OneDrive - University of North Carolina at Charlotte\UNCC_Fall_2026\Sophomore Design\A11\Assem2.zip"><strong>Download SolidWorks CAD Assembly</strong></a></p>
