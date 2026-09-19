# Count Digits Using C

Explanation
temp % 10: Isolates the rightmost digit.num % digit == 0:
Increments count if the digit cleanly divides the original number.temp /= 10:
Drops the processed digit to move to the next position.
