#Question 3a
##Pseudo-code

	FUNCTION GetPlayerName
		validName: Boolean
		PlayerName: Variable
		OUTPUT 'Please enter your name: '
		INPUT 'PlayerName'
		validName <- False
		WHILE NOT validName DO:
			IF len(PlayerName) > 0 DO:
				validName <- True
				RETURN PlayerName
			ELSE DO
				OUTPUT 'Please enter a valid name.'
			END IF
		END WHILE
	END FUNCTION