# proportion_math
This is a python lib that helps with proportion math (ex: x/100 = 20/400)


after downloading the project one can use it on a personal project by using:

from ProportionMath.Proportions import Proportion

__________________________________________________________________________

Once the project has been imported to the file desired to be used on,
all the developer has to do is the following 

1) declare the class object:

prop = Proportion()

2) plug in your variable and numeric values

x = prop.Proportion('x', 20, 30, 100)

3) This proportion class will handle the rest

____________________________________________________________________________

Some things to be aware of!

1) instead of raising an exception for division by 0, this project will, instead
   return a 0. This ensures your program won't break for entering bad data. 

2) Adding more than one alphabetic string character to the arguments of the method
   will result in an exception raised. As this would prevent the ability to
   solve for 'x'

3) When it comes to alphabetic string characters 'X' or 'x' are the only legal characters
   anything else will raise an exception.
