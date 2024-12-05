# Exam
 
12:45PM:

So, the idea here is to make a controller for a 2D rail shooter. My initials are limiting, so I think a good idea is to use the V as a sort of accelerator. The top left and top right parts of the V will be accelerating with a strafe to the left or right, while holding the bottom middle part of the V will slow you down and return you to the middle. The G part, I'm thinking of using each sharp angle as a button to switch between firing types, with the ship shooting automatically. I want to keep it simple, since I really only have two hours to make this. I will start with this for now. 



1:32PM:

TinkerCad design is done, took 2 screenshots of it off, then on, to show that it won't... *explode* if turned on, as TinkerCad does simulate that if you don't put resistors on your ground wires. The code works by reading each value, then I can read the serial output. All I need to do is label the received messages in order to sort them in the code of my game, then I can use them as values to directly modify in game properties like the player's transform or firing states. A serial print is just Serial.println(button1State);, we'd just repeat this line over and over for each one. Or do Serial.print("1: "); followed by another print (NOT PRINTLN, JUST PRINT), in order to sort and label all messages for the game code in Unity or Unreal. Fun! Onto the 3D design.

2:09PM:

Update! The 3D model looks a little weird, but hear me out: The arcade stick is meant to move through the opening made by the V shape. It will essentially work like 2 potentiometer, deciding your acceleration forwards and to the left or right, depending on which half of the V you are moving up or down. The breadboard would probably be attached to two huge sliders, the notch being replaced with a joystick. Then, we have 4 basic buttons, all of which are controlled by the Arduino we have propped at the front of the controller. The shell would probably be bigger than a NES controller. Think the NES... advantage? I can't look it up because we don't have access to the internet but I remember the NES had two good versions of it, one with a circle pad and two grips and another that was just a square with a big 'ol arcade stick. I think the NES advantage was the circle pad one, but for the life of me I can't remember the one with the arcade stick. I'm sure you know which I'm talking about. In any case, the rendering of the 3D shape takes a worryingly long amount of time, so I'll leave myself 20 minutes to upload everything in the hopes that it'll be enough time. Onwards with stuff like the exploded view and bill of materials and drawings and... all that.