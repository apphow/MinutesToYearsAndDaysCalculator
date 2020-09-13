# MinutesToYearsAndDaysCalculator
# Challenge from Tim Buchalka's Java Programming Masterclass for Software Developers course.

Write a method printYearsAndDays with parameter of type long named minutes.

The method should not return anything (void) and it needs to calculate the years and days from
the minutes parameter.

If the parameter is less than 0, print text "Invalid Value".

Otherwise, if the parameter is valid then it needs to print a message in the format "XX min = YY y
and ZZ d".

XX represents the original value minutes.
YY represents the calculated years.
ZZ represents the calculated days.

EXAMPLES OF INPUT/OUTPUT:

  * printYearsAndDays(525600); -> should print "525600 min = 1 y and 0 d"
  * printYearsAndDays(1051200); -> should pring "1051200 min = 2 y and 0 d"
  * printYearsAndDays(561600); -> should print "561600 min = 1 y and 25 d"
  
TIPS:

  * Be extra careful about spaces in the printed message.
  
  * Use the remainder operator.
  
NOTES:

  * The printYearsAndDays method needs to be defined as public static.
  
  * Do not add main method to solution code.
