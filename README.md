Download Link: https://assignmentchef.com/product/solved-cpe202-lab-1-recursion-and-python-testing
<br>
<h1>Lab 1: Recursion and Python Testing</h1>

<ul>

 <li>Do not change any of the function names/parameters given in this assignment.</li>

 <li>In all cases, if the int_list parameter passed into a function is None, the function should raise the ValueError exception</li>

 <li>Write an iterative function to find the maximum integer in a list of integers. If list is empty, return None.</li>

</ul>

<strong>def </strong>max_list_iter(int_list):  <em># must use iteration not recursion </em>

<em>   “””finds the max of a list of numbers and returns the value (not the index)    If int_list is empty, returns None. If list is None, raises ValueError”””</em>

<ul>

 <li>Write a recursive function to reverse a list of integers</li>

</ul>



<strong>def </strong>reverse_rec(int_list):   <em># must use recursion </em>

<em>   “””recursively reverses a list of numbers and returns the reversed list </em>

<strong>   </strong><em>If list is None, raises ValueError”””</em>



<ul>

 <li>Write a recursive function to search a list of integers using binary search along with test cases. If the <strong>target </strong>of the search is in the list, the function returns its index. Otherwise, returns <strong>None</strong> (includes the case where the list is empty return <strong>None</strong></li>

</ul>



<strong>def </strong>bin_search(target, low, high, int_list):  <em># must use recursion </em>

<em>   “””searches for target in int_list[low..high] and returns index if found </em>

<em>   If target is not found returns None. If list is None, raises ValueError “””</em> <strong>Details: </strong>The following files are given to you in your GitHub repository:

<ul>

 <li><strong>py</strong></li>

 <li><strong>py</strong></li>

 <li><strong>py</strong></li>

 <li><strong>py</strong></li>

</ul>



<h1>Test Cases</h1>

Many people tend to focus on writing code as the singular activity of a programmer, but testing is one of the most important tasks that one can perform while programming. Proper testing provides a degree of confidence in your solution. Systematic testing helps you to discover and then debug your code. Writing high quality test cases can greatly simplify the tasks of both finding and fixing bugs and, as such, <strong>will save you time during development</strong>.  However, testing does not guarantee that your program is correct.




For this part of the lab you will practice writing some simple test cases to gain experience with the unittest framework. I recommend watching the first 20 minutes or so of the following video if you need more guidance on testing in Python.  <u><a href="https://www.youtube.com/watch?v=6tNS--WetLI">https://www.youtube.com/watch?v=6tNS</a><a href="https://www.youtube.com/watch?v=6tNS--WetLI">—</a><a href="https://www.youtube.com/watch?v=6tNS--WetLI">WetLI</a></u>




Using your editor/IDE of choice, open the <em>lab1_test_cases.py </em>file. This file defines, using code that we will treat as a boilerplate for now, a testing class with a single testing function.

In the <em>test_expressions </em>function you will see some test cases already provided. You must add additional test cases to verify that your functions (max_list_iter, reverse_rec, bin_search) are correct.