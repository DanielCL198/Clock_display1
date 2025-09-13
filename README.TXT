Project: clock-display
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class ClockDisplay. Then inspect this 
instance and leave the object inspector window open. With the inspector window open, 
call the object's methods, such as timeTick and setTime. Watch the 
"displayString" in the inspector.

The displayString field simulates the actual clock display device. Were this 
program running in a real clock, it would change the real, physical display 
hardware instead of this string. The timeTick method would be triggered once 
every minute by some timer hardware.

Everything else could be pretty much the same.


Note: This project does not implement adequate handling of errors.


**ANSWERS**

22. It starts at that time because the clock was programmed to start at 00:00 when an object is made of it.

23. clicking te timetick method 60 times would make it show 1:00, but an easier way to show that time is to call the setTime method and set it to hour=1 and minute=0, this would display 1:00

24. private NumberDisplay digit

25. private Rectangle window

26. This gives a rollover amount to both hours and minutes allows the person to enter and give a starting value to these hours and minutes by putting int hour and int minute by adding the setTime method

27. The second one has two parameters whereas the first one has none, ad the second one has a call for setTime with two parameters whereas the first one has a call for updatedisplay with 0 parameters. The first constructor is made to create a new clock set at 00:00 but the second constructor is made to create a new clock that displays with the time specified in the parameters.

28. 
return print();
updateStatus();

29. two squares, one triangle, and one circle

30. changeSize, moveHorizontal, moveVertical, makeVisible

32. 2

33. it does the same calculation but gives an answer 0 or less

34. whatever number n is, the answer will be that! as long as you dont surpass 5, if you do, then it will restart the scale from 1 to 5 meaning that 6%5 will give 1 and 7%5 will give 2.

37. Option one is much easier because all you have to do is change the 24 in both clock constructors to 12 and your maximum will then be 12!

