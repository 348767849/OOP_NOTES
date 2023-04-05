# iterations

terable Objects: Objects that we can iterate through like a sequence.
Examples: Strings & Lists (sets and dictionaries too)
Recall that we could iterate through Strings and Lists
To access individual values without indexing, we were able to use for loops
Note:
The portion of the iterable object must be a sequence
Iterable doesn’t always mean indexable
We won’t be doing “indexable” this year

#itter and next method
__iter__() → 
Allows our object to be iterable, when invoked upon (ex. By a for loop), it will called the method. Commonly just returns it self
__next__() →
Allows us to get to the next value when iterating:
Common Practice: 
set an index attribute to -1
increment the index attribute by 1 until self.__index is equal to length of sequence
when the end is reached, raise StopIteration
