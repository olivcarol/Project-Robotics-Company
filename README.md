# Project: Robotics Company
<img width="776" alt="Screen Shot 2021-05-26 at 2 12 29 AM" src="https://user-images.githubusercontent.com/80420919/119605888-ec910280-bdc7-11eb-84e9-ee1a21beaa83.png">

Project proposed by Codecademy (course "Learn Python 3) - studying classes and methods

Scope:
"You have decided to use your programming knowledge to create a new robotics company.
Your idea for micro driving robots which are able to pick up and deliver objects was promising and now you want to start programming the logic.
These code challenges will use your knowledge of Classes to solve some example scenarios. Try solving the five challenge problems below!"

1 - Create a python class called DriveBot.
    Within this class, create instance variables for motor_speed, sensor_range, and direction.
    All of these should be initialized to 0 by default. After setting up the class, create an object from the class called robot_1.
    Set the motor_speed to 5, the direction to 90, and the sensor_range to 10.
    
2 - In the DriveBot class, add a method called control_bot which accepts parameters: new_speed and new_direction.
    These should replace the associated instance variables.
    Create another method called adjust_sensor which accepts a parameter called new_sensor_range which replaces the sensor_range instance variable.
    Afterwards, use these methods to rotate the robot 180 degrees at 10 miles per hour with a sensor range of 20 feet.
    
3 - Upgrade the constructor in the DriveBot class in order to accept three optional parameters.
    The constructor can accept motor_speed (which defaults to 0 if not provided), direction (which defaults to 180 if not provided, and sensor_range (which defaults to 10 if not provided).
    These parameters should replace the associated instance variables.
    Test out the upgraded constructor by initializing a new robot called robot_2 with a speed of 35, a direction of 75, and a sensor range of 25.
    
4 - Create a class variable called all_disabled which is set to False.
    Next, create two more class variables called latitude and longitude. Set both of those variables to equal -999999.
    A third robot has been created below the first two robots. Set the latitude of all of the robots to -50.0 at once.
    Additionally, set the longitude of the robots to 50.0 and set all_disabled to True.

5 - Within the DriveBot class, create an instance variable called id which will be assigned to the robot when the object is created.
    Every time a robot is created, increment a counter (stored as a class variable) so that the next robot will have a different id.
