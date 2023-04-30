Download Link: https://assignmentchef.com/product/solved-csce310-homework-1
<br>
This assignment consists of 5 analytical problems and 2 programming problems. Your solutions to the analytical problems must be submitted, as one PDF, via webhandin. While handwritten (then scanned) solutions to the analytical problems are acceptable, you are strongly encouraged to typeset your solutions in L<sup>A</sup>TEX or a word processor with an equation editor. The legibility of your solutions is of great importance. <strong>It is required that your PDF’s filename not include spaces, percent signs, parentheses or pound symbols.</strong>

<h2>Programming Assignment</h2>

Your methods will be tested on the cse.unl.edu server, using gcc version 4.8.5 (SUSE Linux)). To ensure proper execution, you should test your submission in the <a href="http://cse.unl.edu/~cse310/grade">webgrader</a>

You will submit csce310homework01part01.h, csce310homework01part02.h, csce310homework01part01.cpp, and csce310homework01part02.cpp, along with your PDF, via webhandin. Starter code can be found in Canvas, see the announcement.

productOfDigits

productOfDigits is a function that should take one unsigned long long int as input and return a unsigned long long int value. productOfDigits should return the product of the digits in the input decimal integer.

printPermutations

printPermutations is a function that should take one string as input and print out the unique permutations of that string using the Johnson-Trotter algorithm. Each permutation should appear on a separate line. Section 4<em>.</em>3 in <em>The Design and Analysis of Algorithms </em>may be of some use. You can assume that the string is already in lexicographic order.

<strong>General Guidelines</strong>

Sample header, source, and testing files have been provided. You may modify the .h and .cpp files as needed, but you will only be turning in the four files mentioned above. The webgrader will be compiling the code for each part separately with the command g++ -o /path/to/executable.out /path/to/source/files/*.cpp.

If testing locally, know that test01.cpp takes a filename as a command-line argument and reads in a number from that file. test02.cpp takes one argument: the string.

Written Assignment

<strong>Question 1     </strong>

<em>Adapted from Problem </em>2<em>.</em>1<em>.</em>7 <em>in The Design and Analysis of Algorithms</em>

Gaussian elimination, the classic algorithm for solving systems of <em>n </em>linear equations in <em>n </em>unknowns, requires about  multiplications, which is the algorithm’s basic operation.

<ol>

 <li>How much longer should you expect Gaussian elimination to work on a system of 30 equations versus a system of 10 equations?</li>

 <li>You are considering buying a computer that is 1000 times faster than the one you currently have. By what factor will the faster computer increase the sizes of systems solvable in the same amount of time as on the old computer?</li>

</ol>

<strong>Question 2    </strong>

Question 2<em>.</em>1<em>.</em>9 in <em>The Design and Analysis of Algorithms</em>

<strong>Question 3   </strong>

<em>Adapted from Problem </em>2<em>.</em>4<em>.</em>1 <em>in The Design and Analysis of Algorithms</em>

Solve the following recurrence relations.

<ol start="9">

 <li><em>x</em>(<em>n</em>) = <em>x</em>(<em>n </em>− 1) + 1 for <em>n &gt; </em>1 and <em>x</em>(1) = 9.</li>

 <li><em>x</em>(<em>n</em>) = 6<em>x</em>(<em>n </em>− 1) + 2 for <em>n &gt; </em>0 and <em>x</em>(0) = 6.</li>

 <li><em>x</em>(<em>n</em>) = <em>x</em>(<em>n </em>− 1) + <em>n</em><sup>3 </sup>for <em>n &gt; </em>0 and <em>x</em>(0) = 6.</li>

 <li>1 and <em>x</em>(1) = 7. Solve for <em>n </em>= 7<em><sup>k</sup></em>.</li>

 <li>1 and <em>x</em>(1) = 4. Solve for <em>n </em>= 9<em><sup>k</sup></em>.</li>

</ol>

<strong>Question 4       </strong>(10 points)

Question 3<em>.</em>1<em>.</em>5 in <em>The Design and Analysis of Algorithms</em>

<strong>Question 5       </strong>(10 points)

Question 4<em>.</em>1<em>.</em>5 in <em>The Design and Analysis of Algorithms</em>

<strong>Question 6       </strong>(10 points)

<strong>Extra Credit or Honors Contract </strong>Question 3<em>.</em>3<em>.</em>5 in <em>The Design and Analysis of Algorithms</em>

<h1>webgrader Notes</h1>

The webgrader should take roughly 60 seconds to complete running.

<strong>Your submission’s success against each test case will be determined by use of </strong>diff<strong>. Your output must be exact. If you are intending to use debugging output, send that output to stderr, not stdout. Only send output you intend to be matched against the solution output to stdout. </strong><strong>External Resources</strong>

<a href="http://www.cplusplus.com/">cplusplus.com </a><a href="http://en.cppreference.com/w/">cppreference.com</a>

<a href="https://en.wikibooks.org/wiki/Subject:C++_programming_language">Wikibook</a>