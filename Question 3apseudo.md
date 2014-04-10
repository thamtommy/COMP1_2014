#Question 3a
##Pseudo-code

	FUNCTION GetPlayerName
		validName: Boolean
		PlayerName: Variable
		validName <- False
		WHILE NOT validName DO:
			OUTPUT 'Please enter your name: '
			INPUT 'PlayerName'
			IF len(PlayerName) > 0 DO:
				validName <- True
				RETURN PlayerName
			ELSE DO
				OUTPUT 'Please enter a valid name.'
			END IF
		END WHILE
	END FUNCTION