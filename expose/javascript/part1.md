# Part 1

## Question 1
It prints: values added: 20. There is no error.

## Question 2
It prints: final result: 20. There is no error.

## Question 3
Because var has function scope, not block scope. This can cause bugs because the variable can be accessed outside the block where it is defined, which may lead to unexpected behavior.

## Question 4
It prints: values added: 20. There is no error.

## Question 5
It will cause an error. The error is because result is declared with let, which has block scope. So result cannot be accessed outside the if block, and line 13 will give a ReferenceError.

## Question 6
It will cause an error. The error is because const variables cannot be reassigned. In the code, result is declared as const but later we try to change its value, which is not allowed.

## Question 7
It will cause an error. Because the program already fails before reaching line 13 due to const reassignment. So nothing is printed for line 13.