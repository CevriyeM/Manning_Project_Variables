When two variables are set to the same value, 

for immutable objects(integer, float, string, tuple data types) 
if the value of a variable changes, it does not effect the value of the other variable.

for mutable objects (lists and dictionaries),
if the value of a variable changes, the value of the other variable also changes. 



For immutable objects when the value of a variable changes, the ID of that variable also changes.

For mutable objects (lists and dictionaries), even if the value changes the ID does not change.
So when two mutable objects are set to the same value, they share the same ID. 
When a change is made to one of the variables, since the variables share the same ID, the other variable also changes.  

