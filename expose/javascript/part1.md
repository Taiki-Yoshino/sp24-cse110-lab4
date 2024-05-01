1. 20
2. 20
3. 20
4. error: result is not defined. 
   1. Result is defined as let inside the if-block, but line13 calles it from ouside of the scope.
5. TypeError: Assignment to constant variable.
   1. Result is decleared as const, so we can't change the value in line9.
6. The code doesn't reach to this line due to the previous error. 
   1. Even the previous error ignored, result is defined inside the if-block, but line13 calles it from ouside of the block, it will sill cause the error.