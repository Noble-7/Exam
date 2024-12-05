# Exam
 
12:45PM:

So, the idea here is to make a controller for a 2D rail shooter. My initials are limiting, so I think a good idea is to use the V as a sort of accelerator. The top left and top right parts of the V will be accelerating with a strafe to the left or right, while holding the bottom middle part of the V will slow you down and return you to the middle. The G part, I'm thinking of using each sharp angle as a button to switch between firing types, with the ship shooting automatically. I want to keep it simple, since I really only have two hours to make this. I will start with this for now. 



1:32PM:

TinkerCad design is done, took 2 screenshots of it off, then on, to show that it won't... *explode* if turned on, as TinkerCad does simulate that if you don't put resistors on your ground wires. The code works by reading each value, then I can read the serial output. All I need to do is label the received messages in order to sort them in the code of my game, then I can use them as values to directly modify in game properties like the player's transform or firing states. A serial print is just Serial.println(button1State);, we'd just repeat this line over and over for each one. Or do Serial.print("1: "); followed by another print (NOT PRINTLN, JUST PRINT), in order to sort and label all messages for the game code in Unity or Unreal. Fun! Onto the 3D design.