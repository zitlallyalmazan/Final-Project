## Lists

Lists are useful when we want to store a collection of different data types
and subsequently add, remove, or perform operations on each elemnt of the list(by 
looping through them).

Lists are useful to store other adata structures ( and even more lists) by creating,
for instance, lists of dictionaries, tuples, or lists. It is very common to store a table
as a list of lists (where each inner list represents a table's column) for subsequent
data analysis.

# Pros of Lists

* They represent the easiest way to store a collection of related objects.
* They are easy to modify by removing, adding, and changing elements.
* They are useful for creating nested data structures, such as a list of lists/dictionaries.

# Cons of Lists

* They can be pretty slow when performing arithmetic operations on their elements.
* They use more disk space because of their under-the-hood implemntation.

# Problem to solve

The linked list is a usefule data structure providing similar functionality to an array, but
in a dynamic package. Similar to BST, values in a linked list are wrapped in an instance of a 
'node' class containing a pointer, allowing the whole list to be linked together by distributed
references.