# Part 1a
1. values added: 20
2. final result: 20
3. values added: 20
4. This will give an error since result is out of scope and is therefore not defined.
5. The code will not run, since assigning a value to a const produces an error. 
6. Same as question 5. 

# Part 1b
1. "3" will be printed. 
2. "150" will be printed.
3. "150" will be printed.
4. The function will return [50,100,150], since it calculates the discounted price for each item in prices and adds them to the discounted array.
5. This will produce an error since i is out of scope when it is logged. 
6. This will produce an error since discountedPrice is out of scope when it is logged. 
7. "150" will be printed.
8. The function will return [50,100,150], since it does exactly the same calculations as in question 4.
9. This will produce an error since i is out of scope when it is logged. 
10. "3" will be printed.
11. The function will return [50,100,150], since it does exactly the same calculations as in question 4. Though discounted is a const, the array is still able to be pushed to. 
12. <br>
  A: student.name  
  B: student['Grad Year']  
  C: student.greeting()  
  D: student['Favorite Teacher'].name  
  E: student.courseLoad[0]  
13.  
  A: The 2 gets converted to the string "2", so the end result is "32"  
  B: The '3' gets converted to the number 3, so the end result is 1  
  C: The null gets converted to 0, so the end result is 3  
  D: The null gets converted to "null", so the end result is "3null"  
  E: The true gets converted to 1, so the end result is 4  
  F: Both false and null get converted to 0, so the result is 0  
  G: undefined gets converted to the string "undefined", so the result is "3undefined"  
  H: undefined gets converted to NaN, so the result is NaN    
14.  
  A: '2' gets converted to the number 2, so 2 > 1 is true.  
  B: '2' is alphabetically higher than '12' since '2' is larger than '1', so '2' < '12' is false.  
  C: '2' will get converted to the number 2, so 2 == '2' is true.  
  D: Strict equality does not allow for type conversion, so 2 === '2' is false.  
  E: true gets converted to the number 1, so true == 2 is false.  
  F: Here 2 is explicitly converted to true, so true === Boolean(2) is true.  
15. == will convert either or both sides to numbers if they are of different types, and will also explicitly say that null is equal to undefined. === does neither of these.  
16. See code file.  
17. modifyArray calls a given function on every element of the input array. In this case doSomething multiplies the input by 2, so the output array will be [2,4,6]  
18. See code file.  
19. 1,4,3,2 (separated by new lines)
