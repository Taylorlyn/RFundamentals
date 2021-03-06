# R Fundamentals Day 3

<center>
<div>
<table>
<tr>
<th>[Day1](Day1.md)</th><th>[Day2](Day2.md)</th><th>[Day3](Day3.md)</th><th>[Day4](Day4.md)</th>
</tr>
</table>
</div>
</center>

+ [R Session for Day 3](RSession3)

+ Recap/Questions
+ Everything is an object in R - including the language objects, functions, if, while, ....
+ lists, data.frames 
    + [, [[ and $
    + Data frames and 2-D subsetting
+ Can't use logical vector in 1-D list subsetting for [[ 
    + x[[  c(TRUE, FALSE, TRUE, ... ) ]]
    + Need to use which().  But need to ensure only one or else hierarchical subsetting.
    + Or `x [ logicalVector ][[1]]`
+ [factors](Factors.html)
    + Subsetting by factors and keeping/dropping levels.
+ [Vectorization in rnorm(), etc.](rnormVec.html)
    + `rnorm(n, mean = vector, sd = vector)`
+ [apply() functions](Apply.html)
    + Passing additional arguments
    + Different apply() functions
+ [try()/tryCatch()](tryCatch.html)
+ [2-D subsetting - matrices](MatrixSubsetting.html)
+ [Writing Functions](WritingFunctions.html)
    + Default values for parameters
    + Idioms
    + warnings and errors
+ [Debugging](Debugging.html)
+ [Writing R Packages](WritingPackages.html)
    + Directory structure
	+ DESCRIPTION
	+ NAMESPACE
+ [Other Topics](Day4.html)

