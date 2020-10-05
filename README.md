
# CS4331 - Virtual_Reality 5331 Project-1 Report

## How covid-19 effected your surroundings

Demo link :arrow_forward: https://rohithreddyanugu.github.io/VR-Project-1/     
Video :point_right: :point_right:https://youtu.be/nNR9FYp3B1A  :point_left: :point_left:

## Features:
:arrow_right: Language:  a-frame:heavy_plus_sign: three.js

:arrow_right: add models using 
```
<a-assets>
      
      <a-asset-item id="CeilingfanO" src="https://cdn.glitch.com/1eae885f-ae53-4ff4-8f1d-24b94e81e988%2F74e63c0c-df5a-4f88-a0dc-e7118cf071c5_540%20Ceiling%20Fan.obj?      v=1600892230889">
      </a-asset-item>
      <a-asset-item id="CeilingfanM" src="https://cdn.glitch.com/1eae885f-ae53-4ff4-8f1d-24b94e81e988%2F74e63c0c-df5a-4f88-a0dc-e7118cf071c5_540%20Ceiling%20Fan.mtl?v=1600892224
      
      a-obj-model rotation="0 90 0" position="11 1.5 -2" scale="2 4 2" src="#CeilingFanO" mtl="#CeilingFanM"></a-obj-model>
      
```

### Room layout
The screenshots below show different angles of the room and the various models in the room. The room is a rectangle with a size of 22 by 23. Most of the models that are used in this room were from [Poly](https://poly.google.com/). The room was first made using [Glitch](https://glitch.com/) then imported to GitHub. There are  different lights in the room, 3 are used to show orange fading lights on the object. The last light is used for lighting the room with an ambient light. The dynamic objects in the room are the ceiling fan and the pikachu. The fan rotates at it's position in clockwise direction whereas pikachu moves from one point to the other and also produces a sound pikaa pikkaa!! when you click on the position given to it.
The Room also contains several posters on the floor and also on the walls that encourages to stay safe by maintaining social distance, regularily sanitizing of hands and by wearing masks.

### The pictures shows an overview of the how the room is!

![alt text](https://github.com/rohithreddyanugu/VR-Project-1/blob/main/2020-09-27%20(1).png)
![alt text](https://github.com/rohithreddyanugu/VR-Project-1/blob/main/2020-09-27%20(10).png)
![alt text](https://github.com/rohithreddyanugu/VR-Project-1/blob/main/2020-10-04%20(3).png)
![alt text](https://github.com/rohithreddyanugu/VR-Project-1/blob/main/2020-09-27%20(3).png)
![alt text](https://github.com/rohithreddyanugu/VR-Project-1/blob/main/2020-09-27%20(6).png)
![alt text](https://github.com/rohithreddyanugu/VR-Project-1/blob/main/2020-09-27%20(12).png)

### A picture that shows the top view of the room.
This picture shows the top view of the VR Study hall that is created.
![alt text](https://github.com/rohithreddyanugu/VR-Project-1/blob/main/top%20view.png)


### Dynamic moving object change of position.
The change of position of pikachu from one position to the other cab be demonstrated in the picture below.

![alt text](https://github.com/rohithreddyanugu/VR-Project-1/blob/main/2020-10-04%20(5).png)

In the above picture we can see that pikachu is at a position that is close to the blackboard.

![alt text](https://github.com/rohithreddyanugu/VR-Project-1/blob/main/2020-10-04%20(6).png)

In this picture we can see that pikachu is at another position, that is far away from the blackboard.

And this animation for change of position can be obtained by using this piece of code.

     ``` 
      <a-entity geometry="primitive: box" color="blue" rotation="0 0 0" position="1 1.3 -10.5 " scale="3.5 3.5 3.5" obj-model="position:1 1.3 -10.5 ;obj:#pikachuO; mtl:#pikachuM"  class="intersectable" >
      <a-animation begin="click" attribute="position" from="1 1.3 -10.5" to= "1 1.3 -0.5 " dur="3000" direction="alternate" easing="ease-in-out" ></a-animation>   
      <a-animation end="click" attribute="position" from="1 1.3 -0.5" to= "1 1.3 -10.5" dur="3000" direction="alternate" easing="ease-in-out" ></a-animation>   

### **Study room**
:one: Refrigirator   

:two: Drafting table

:three: Blackboard

:four: Projector 

:five: Pikachu

:six: Posters

:seven: Study chairs 

:eight: study table

:nine: Book shelf

:one: : zero: Covid chart

:one: :one: Sanitizer  

:one: :two: Sanitizer table

:one: :three: Door

:one: :four: Fan

:one: :five: books

:one: :six: Lockers

backgorund music: https://www.soundboard.com/sb/Pikachu_Sound


