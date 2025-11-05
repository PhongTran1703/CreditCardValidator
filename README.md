# CreditCardValidator

Using Luhn Algorithm to verify the credit card number

1. Double every second digit from right to left, if doubled number is 2 digits, split them.
2. Add all single digits from step 1.
3. Add all odd numbered digits from right to left
4. Sum result from steps 2 & 3
5. If step 4 is divisible by 10, credit card number is valid.

 
