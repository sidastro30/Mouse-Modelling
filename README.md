# Mouse-Modelling

```
Modelling the behaviour of the system using State Charts
Using Simulink – Stateflow to model & implement a system in terms of Hierarchical state machines
```
![image](https://user-images.githubusercontent.com/81389879/177148743-cc1458cd-4751-4e86-ba44-28550228b187.png)
```
The inputs to the mouse are:
• x, y co-ordinates (As we moves the mouse these co-ordinates changes)
• z value(Scroll wheel changes the value of z)
• LeftButton ,RightButton (values of these inputs can be 1 (pressed), 0(released))
Assumption: Buttons, wheel & pointer are independent. We are using mouse for reading a pdf. If wheel is scrolling up then output “UP” should be high. If wheel I scrolling down then output “DOWN” should be high. If we are moving pointer with LeftButton pressed(1), then the output “SelectText” should be high and it will go low if the LeftButton is pressed again. If there is a double left click then output “Zoom” should be high. The time interval between successive left click should be less than 2 seconds. If any of the outputs UP, DOWN, Zoom are high then after 2 seconds , these outputs will become low.
```
![20AT61S01_2_1](https://user-images.githubusercontent.com/81389879/177148963-bffa0d85-c808-44fe-b879-fb67d45f367e.jpg)
![20AT61S01_2_2](https://user-images.githubusercontent.com/81389879/177148950-f37ed22e-8664-472b-aeae-aa31736d12f3.jpg)
![select](https://user-images.githubusercontent.com/81389879/177148957-d09a4529-c314-412e-bffe-0233ce7502d7.jpg)
![zoom_scroll](https://user-images.githubusercontent.com/81389879/177148959-e047bf63-123c-449c-8592-751480cb541d.jpg)

