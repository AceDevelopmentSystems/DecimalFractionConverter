# DecimalToFractionConverter
Class to allow conversion from decimal to fraction and vice versa

Ever need a way to represent a decimal into a fraction Convert the number so you can display 1/4 instead of 0.25.
this class allows you to do so

Creates a Fraction object which allows you to extract :

**InitialNumber** - Decimal - the initial number used to create the fraction.

**WholePortions** - Long - value of whole portions of number e.g
              - 100/4 = 25               
              - 5/4   = 1 
              - 3/4   = 0
               
 **Numerator** - Long - The value placed above the horizontal line in a fraction is called a numerator. It signifies the number of parts taken out of the whole.
 
 **Denominator** - Long - The numeric value below the vinculum of a fraction is called the denominator. It represents the total number of equal parts as a whole.
 
 **ImproperNumerator** - Long - Value of the numerator if > 0
 
 **IsNegative** - Boolean - Indicates if the initial decimal is negative or not
 
 **GreatestCommonFactor** - Long - Is the largest factor that all the numbers share.
 
 **RepeatedNumbers** int - number of digits repeated due to division - to allow for limiting answer lengths
 
 

