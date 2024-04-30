1. values added:  20
2. final result:  20
3. values added:  20
4. The code returns the error 'result is not defined' because the let keyword makes result only able to be accessed within the block it is defined in, so it cannot be accessed outside the block where it is attempted to be printed with console.log on line 13.
5. The code returns the error 'Assignment to constant variable.' because on line 7 we try to assign num1 + num2 to result, but since it was intialized with the const keyword we cannot reassign a value to it.
6.  The code returns the error 'Assignment to constant variable.' because on line 7 we try to assign num1 + num2 to result, but since it was intialized with the const keyword we cannot reassign a value to it. Also, even if the reassignment did not happen it would still be an eror because result cannot be used out of its scope.
