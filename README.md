# Python List Operations

This script demonstrates various Python list operations including:
- Creating an empty list
- Appending items
- Inserting at a specific position
- Extending a list with another list
- Removing the last element
- Sorting in ascending order
- Finding the index of a specific value

## Code Example
```python
my_list = []
my_list.extend([10, 20, 30, 40])
my_list.insert(1, 15)
my_list.extend([50, 60, 70])
my_list.pop()
my_list.sort()
print("Index of 30:", my_list.index(30))
print("Final list:", my_list)
