1. The bug was that the numbers from the input boxes were being treated like strings instead of actual numbers. So instead of adding them like 2 + 3 = 5, it was putting them together like "2" + "3" = "23".
2. To fix it, I changed the code so that the input values get converted to real numbers using Number(). That way, when the two values are added, they act like numbers and not strings.








