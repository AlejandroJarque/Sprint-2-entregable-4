In this case, to refactor the program, I created two models:

## Firts Model:
The first contained information about the customers and the selected glasses, 
generating one object representation for the customer and another for the glasses.

## Second Model:
In the second one, things get a little more complicated, because I've represented a model with a glasses object, in which I nest a supplier object to show all its information, 
and then a sales object, which nests a customer object, an employee object, in addition to other data mentioned in the interface

## Tenologies:
- Mongo Compas
- Json Files
