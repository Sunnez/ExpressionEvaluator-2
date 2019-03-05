# ExpressionEvaluator
Python script to evaluate arithmetical expressions.

Most of the code is actually turning a string into tokens and this is done in a very hacky manner. The fun and interesting part, and the reason I coded this, was the algorithm which should hopefully be readable :-)

Usage example:
```
python3 main.py "5 +2*(3^2*2-15) -6^(6/ (5-2)*2-2)/ (13 -10)"
```
```
RPN: 5 2 3 2 ^ 2 * 15 - * + 6 6 5 2 - / 2 * 2 - ^ 13 10 - / - 
Result: -1.0
```
