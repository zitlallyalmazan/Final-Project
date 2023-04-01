## Linked List

Dictionaries in Python are very similar to real-world dictionaries. These are mutable data structures
that contain a collection of keys and, associated with them, values. This structure makes them very 
similar to word-definition dictionaries.

Dictionaries are used to quickly access certain data associated with a unique key. Uniqueness is essential,
as we need to access only certain pieces of information and not confuse it with other entries. We use dictionaries
when we are able to to associate (in technical terms, to map) a unqie key to certain data, and we access
that data very quickly (in constant time, no matter the dictionary size).

# Pros of Dictionaries

* They make code much easier to read if we need to generate key:value pairs. We can also do the same with a list of lists
(where inner lists are pairs of "keys" and "values"), but this looks more complex and confusing.
* We can look up a certain value in a dictionary very quickly. Instead, with a list, we would have to read the lists before
we hit the required element. This difference grows drastically if we increase the number of elements.

# Cons of Dictionaries

* They occupy a lot of space. If we need to handle a large amount of data, this is not the most suitable data structure.
* Compatibility issues. 