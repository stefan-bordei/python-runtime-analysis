# Runtime analysis done in Python3.



__Algorithms:__

1. __Iterative factorial:__
 - Input: integer
 - initialize factorial variable with 1
 - for numbers in range 2 to input + 1 factorial += number
 - return factorial


2. __Recursive factorial:__
 - Input: integer
 - if input is 0 return 1
 - else return factorial function with $n - 1$ as argument n times


3. __Tail recursive factorial:__
 - Input: integer, accumulator = 1
 - if input is 0 return accumulator
 - else return factorial function with $n - 1$ as argument n times
 
4. __Linear search:__
 - Input: array and element to be found
 - iterate through the array and check if the element exists
 - if found return the index of the element
 

5. __Binary search:__
 - Input: array and element to be found
 - initialize lower and mid to 0 and high to the length of the array
 - as long as low <= high
  - mid = middle of the array
  - if mid < element low becomes mid
  - if mix > element high becomes mid
  - if mid = element return mid
