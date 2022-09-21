Start
mystnumber = 3
SEND 'Please enter the first number' TO DISPLAY
RECEVIVE number FROM KEYBOARD SEND 
IF guess > 10 THEN
SEND 'Too high! Your guess must be between 1 and 10' TO DISPLAY
ELSE 
IF guess = mystnumber THEN
SEND 'Lucky Guess' TO DISPLAY
ELSE 
SEND 'Unlucky Guess.. The correct number is + mystnumber' TO DISPLAY
END IF
END IF
END IF
