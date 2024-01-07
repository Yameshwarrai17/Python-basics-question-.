"""". Write a program that asks the user to enter the width and length of a room. Once these values have
been read, your program should compute and display the area of the room. The length and the width
will be entered as floating-point numbers. Include units in your prompt and output message; either
feet or meters, depending on which unit you are more comfortable working with."""

unit_preference = input("Enter the unit preference");
width = float(input("Enter the width :"));
Height = float(input("Enter the Height :"));
area = width * Height;
print(f"The area is {area} square {unit_preference}");


"""An online retailer sells two products: widgets and gizmos. Each widget weighs 75 grams. Each gizmo
weighs 112 grams. Write a program that reads the number of widgets and the number of gizmos from
the user. Then your program should compute and display the total weight of the parts"""



widget = int(input("Enter the no. of widgets:"));
gizmo = int(input("Enter the no. of gizmos:"));
widget_weight = 75;
gizmo_weight = 112;
total_weight = widget * widget_weight + gizmo * gizmo_weight;
print(f"the total weight is {total_weight} grams");

# Write a program that determines how quickly an object is travelling when it hits the ground. The user will enter the height from which the object is dropped in meters (m). Because the object is droppedits initial speed is 0 m/s. Assume that the acceleration due to gravity is 9.8m/s2. You can use theformula vf=p(v 2i + 2ad) to compute the final speed, vf , when the initial speed, vi, acceleration, a,and distance, d, are known.


import math
float_Height = float(input("Enter the height from the ground"));
Initial_velocity = 0;
acceleration = 9.8;
final_speed = math.sqrt(Initial_velocity**2 + 2*acceleration*float_Height);
print(f"the final speed of the ball is{final_speed}");



""""Write a program that reads a four-digit integer from the user and displays the sum of its digits. For
example, if the user enters 3141 then your program should display 3 + 1 + 4 + 1 = 9."""


Number = int(input("Enter the number:"));
thousands = Number // 1000;
hundereds = Number % 1000 // 100;
tens = Number % 100 // 10 ;
units = Number % 10;
print(f"The sum of the digit is {thousands + hundereds + tens + units}");


"""". Write a program that reads three integers from the user and displays them in sorted order (from
smallest to largest). Use the min and max functions to find the smallest and largest values."""

Number1 = int(input("Enter the number:"));
Number2 = int(input("Enter the number2:"));
Number3 = int(input("Enter the number3:"));

min = min(Number1,Number2,Number3);
max = max(Number1,Number2,Number3);

mid_number = (Number1 + Number2 + Number3) - min - max;
print(f"The number is in ascending order {min} {mid_number} {max}");


""""Create a program that reads duration from the user as a number of days, hours, minutes, and seconds.
Compute and display the total number of seconds represented by this duration."""


no_of_days = int(input("Enter the no. of days:"));
no_of_hrs = int(input("Enter the no.of hrs:"));
no_of_min = int(input("Enter the no.of min:"));
no_of_sec = int(input("Enter the no.of sec:"));
total_sec = no_of_days*24*60*60 + no_of_hrs*60*60 + no_of_min*60 + no_of_sec;
print(f"The total no.of sec is {total_sec}");


