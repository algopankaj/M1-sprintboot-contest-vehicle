# M1-sprintboot-contest-vehicle

Vehicles

The following project contains two subtasks:

Subtask 1: You are given the classes Vehicle, Car, and F1. Complete the driver code of each of these classes.
Subtask 2: You are given the interface WaterVehicle. Construct a new class Boat (with exactly the same and member variables as given below).
The details of the classes that constitute the project are:

Vehicle: name, currentSpeed, currentDirection

i. constructor: given the name of the vehicle, initialize speed and direction as 0.
ii.move(speed, direction): set the current speed and direction
iii.steer(direction): Add direction to the currentDirection
iv.stop(): Stop the car by setting current speed to 0

Car: extends Vehicle

i.constructor: initialize the variables using parameters and set currentGear as 1.
ii.changeGear(newGear): set the current gear to newGear parameter.
iii.changeSpeed(newSpeed, newDirection): set the speed and direction using move().

F1: extends Car

i.accelerate(rate): add rate to the current speed and change the gear accordingly
ii.Boat: implements WaterVehicle interface

Has following member variables: a. name : of String type b. capacity : of int type
Return name and capacity in getVehicleName and getVehicleCapacity respectively.
Note:

Make sure that the class names are exactly the same.
