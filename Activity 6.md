SEND 'Please enter the first number' TO DISPLAY
RECEIVE firstNumber FROM KEYBOARD
SEND TO DISPLAY 'Please enter the second number'
RECEIVE secondNumber FROM KEYBOARD
SEND 'Please enter the third number'
RECEIVE thirdNumber FROM KEYBOARD
SET total TO (firstNumber + secondNumber + thirdNumber)/3
SEND total TO DISPLAY
