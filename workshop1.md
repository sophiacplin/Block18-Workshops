#header

-bullets

# Workshop: Writing Test Specifications

# Unit Test

- expect ([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be [-1, 1, 3, 9, 15].
- when user input letters, they should be shown an error and prompted to enter numbers instead.
- when multiple of the same odd number is entered in the array, only show one of the same number.
- when a calculation is entered, it should recognize the outcome of the calculation and be expected in the result if it is an odd number.

# Functional Test (Shopping Cart)

- when a user is trying to checkout without an account, they should be asked if they would like to sign up, or check out as a guest without an account.
- when a user is trying to checkout and has an account, they should be direct into the first step of the checkout process page.
- If the user is trying to checkout with an empty cart, they should be prompt to keep shopping and put products into cart.
- The checkout process should be, when the user hit 'proceed to checkout', they will enter the checkout process, first-step user will be asked to sign in, second-step will ask the user to join premium member, thrid-step will ask the user to enter shipping information, fourth-step will have the user choose payment method, fifth step will ask the user to enter payment information, sixth-step will have the user review and confirm the order, and the seventh-step which is the last step will show user whether the order has successfully been placed or failed.
- Logged-in users should be able to store shipping information and add delivery instruction.
- An expected delivery date should be shown.
- Users should be able to enter coupons or gift cards at the cart or at the payment page.
- Users should be able to cancel checkout and have the option to keep shopping with original products staying in cart.
- user should be able to see order summary in a small section throughout the checkout process.
