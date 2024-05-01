1. 3
   1. discountPrices funtion takes three elemnts of array as input, so it executes the line6 for loop three times. After that i hold 3, and print out it in line12.
2. 150
   1. Line13 output the discountedPrince in the final for loop(line6-10). prices[i] = 300 and discount is 0.5, so the discountedPrice = 150.
3. 150
   1. Line14 output the finalPrice in the final for-loop(line6-10). discountedPrice = 150, so finalPrice became also 150.
4. [50,100,150]
   1. The function calculate and return half of each elements of array. The input array is [100,200,300], so it returns [50,100,150].
5. ReferenceError: i is not defined
   1. i is defined as let inside the for-loop, but it is called outside of the scope.
6. ReferenceError: discountedPrice is not defined
   1. discountedPrice is defined inside the for-block(line6-10), but line12 calls it from outside the block.
7. 150
   1. Line14 outputs the finalPrice in the final for-loop(line6-10). discountedPrice = 150, so finalPrice became also 150.
8. [50,100,150]
   1. The same reason for Q4.
9. ReferenceError: i is not defined.
   1.  i is defined as let inside the for-loop block(line6-9), but line 11 calls it outside the block.
10. 3
    1.  length is the number of elements of input array. The function takes [100,200,300], so the length become 3.
11. [50,100,150]
    1.  The same reason for Q4.
12.  
     1.   A: student.name;
     2.   B: student['Grad Year'];
     3.   C: student.greeting();
     4.   D: student['Favorite Teacher'].name;
     5.   E: student.courseLoad[0];
13.  
     1.   A: '32'
          1. The number 2 is converted to the string '2', resulting in the concatenation '3' + '2' which produces '32'.
     2.   B: 1
          1. The - operator doesn't concatenate. It converts the string '3' into a number and performs arithmetic subtraction, hence '3' - 2 becomes 3 - 2 which is 1.  
     3.   C: 3
          1. null is treated as 0, so 3 + null becomes 3 + 0, which is 3.
     4.   D: '3null'
          1. null is converted to the string 'null', and '3' + 'null' results in '3null'
     5.   E: 4
          1. true is converted to 1, so true + 3 is 1 + 3, which equals 4.   
     6.   F: 0
          1.  Both false and null are treated as 0. Therefore, false + null is 0 + 0, which is 0
     7.   G: '3undefined'
          1.  undefined is converted to the string 'undefined', so '3' + 'undefined' results in '3undefined'.
     8.   H: NaN
          1.   undefined cannot be converted into a number, '3' - undefined results in NaN.
14.  
     1.   A: true
          1.   '2' becomes 2, and since 2 is greater than 1, the result is true.
     2.   B: false
          1.   '2' comes after '1' in lexicographical order, '2' is considered greater than '12'.
     3.   C: true
          1.   Both operands are converted to numbers, so the comparison becomes 2 == 2, which is true.
     4.   D: false
          1.   one operand is a number and the other is a string, they are not strictly equal.
     5.   E: false
          1.   true is converted to 1, not 2. Thus, true == 2 evaluates to 1 == 2, which is false.
     6.   F: true
          1.   both sides are true and of the same type (boolean), the comparison with === is true
15.  The == operator in JavaScript checks for value equality and performs type coercion if the operands differ in type, allowing for a more lenient comparison. In contrast, the === operator checks for both value and type equality, requiring exact matches without performing type conversion.
16.  redCars: 21, blueCars: 45, raceCars: 5, rareCars: 2, part2-question16.js
17.  [ 2, 4, 6 ]
     1.   The modifyArray function takes an array and a callback function, iterating over each array element and applying the callback to produce a new array of results. doSomething callback function doubles each number, resulting in the array [2, 4, 6]. 
18.  part2-question18.js
19.  1 4 3 2