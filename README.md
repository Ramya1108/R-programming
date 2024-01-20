> assignment2 <- c(16, 18, 14, 22, 27, 17, 19, 17, 17, 22, 20, 22)
> myMean <- function(assignment2) { return(sum(assignment2)/length(assignment2)) }
> myMean(assignment2)
[1] 19.25
> EXPLANATION
A vector assignment2 with the values [16, 18, 14, 22, 27, 17, 19, 17, 17, 22, 20, 22] is defined by the supplied R code. The definition of a function called myMean follows, which computes the mean (average) of the values in a vector (in this case, assignment2) as an input. The vector's length is divided by the total of all of its values to determine the mean.
This is how the code is broken down:
assignment2 \- c(16, 18, 14, 22, 27, 17, 19, 17, 17, 22, 20, 22): This generates a vector with the indicated numerical values called assignment2.
function(assignment2) { return(sum(assignment2)/length(assignment2)) } for myMean <- This defines a function called myMean, whose argument is a vector (assignment 2). Within the function, the value is calculated to the mean by dividing the vector's length (length(assignment2)) by its total (sum(assignment2)). The outcome is given back.
myMean(assignment2): This line prints the outcome of the myMean function call that takes the vector assignment2 as an input. The mean of the numbers in assignment 2 is 19.25 in this instance.
References: R is the programming language used to write this code. The length and sum functions that were utilized are typical R functions. For further information on these functions, consult the R documentation: for sum functions, length function 
