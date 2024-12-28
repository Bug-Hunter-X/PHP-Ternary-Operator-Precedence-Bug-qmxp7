# PHP Ternary Operator Precedence Bug

This repository demonstrates a common error in PHP related to the precedence of operators within a ternary expression.  Improper use of parentheses when the ternary operator is combined with other operators (like +, *, &&, ||) can lead to unexpected results.

The `bug.php` file shows the incorrect implementation, highlighting how missing parentheses cause incorrect order of operations.  `bugSolution.php` provides the correct version with parentheses to ensure the intended evaluation order.

This example illustrates the importance of being mindful of operator precedence in PHP, especially when using the ternary operator with complex expressions.