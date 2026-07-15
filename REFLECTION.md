# Reflection – Daily Schedule Simulator

## What was your approach to designing the schedule?
I chose my activities based on my typical weekday. I considered what I was doing, and implemented it into the program.

## What was one challenge or unexpected behavior you encountered?
One unexpected behavior I encountered was with my random feature. I intended for there to be a 50% chance of the schedule saying I'm playing piano or cello, but with every test I was continuosly receiving the output of "playing cello". I eventually figured out that this was because I was repeatedly declaring the variable inside of the set interval, therefore it was deleting the value of the variable each time the callback function ran. 

## What does this assignment teach you about async code?
If this was a regular script that ran without delays, the page would stay fixed, while using async code, it is possible for things to gradually change over time. 

## What creative element did you add?
I added both a clock and a randomization element. 

## How does this project simulate or differ from real-world schedules?
This simulation moves at the same pace as real life, however every day repeates with an extremely similar schedule. Often in the real world, there is a lot more unpredictability, in comparison to my simulation. 
  