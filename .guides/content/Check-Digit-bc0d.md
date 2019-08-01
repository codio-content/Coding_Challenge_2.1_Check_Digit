## Check Digits Explained
Take a look at the back cover of a book and you will probably see a 10 digit ISBN-10 number. It may look something like this:

![barcode](/images/barcode.png)

The ISBN-10 number is clearly marked across the top of the barcode. Don't get it mixed up with the ISBN-13 number which is also shown. The last digit is the **check digit**. An algorithm can be applied to the other nine numbers and the output should be the same as the check digit.

Check digits are used to ensure that data is entered correctly. For example, someone may need to manually input the numbers on the barcode in a shop. The check digit provides a mechanism to ensure that the other numbers were error free.

## How to calculate a check digit
Grab a pen and paper and follow the instructions below.

Here are the first 9 digits for an ISBN number **147186614**

**Step 1**
Multiple the first number by 1, the second by 2, the third by 3 and so on.

**Step 2**
Add all the totals together from Step 1 and record

**Step 3**
Divide the total from Step 2 by 11 and record the remainder

**Step 4**
The remainder is the check digit. In this case it should be **9**.

**Step 5**
Now try with some other ISBN numbers. Use Amazon's book section for valid ISBNs.


## Task
Write a program to calculate the check digit for any ISBN.

 - Allow a user to enter the first 9 digits of a valid ISBN number ignoring spaces and hyphens.
 - Output the check digit
 - If the remainder is 0 then the check digit is 0
 - If the remainder is 10 then the check digit is X
 
