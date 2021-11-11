# Building a Simple Class

## Create a Car Class

1. Start by defining a class named Car.
2. Insert class documentation that describes this class - see Canvas page: "Multiple Files and Module Documentation"
3. Next define the constructor method. Remeber that this belongs to the class, so it should be indented from the class definition line. This class has three instance variables for make, model, and year. Include the parameters make, model and year in the constructor definition.

> > Within the constructor define instance the variables. We want these to be "private" so use a leading underscore in the name. Use the constructor parameters to assign values to the instance variables.
> - _make
> - _model
> - _year

4. Continue with the class definition by defining the following six methods.

> - set_make(self,make)
> - set_model(self,model)
> - set_year(self,year)
> - get_make(self)
> - get_model(self)
> - get_year(self)

At this point the class definition is complete. Continue by writing test code that will test all the methods defined in the class.

5. Create a TestCar() function that

> - creates a car
> - prints the car's properties using the get methods
> - updates the car's properties using the set methods and then prints them out to demonstrate that the set methods worked.
> - add comments above each line of code to indicate what you think the following code is testing.

6. Use conditional execution ("if \_\_name__ == "\_\_main__":) to call the TestCar function.
