## Arrays in Python

* There aren't built-in arrays for Python, so just use a list.  

ExampleArray = ["This", "is", "an", "array"]  

Can store huge numbers of values, and you can access values via the index number.  
# I want "This" string value from array
y = ExampleArray[0]
print(y)

# You can also modify the value at that index value
ExampleArray[0] = "A List"
print(y)

Get the length of an array
y = len(ExampleArray)

Looping through an array:
for _ in ExampleArray:
	print(_)

Adding elements to a list:
* This would then be at index[4]
ExampleArray.append("Ta-Dah")

Removing an element from an array:
ExampleArray.pop(1)

BUT....
you can also use .remove() to remove the first matching value within the list. 
This begins at index[0]  


"""
for i in range(len(LIST)):

do your operations on the value at the index element...
ex: blah = sum(someList[i])

"""



append()	Adds an element at the end of the list
clear()	Removes all the elements from the list
copy()	Returns a copy of the list
count()	Returns the number of elements with the specified value
extend()	Add the elements of a list (or any iterable), to the end of the current list
index()	Returns the index of the first element with the specified value
insert()	Adds an element at the specified position
pop()	Removes the element at the specified position
remove()	Removes the first item with the specified value
reverse()	Reverses the order of the list
sort()	Sorts the list



// TODO Do all of this in Markdown you fool
