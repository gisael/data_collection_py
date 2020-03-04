# Lists

## Create a list

The simpliest way to create a list is assigning "[ ]" into a variable. Note that is perfevtly find create an empty list 
as well as a defined lsit.

```python
mylist = ['monday', 'tuesday', 'wednesday']
```

## Access a list

### Specific item
```python
mylist[1]
```
**Output:** 'tuesday'

Note: the first item/position of a list is represented by the number 0. in this case, the position #1 will return the item
in the second position in the list.

### Negative indexing
```python
mylist[-1]
mylist[-2]
```
**Output[1]:** 'wednesday' <br>
**Output[2]:** 'tuesday'

Note: Indexing done backward. Last item is [-1], second last item [-2] and so on.

### Range of data

thislist = ['apple', 'banana', 'cherry', 'orange', 'kiwi', 'melon', 'mango']

```python
mylist[2:5]
mylist[-5:-3] 
mylist[-2:-1] 
mylist[-2:] 
mylist[-1] 
```

**Output[1]:** ['cherry', 'orange', 'kiwi'] <br>
**Output[2]:** ['cherry', 'orange'] <br>
**Output[3]:** ['melon'] <br>
**Output[4]:** ['melon', 'mango'] <br>
**Output[5]:** 'mango' <br>

Note: ranges are inclusive to the left '[' but exclusive to the right ']' mylist[0:3] will return items in postition 0,1,2 but not in 3

## Change an existing value inside a list

```python
mylist = ['apple', 'banana', 'pear']
mylist[1] = 'passion_fruit'
print(mylist)
```

**Output[1]:** ['apple', 'passion_fruit', 'pear']

## Add a new value

```python
mylist.append('nispero')
print(mylist)
```
**Output[1]:** ['apple', 'passion_fruit', 'pear', 'nispero']

## Remove values
### Remove by label

```python
mylist.remove('pear')
print(mylist)
```

**Output[1]:** ['apple', 'passion_fruit', 'nispero']

### Remove by index

```python
mylist.pop()
print(mylist)
```

**Output[1]:** ['apple', 'passion_fruit']

```python
mylist.pop(0)
print(mylist)
```

**Output[1]:** ['passion_fruit']


## Loop through the list


## Check list length


## Copy a list


## Join several list


## Sort list


## Create a multidimensional list


