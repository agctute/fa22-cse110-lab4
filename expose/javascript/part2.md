# Part 2
## Question 1:
The code returns 3 because that is the last value that ```i``` is assigned (and also because the log function remains in function).

## Question 2:
The code returns 150 for the same reasons stated in Question 1, but with ```discountedPrice``` instead of ```i```.

## Question 3:
The code returns 150 for the same reasons stated in Question 1, but with ```finalPrice``` instead of ```i```.

## Question 4:
The function returns [50, 100, 150] since ```discounted``` is defined in the scope of the function.

## Question 5:
The code returns an error since ```i``` is only defined in the scope of the ```for``` loop

## Question 6:
The code returns an error since ```discountedPrice``` is only defined in the scope of the ```for``` loop

## Question 7:
The code will return 150 since ```finalPrice``` is still defined in the scope of the function even with the use of ```let```

## Question 8:
The function will return [50, 100, 150] since, the ```discounted``` is in the scope of the function and hence values can be pushed to it and it can be returned. 

## Question 9:
The code returns an error since ```i``` is only defined in the scope of the ```for``` loop

## Question 10:
The code prints 3 since ```length``` is defined within the same scope as the log and is never changed. 

## Question 11:
the function returns [50, 100, 150] since the ```const``` declaration only defines the reference to the ```discounted``` array as immutable, but the array itself can still be changed. 

## Question 12:
### A:
```student.name```

### B:
```student['Grad Year']```

### C:
```student.greeting()```

### D:
```student['Favorite Teacher'].name```

### E:
```student.courseload[0]```

## Question 13:
### A:
'32' since first datatype is String and '+' is used, signaling a string concat

### B:
1 since '-' is used

### C:
3 since first datatype is Number

### D:
'3null' since first datatype is String and '+' is used

### E:
4 since first datatype is not string and '+' is used

### F:
0, because js is fucked

### G:
'3undefined' since it is concatenating strings

### H:
NaN, since Number(undefined) is NaN, and a numerical operation is used

## 14:
### A:
true since 2 > 1 when both are converted to Numbers

### B:
false since neither are Numbers

### C:
true since the equivalence is not strict on datatype

### D:
false since the equivalence is strict on datatype

### E:
false since true corresponds to 1 when translated into a Number

### F:
true since 2 as a Boolean translates to true

## 15:
```==``` refers to equivalences that are not strict in typing, meaning that two datatypes can be compared, while ```===``` does not allow this, and requires both values to be the same type to return true

## 16:
See relevant js file

## 17:
the call to ```modifyArray``` will return [2, 4, 6] since for each value in the input array, it is used as an input to the ```callback``` function whose result is pushed into the returned array. 

## 18:
see relevant JS file

## 19:
1

3

4

2


