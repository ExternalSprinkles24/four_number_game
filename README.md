# four_number_game
The 'four number game' has been solved in this file!
By External_Sprinkles24.
This file contains every 4 digit number from (and including) 0000 up to (and including) 9999.
However each number has been manipulated via the following rules: 

::DISCLAIMER::
The rules of this game are heavily argued. These rules are my rules that I have chosen in order for the completed list to exist.
::END DISCLAIMER::

	(1) All 4 numbers must be used in one computation (we must only have one equals (=) sign).
		eg: for the number 1 2 4 0, we CANNOT say - 1 - 2 + 4 = 1, 1 concatenate 0 = 10.
    
	(2) All 4 numbers must be used in the order in which they are presented. 
		eg: for the number 2 1 1 4 we CANNOT say 2 * 4 + 1 + 1 = 10
      
	(3) Concatenation is allowed.
		eg: for the number 7 1 7 1 we can concatinate the 1 and 7 to get, (-7 + 17) / 1
    
	(4) We are ONLY allowed to use the following mathematical operations to the 4 numbers	
		+ (add)
		- (subtract)
		* (multiply)
		/ (divide) 
		( (open brackets)
    	) (close brackets)
		^ (exponent)
		! (factorial)
		. (Decimal point. We must allow the omittion of the 0 when dealing with -1 < decimals < 1)
		% (percentage)
		n-th root (We are allowed to use short hand notation for square roots. However if we wish to take the n-th root n > 2, then n must be available in the four digit number to use)
			the notation for roots in this document is root(n, m) --> the n-th root of m.
      
	(5)The result must equal 10.

These rules were chosen in order to solve all 10,000 four digit numbers. 
For example, I cannot find a way to do the number 6768 without the % sign.
I can also not find a way to do 0000 without the sqrt() sign while being allowed to omit the 2 from the sqrt.
