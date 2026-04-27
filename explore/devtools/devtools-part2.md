1. The bug is that num1 and num2 are strings from the input fields, so the + operator concatenates them and produces "23" instead of adding them as numbers.

2. I would convert num1 and num2 to numbers before adding them.
let result = Number(num1) + Number(num2);