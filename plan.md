3n+1 (collatz conjecture)

<input type="number">

Make sure to check that user enters an integer, cannot be a float or string.

If number is even, divide by 2

If number is odd, multiply by 3 and add 1

Stop the calculation when  i== 1 (with the exception of starting with 1 [should be okay if I put the i==1 after the other conditionals])

I also need a variable (n) that counts the number of hops in the graph

A system that can graph the whole thing
-might make it easier if I make a table of values as the system goes (x = hops, y = values)
-chart.js looks good (w3schools has good documentation on it)
-maybe it would be a good idea to make a multiple line graph that adds the user's inputs together and changes the x-y axes based on the biggest graph. This way they can try to make the longest collatz and compare to previous attempts



While i != 1 
Or 
While i > 1 may be better



function isEven(number) {
  return number % 2 === 0;
}

// Example usage:
console.log(isEven(4));  // Output: true
console.log(isEven(7));  // Output: false
