#>> INTEGERS AND FLOATS

###Words are great and all, but what about numbers?

Ruby breaks its number system down into two types:
**integers** and **floats**

Simply stated:   
An *integer* is any number that does not have a decimal point.

 *   `10 `

 *   `3 `

 *  `894208304 `

A *float* is any number with a decimal point.

*  `2.3 `

*  `42095.90 `

*  `0.000002930 `

This is actually a really important distinction, especially when it comes to doing any sort of math in Ruby.

##Ruby Math
A few important operations to know (and love):

*  `+ ` **addition**

		3+4
		>> 7

*  `- ` **subtraction**

		3-4
		>> -1


*  `* ` **multiplication**

		3*4
		>> 12

*  `/ ` **division**

		5/3
		>> 1
Division with integers will only yield integers. Therefore, when we divide 5/3, Ruby rounds down to the nearest whole number.

		5.0/3.0
		>> 1.666666666667
Division with floats will yield floats. Putting a `.0` on the end of both of our numbers makes them floats, which makes our answer much more exactly.

*  `% ` **modulo**

		5%3
		>> 2
Modulo calculates the remainder left over after dividing two integers or floats.

*  `** ` **to the power of**

		3**2
		>> 9 
