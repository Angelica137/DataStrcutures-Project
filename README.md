# Data structures

1. Least recently used cache

For our first problem, the goal will be to design a data structure known as a Least Recently Used (LRU) cache. For the current problem, consider both ```get``` and ```set``` operations as an ```use operation```.

Your job is to use an appropriate data structure(s) to implement the cache.

In case of a ```cache hit```, your ```get()``` operation should return the appropriate value.
In case of a ```cache miss```, your ```get()``` should return -1.
While putting an element in the cache, your ```put()``` / ```set()``` operation must insert the element. If the cache is full, you must write code that removes the least recently used entry first and then insert the element.

All operations must take ```O(1)``` time.

For the current problem, you can consider the ```size of cache = 5```.

Use the boiler plate code and example test cases to get you started on this problem.