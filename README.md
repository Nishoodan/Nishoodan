## R Calculator 

Here’s a simple R calculator that performs basic arithmetic operations:

```r
# Simple R Calculator

add <- function(x, y) {
  return(x + y)
}

subtract <- function(x, y) {
  return(x - y)
}

multiply <- function(x, y) {
  return(x * y)
}

divide <- function(x, y) {
  if(y == 0) {
    return("Division by zero is not allowed")
  } else {
    return(x / y)
  }
}

# Example usage
add(10, 5)        # Returns 15
subtract(10, 5)   # Returns 5
multiply(10, 5)   # Returns 50
divide(10, 5)     # Returns 2
