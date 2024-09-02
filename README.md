# Built in DSA in python

Python offers several built-in data structures, each serving a specific purpose and optimized for different types of operations.

 Dictionaries  are a versatile data structure that allows for the storage of key-value pairs. They provide an efficient way to retrieve values when the corresponding key is known, making them ideal for scenarios where quick lookups are required. Keys in dictionaries are unique and can be of various data types, while the values can be any object. This flexibility makes dictionaries highly useful for mapping relationships and storing associative arrays.

**Lists** in Python are dynamic arrays that can hold elements of any data type. They are ordered, meaning that the elements are stored in a specific sequence and can be accessed using their index. Lists are mutable, allowing elements to be added, removed, or modified in place. They are widely used for managing collections of items, where order matters, and where the ability to change the content is required. Lists are commonly used for tasks like storing sequences of data, such as items in a shopping cart or elements in a queue.

**Sets** are an unordered collection of unique elements. They are particularly useful for operations that involve membership tests, such as determining if an item is present in a collection. Sets are also used to perform mathematical operations like union, intersection, and difference. Because sets do not maintain any particular order and do not allow duplicate elements, they are ideal for managing collections where each element must be distinct and where order is irrelevant.

**Tuples** are similar to lists but are immutable, meaning their elements cannot be changed once assigned. Tuples are typically used to represent fixed collections of items, such as coordinates or records, where the integrity of the data should remain constant. Their immutability makes tuples hashable, allowing them to be used as keys in dictionaries or as elements in sets, which is not possible with lists.
