### Lists
python
# List creation
fruits = ["apple", "banana", "orange"]
numbers = [1, 2, 3, 4, 5]
mixed = [1, "hello", 3.14, True]

# List methods
fruits.append("grape")       # Add to end
fruits.insert(1, "mango")   # Insert at index
fruits.remove("banana")     # Remove first occurrence
popped = fruits.pop()       # Remove and return last item
fruits.sort()               # Sort in place
fruits.reverse()            # Reverse in place

# List comprehensions
squares = [x**2 for x in range(10)]
evens = [x for x in range(20) if x % 2 == 0]
