Think about the following; you may need to make assumptions or decisions about the prompt and how the code should behave:
What should happen with unexpected inputs?
What kinds of unexpected inputs should we worry about?
What should happen when there are multiples of the same odd number in the arrays? (Hint: We gave you the answer to this one in the example above.)

Unit Tests:
A function called "multiplication" that returns the product of the two input numbers.
--Expect multiplication(5,9) to be a number.
--Expect multiplication(5,9) to be equal to 45.
--Expect multiplication('c', 9) to be an error.
--Expect multiplication(3, 'p') to be an error. 
  
  
A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.
Example: concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1])
...should result in [-1, 1, 3, 9, 15]
--Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be [-1, 1, 3, 9, 15].
--Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be integers only.
--Expect concatOdds([3, b, 1], [9, 1, a, 1, 4, 15, -1]) to be an error. 
--Expect concatOdds([3, 2.5, 1], [9, 1, 7.3, 1, 4, 15, -1]) to be an error.

Functional Tests:
A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.
Think about the following; you may need to make assumptions or decisions about the prompt and how the feature should behave:
What should happen if the cart is empty?
What needs to be shown to the user at each step of check out?
What behaviors of this feature does the prompt miss or gloss over?
Hint: Observe the shopping cart and checkout features of some popular websites to get some ideas!
  When a user clicks the cart icon and their cart is empty, they should be shown a message that says the cart is empty with a link to continue shopping.
  When a user clicks "checkout" with at least one item in their cart, they should be taken to a login page with options to log in, create an account, or check out as a guest.
  
  
