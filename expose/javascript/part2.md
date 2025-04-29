1) The code outputs "3" because we defined i with var, which makes it accessible outside the scope of the for-loop.
2) The code outputs "150" because at the time that "i" escapes the for-loop, it is taking the discounted price of the last value in the prices array, 300, and half of this is 150.
3) The code outputs "150" because finalPrice is the rounded version of the intiial discountedPrice. In this case, the variable in discountedPrice variable contains "150" and isn't changed after the finalPrice variable does its operations, leaving it 150.
4) This function will return the final array of prices after applying the discount to each of the prices.
5) This function will error because we used "let" to define "i" which isn't recognized by the console.log at line 12.
6) This code will error because we used "let" to define "discountedPrice" within the for-loop so it will be be recognized by line 13.
7) The code will return "150" This is becuase we used "let" to define "finalPrice" within the entire function which is recognzied at line 14.
8) This function will return the discounted prices after applying the discount to each of the intial prices.
9) This function will return an error because we used "let" to define "i" and it will be be recognized at line 11.
10) This function will return "3" because we used "const" to define "length" which will be recognized at line 12.
11) This function will return the final array of prices after applying the discount to each of the prices. We use const to define all variables and redefine "discountedPrice" every array so the value changing won't cause this program to error.
12)
- a. student.name
- b. student.['Grad Year']
- c. student.greeting()
- d. student.['Favorite Teacher'].name
- e. student.courseLoad[0]

13) 
- a. 32, 2 maps to its string version
- b. 1, 3 maps to its int version
- c. 3, null maps to 0
- d. 3null, null maps to its string version
- e. 4, true maps to 1
- f. 0, false maps to 0 and null maps to 0
- g. 3undefined, undefined maps to its string version
- h. NaN, Can't subtract a string that doesn't have a value

14) 
- a. true, 2 is mapped to its integer value
- b. false, lexographically '2' is larger than '12'
- c. true, 2 is mapped to its integer value
- d. false, false because '===' checks for type and value equality
- e. false, true is mapped to 1
- f. true, boolean is mapped to 1 because its value is not null and true is mapped to 1. Both are the same type and value.

15) '===' checks for equivalent type and value while '==' only checks for value equivalency

16) in part2-question16.js

17) modidyArray calls doSomething on every item in the input array. modifyArray creates a new array and for every element in the input array, calls the doSomething function on it and then pushes the new value to the new Array. 

18) in part2-question18.js

19) The output is 1\n4\n3\n2. This is because we first print 1, we then schedule timeouts for to print 2 a second later and print 3 immediately. We then print 2 after the timeout expires.