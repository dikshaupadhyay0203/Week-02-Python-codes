# Creating a tuple
my_tuple = (1, 2, 3, 'hello', 3.14)

# Accessing elements
print(my_tuple[0])   # Output: 1
print(my_tuple[3])   # Output: 'hello'

# Slicing
print(my_tuple[1:4])  # Output: (2, 3, 'hello')

# Concatenating tuples
tuple1 = (1, 2, 3)
tuple2 = ('a', 'b', 'c')
concatenated_tuple = tuple1 + tuple2
print(concatenated_tuple)  # Output: (1, 2, 3, 'a', 'b', 'c')

# Tuple unpacking
a, b, c = (4, 5, 6)
print(a, b, c)  # Output: 4 5 6

# Length of a tuple
print(len(my_tuple))  # Output: 5

# Checking membership
print(3 in my_tuple)  # Output: True
print('world' in my_tuple)  # Output: False

# Iterating through a tuple
for item in my_tuple:
    print(item)

# Nested tuples
nested_tuple = ((1, 2), (3, 4), (5, 6))
print(nested_tuple[1][0])  # Output: 3

# Creating a single-element tuple
single_element_tuple = (42,)
print(single_element_tuple)  # Output: (42,)
