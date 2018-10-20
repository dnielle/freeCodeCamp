---
title: Evaluating Polynomials Synthetic Division
---
## Evaluating Polynomials Synthetic Division

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/algorithms/evaluating-polynomials-synthetic-division/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

#### More Information:
<!-- Please add any articles you think might be helpful to read before writing the article -->


Step 1: Check your divisor 

In order to do Sythetic Division your divisor must be a linear expression with a leading coefficient of 1.
i.e. (x-7), (x+25) and so on.

Moreover, if you have an expression such as 2x-12 although it is a linear expression you still have to manipulate it into having a leading coefficient of 1. 

Recall: 2x-12
        x - 12/2
        x-6
        
Step 2: Set-up (a matter of preference)

On the Divisor: Some people prefer using the number in the factor directly, that is if you have x-7 you will use -7 and subtract down columns.
Others prefer using the root +7 and then adding down columns, as they believe adding is way easier.

Whichever way you choose, that number will be on the outside of your L-box.

On the Dividend: Always check if your exponents are in descending order, if not you must use a zero for that term.
                 An example is if you have f(x) = 2x^4 - 5x^3 - x + 17
                                you then must use 2    - 5  0  -1   17 inside L-box.
                                
Your setup should look like this

                                 +/- 7 | 2  -5  0  -1  17 
 
