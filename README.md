1. What is the Big O for this?
  1) Constant 
  2) Linear 

2. Constant - Regardless of the size of the value you put in, the function just divides it by
    zero and checks if there is a remainder. It's two steps no matter what.
    
3. Polynomial - there are two levels of looping. levels = polynomial

4. Linear - since the function is looping through the array and doubling each value, 
    the runtime will be directly proportional to how many values there are in the array
    
5. Linear - loop is checking each value to see if it matches the item. more values = longer loop

6. Polynomial - two levels of looping. levels = polynomial

7. The algorithm is computing the Fibonacci numbers up to the number given (num = 10, returns
    first 10 numbers of Fibonacci sequence). The Big O is exponential, because for each loop
    of the array, the function has to check the past 2 numbers in the results.
    
8. Logarithmic - it looks like the algorithm cuts down on runtime by sorting the array to find
  the item
  
9. Constant - input size doesn't matter, the function just finds a random element and that index

10. The algorithm checks if n is a prime number. I think it's linear because the function will
    always do the first two steps (check if n < 2 or n/1 does not have a remainder) and then 
    the runtime of the for loop just depends on how big n is

