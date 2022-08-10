Bankist app
----------
----------

What is it?
----------

*Bankist app* is a simple simulation of bank user account page.

Now it has 2 hardcoded accounts, where you can do such operations
as transfer money, request loan, close account and see all
these movements and your balance in the UI.

How to log in and look how it works?
----------

**User 1**
user: hk
pin: 1111

**User 2**
user: os
pin: 2222

How to use?
----------

You have to log in to account at first.

+ Transfer money
Enter username of the another account (hk or os) and
the amount smaller than you have on your deposit.
On success you will see this operation as WITHDRAWAL
in the movements area.

+ Request loan
Fill the field with the necessary amount, push the button, 
and your balance will increase on this amount, and you'll see
this operation as DEPOSIT in the movements area.

+ Close account
After filling the fields with the data you will be logged out.

+ What else? 
It is possible to sort the movements on the amount.
After 5 minutes you will be logged out, and the counter displays
in the UI.
You can see your current balance, incoming and outcoming amounts,
interest rate, date and time when you were logged in. 

JS tricks used in this project
----------

*Working with arrays methods:*
sort, slice, reduce, filter, map, split, join.

As an example createUsernames function. It converts 
first and second names of the account owner to username which
contains small first letters of these words. 

*Intl API* were used to display the date and currency.
