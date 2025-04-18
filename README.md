# EwbankGrader
Find overall grade of sport climb by adding up the sections

This is a simple Ewbank version of the MASTERPEICE DarthGrader.

I did my own math using some set points from Darth, see: https://www.desmos.com/calculator/c3mshhgvzb . Polynomial used is just a quadratic, which is simple but does cause some errors on edge cases.

To calibrate this to a particular crag or style think about two climbs of the same grade stacked on top of each other. Consider what the combined grade would be with no rest (N) and also with a good rest (G). Set N to be the no rest increase in grade, and G to be the good rest increase.

For example, by default N is 2.5, which means if you stack two 25s with no rest you get a 27.5 (a 27/28). A good rest would add 1.75 grades and result in a hard 26.

Can use V-grades, it converts them like this: https://www.desmos.com/calculator/a7n2mkrfw7 and does a similar adjustment to Darth.
