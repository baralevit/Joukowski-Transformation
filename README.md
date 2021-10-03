# Joukowski-Transformation
The Joukowski transform maps circles to lines, circular arcs, ellipses or airfoils depending on the radius and the center of the circle. \
Since the flow around a circle is known, using the Joukowski transformation we can discover the the flow patterns around elliptical cylinders or airfoils.

The following are examples of the transformation:\
Set the constant in the Joukowski transform to be 1 (a=1)\
A circle centered at the origin of radius 1 is mapped to a line:
<p align="center">
<img width="351" alt="1" src="https://user-images.githubusercontent.com/69160824/134475715-a7f21fd3-b61f-4b4a-b405-dbebed12a7fc.PNG"> 
</p>
 If the center is on the y-axis, and the circle cuts the x-axis on the non-conformal points (±1) then the circle is mapped to a circular arc:
<p align="center">
<img width="351" alt="2" src="https://user-images.githubusercontent.com/69160824/134475718-9c2d25b4-62db-4e1d-b095-a178bc7cdbdc.PNG"> 
</p>
A circle that engulfs the conformal points (for example circle at the origin with radius bigger than 1) is mapped to an ellipse:  
<p align="center">
<img width="351" alt="3" src="https://user-images.githubusercontent.com/69160824/134475719-e7de5061-e1f2-4be9-970a-9f802d847bea.PNG"> 
</p>
The Joukowski transform maps a circle to an airfoil when the circle passes through only one non-conformal point. For a symmetric airfoil consider for example a circle centered at (-0.5,0) with radius 1.5:
<p align="center">
<img width="349" alt="4" src="https://user-images.githubusercontent.com/69160824/134475722-b445f4ef-76b5-4335-ace5-d05ec72862d8.PNG"> 
</p>
For a cambered airfoil the center needs to by asymmetric with respect to the y-axis:
<p align="center">
<img width="349" alt="5" src="https://user-images.githubusercontent.com/69160824/134475723-7f7f42a3-8058-49d3-8bbc-1089bd66d083.PNG"> 
</p>

In general, note that if the circle passes through either of the two non-conformal points (±1 in this case) then the transformation contains a sharp edge, as we see in the airfoil examples above (the tail of the airfoil is sharp). Similarly, we see that two sharp edges exist when the circle passes through both of the non-conformal points, as demonstrated in the first two examples when the circle was mapped to a line or an arc. 
