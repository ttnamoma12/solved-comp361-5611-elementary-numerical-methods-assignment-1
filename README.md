Download Link: https://assignmentchef.com/product/solved-comp361-5611-elementary-numerical-methods-assignment-1
<br>
<strong>Problem 1. (25%) </strong>Write a program and use it to compute the <em>Harmonic sum </em>,

<em>, </em>using <strong>single precision </strong>(<em>i.e., float</em>), for <em>N </em>= 10<em><sup>n</sup></em>, with <em>n </em>= 1<em>,</em>2<em>,</em>3<em>,</em>···<em>,</em>8<em>, </em>(or higher). Repeat the computations, but use the <strong>double precision</strong>. Plot the partial sums on the graph in terms of <em>N </em>values. Mathematically, <em>i.e.</em>, when using <em>exact </em>arithmetic, this sum is known to <em>diverge </em>as <em>N </em>tends to infinity, <em>i.e.</em>, the sum can be made arbitrarily large by taking <em>N </em>sufficiently large. Explain the observed behavior of the <em>numerically </em>computed sums. You can the calculus books, e.g. Stewart <em>Calculus</em>, Cengage 2015 or internet to determine the asymptotic behaviour of the harmonic series and to help you to interpret the results of computations (always cite your sources in the assignment report).

Similarly compute the sum (in single and double precision) and report your findings. Plot the partial sums on the graph in terms of <em>N </em>values.

Mathematically this sum is known to <em>converge </em>as <em>N </em>tends to infinity. Use the internet or calculus books to compute the sum analytically for a fixed <em>N </em>and find its limit when <em>N </em>→ ∞.

<strong>Problem 2. (25%) </strong>For given <em>x</em><sup>(0)</sup>, say, <em>x</em><sup>(0) </sup>= 1<em>.</em>0, write a program to compute the sequence <em>x</em><sup>(1)</sup>, <em>x</em><sup>(2)</sup>, <em>x</em><sup>(3)</sup>, ···, <em>x</em><sup>(<em>N</em>)</sup>, up to a suitably large value of <em>N</em>, <em>e.g.</em>, <em>N </em>= 20, or higher where necessary, using the recurrence relation

<em>x</em><sup>(<em>k</em>+1) </sup>= <em>f</em>(<em>x</em><sup>(<em>k</em>)</sup>)<em>,              k </em>= 0<em>,</em>1<em>,</em>2<em>,</em>3<em>,</em>···<em>,</em>

where  . Plot the results on the graph in terms of <em>N </em>values.

Describe in a few words the observed behavior of the sequence. In particular, does the sequence approach a limiting value? If yes, then do you recognize what this limiting value is? Does the limiting value depend on <em>x</em><sup>(0) </sup>? The theory for this problem may be found in the Notes, p. 102-116.

Also compute the sequence with <em>f</em>(<em>x</em>) = <em>cx</em>(1−<em>x</em>), for five cases, namely, <em>c </em>= 0<em>.</em>95, <em>c </em>= 1<em>.</em>55, <em>c </em>= 2<em>.</em>0, <em>c </em>= 3<em>.</em>6, and <em>c </em>= 3<em>.</em>98. For each of these cases choose the value of <em>x</em><sup>(0) </sup>to lie between 0 and 1, for example, <em>x</em><sup>(0) </sup>= 0<em>.</em>1. Plot the results on the graph in terms of <em>N </em>values. In each case describe the observed behavior of the sequence. The theory for this problem may be found in the Notes, p. 117-125.

<strong>Problem 3. (50%) </strong>Consider the approximate integration of a function <em>f</em>(<em>x</em>) over the interval [0<em>,</em>1]. Let <em>M </em>be a positive integer, and let <em>h </em>= 1<em>/M</em>, and <em>x<sub>k </sub></em>= <em>kh</em>, for <em>k </em>= 0<em>,</em>1<em>,</em>2<em>,</em>3<em>,</em>···<em>,M. </em>Thus <em>x</em><sub>0 </sub>= 0 and <em>x<sub>M </sub></em>= 1. Then one approximate integration formula is

<em>.</em>

This method is known as the <em>Midpoint Rule</em>.

Another approximate integration formula is

<em>.</em>

This method, which requires <em>M </em>to be even, is known as the <em>Simpson’s Rule</em>.

Implement these two methods in programs, and use each of these to approximately integrate the function <em>f</em>(<em>x</em>) = sin(<em>πx</em>) over the interval [0<em>,</em>1], using successively the following values of <em>M</em>: <em>M </em>= 2, 4, 8, 16, ··· . For each of these values of <em>M </em>print the error, <em>i.e.</em>, the absolute value of the difference between the approximation and the known exact value of the integral, which you can obtain analytically. Plot the results on the graphs. Make sure to represent <em>π </em>to sufficient precision in your program!

Furthermore, for each of the two methods, determine from your computations the smallest value of <em>M </em>for which the error is less than 10<sup>−7</sup>. How many function evaluations are required in each of these two cases?

Can you describe the observed behavior of the error? In particular, for each of the two methods, can you say approximately how the error depends on <em>h </em>? More specifically, it is known that the errors will be approximately proportional to <em>h<sup>p</sup></em>, where <em>p </em>is an integer that depends on the method. Can you tell from the numerical results what <em>p </em>is for each of the two methods? Also can you explain what happens to the error when <em>M </em>gets “very large”?

In the last part of this problem you will justify some of the previous results theoretically. Specifically:

<ul>

 <li>Use the internet, the calculus books or the textbook to find the upper boundson the error of the Midpoint Rule, i.e., on in terms of <em>f</em>, its derivatives and <em>M</em>. Use the bound to find the smallest value of <em>M </em>such that the error bound becomes less than 10<sup>−7</sup>.</li>

 <li>Use the internet, the calculus books, the textbook or the Notes, p. 268286 to find the error bound for the Simpson Rule, i.e. the upper bounds on</li>

</ul>

in terms of <em>f</em>, its derivatives and <em>M</em>. Use the bound to

find the smallest value of <em>M </em>such that the error bound becomes less than 10<sup>−7</sup>.

For this assignment you need to submit the report describing your findings and the source codes of all the programs you developed.