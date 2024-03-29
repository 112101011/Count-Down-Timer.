# Count-Down-Timer.
This repository is regarding designing count down timer using python. <br/>

[short presentation on this project](https://www.youtube.com/watch?v=AsolgUy9wUI)

## Problem statement:
Design a count down timer that has following features:
1) Reset
2) Stop
3) Pause
4) Resume <br/>

![thumbnail](https://github.com/112101011/Count-Down-Timer./assets/111628378/4b316e15-53fb-4c25-9e4f-df518d50e297)

## Description of approach:
Here python programming language is used to design this count down timer. Nevertheless any programming language can be used to design this timer with same features. <br/>
Here the working of count down timer can be followed by using the following state diagram: <br/>
![picto](https://github.com/112101011/Count-Down-Timer./assets/111628378/547cc34a-d516-4a64-b900-086207dff30f)

Here the message ‘ERROR’ is given sometimes by the timer when a operation of no-sense at a state is performed. For example: when alarm is stopped there is no sense of pausing the alarm. So here ‘ERROR’ message is displayed but the state remains the same. This is one of the examples of such redundant cases and there are many, that are clearly mentioned in the state diagram. 

## Description of python program:
Here in the python code we can observe that a class object is created to perform this count timer execution. We can see that the ‘ERROR’ cases are handled in every button method in python. <br/>
There are four buttons they are: 
1) reset button
2) stop button
3) pause button
4) resume button.<br/>

And the message is printed every instant whether there is some error  in the sequence of button that can  be inferred from the state diagram. <br/>
The important part of the code is decreasing the time. This code is written in the class method countdown_timer. After every second the seconds left is decremented by one and when seconds left becomes zero the countdown timer stops decrementing.

## tk screen:
![pic](https://github.com/112101011/Count-Down-Timer./assets/111628378/10a14e04-f051-40cd-ac3a-74da8812a0aa)

## Further scope:
Sound can be added to this count down timer. We can add it in two ways. One would be that the sound is 'ON' while the count down timer is decrementing and it sound stops as soon as time left becomes zero. Other would be sound is 'ON' as soon as timer is zero. 
