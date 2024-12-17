### Assuming there are 7.481 gallons in a cubic foot, write a program that asks the user to enter a number of gallons, and then displays the equivalent in cubic feet.

### Write a program that generates the following table:

  1990 135
  1991 7290
  1992 11300
  1993 16200

Use a single cout statement for all output.

### Write a program that generates the following output:

  10
  20
  19

Use an integer constant for the 10, an arithmetic assignment operator to generate the 20,
and a decrement operator to generate the 19.

###  Write a program that displays your favorite poem. Use an appropriate escape sequence
### for the line breaks. If you don’t have a favorite poem, you can borrow this one by Ogden
### Nash:
Candy is dandy,
But liquor is quicker.
C++ Programming Basics


###  On a certain day the British pound was equivalent to $1.487 U.S., the French franc was $0.172, the German deutschemark was $0.584, and the Japanese yen was $0.00955.
### Write a program that allows the user to enter an amount in dollars, and then displays this
### value converted to these four other monetary units.

### You can convert temperature from degrees Celsius to degrees Fahrenheit by multiplying by 9/5 and adding 32. Write a program that allows the user to enter a floating-point number representing degrees Celsius, and then displays the corresponding degrees Fahrenheit.

### If you have two fractions, a/b and c/d, their sum can be obtained from the formula

a c a*d + b*c
--- + --- = -----------
b d b*d
For example, 1/4 plus 2/3 is
1 2 1*3 + 4*2 3 + 8 11
--- + --- = ----------- = ------- = ----
4 3 4*3 12 12

### Write a program that encourages the user to enter two fractions, and then displays their
### sum in fractional form. (You don’t need to reduce it to lowest terms.) The interaction
### with the user might look like this:
   Enter first fraction: 1/2
   Enter second fraction: 2/5
   Sum = 9/10
You can take advantage of the fact that the extraction operator (>>) can be chained to
read in more than one quantity at once:
cin >> a >> dummychar >> b;

### In the heyday of the British empire, Great Britain used a monetary system based on
### pounds, shillings, and pence. There were 20 shillings to a pound, and 12 pence to a
### shilling. The notation for this old system used the pound sign, £, and two decimal points,
### so that, for example, £5.2.8 meant 5 pounds, 2 shillings, and 8 pence. (Pence is the plural
### of penny.) The new monetary system, introduced in the 1950s, consists of only pounds
### and pence, with 100 pence to a pound (like U.S. dollars and cents). We’ll call this new
### system decimal pounds. Thus £5.2.8 in the old notation is £5.13 in decimal pounds (actually £5.1333333). Write a program to convert the old pounds-shillings-pence format to
### decimal pounds. An example of the user’s interaction with the program would be
Enter pounds: 7
Enter shillings: 17
Enter pence: 9
Decimal pounds = £7.89
In most compilers you can use the decimal number 156 (hex character constant ‘\x9c’)
to represent the pound sign (£). In some compilers, you can put the pound sign into your
program directly by pasting it from the Windows Character Map accessory.
