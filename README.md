# cs314---specification-7---anagrams-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs314-specification-7-anagrams-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;63138&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS314 - Specification 7 - Anagrams Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<p dir="ltr" align="left"><b>Programming Assignment 7&nbsp;</b>Individual Assignment. You must complete this assignment on your own. You may not acquire from any source (e.g.&nbsp; another student or an internet site) a partial or complete solution to a problem or project that has been assigned. You may&nbsp;<b>not</b>&nbsp;show another student your solution to an assignment. You&nbsp;<b>may&nbsp;not</b>&nbsp;have another person (current student, former student, tutor, friend, anyone) “walk you through” how to solve an assignment. You may get help from the instructional staff. You may discuss general ideas and approaches with other students but you may not develop code together. Review the&nbsp;<a href="https://www.cs.utexas.edu/~scottm/cs314/syllabus.htm#Collaboration">class policy on collaboration from the syllabus</a>.

<ul>
<li>Placed online: Tuesday, March 23</li>
<li>20 points, ~2% of final grade.</li>
<li>Due: no later than 11<span style="font-size: medium;">&nbsp;pm, Thursday, April 1(no fooling)</span></li>
<li><span style="font-size: medium;"><a href="https://www.cs.utexas.edu/~scottm/cs314/Assignments/index.htm">General Assignment Requirements</a></span></li>
</ul>
The purposes of this assignment are:

<ol>
<li>to use various data structures</li>
<li>to implement a program that uses multiple classes</li>
<li>to implement a recursive backtracking algorithm</li>
</ol>
Thanks to Stuart Reges for sharing this assignment with me.

In this assignment you will implement several classes that allow a user to find anagrams of words and phrases they type in.

<hr>
<b>Summary:&nbsp;</b>An anagram is formed by taking all of the letters in one word or phrase and scrabbling them to form a new word or phrase. All of the letters from the original word / phrase must be used and no letters can be added. The new word or words must be valid based on some dictionary. For example an anagram of the phrase “<b><code>Isabelle Scott</code></b>” is&nbsp;<code><strong>"obstacle stile"</strong></code>.

There are many online anagram solvers. One of the better ones can be found at&nbsp;<a href="http://wordsmith.org/anagram/index.html">http://wordsmith.org/anagram/index.html</a>.

See the guide below for suggestions on how to complete the assignment.

<b>Files:</b>

<table border="2" width="100%" cellspacing="6" cellpadding="6">
<tbody>
<tr>
<td align="right" valign="top" width="15%">Source Code</td>
<td width="50%"><a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A7_Anagrams/AnagramMain.java">AnagramMain.java&nbsp;</a>The driver program for the completed anagram solver.</td>
<td width="50%">Provided by me. Do not alter except for printing out time results if you would like.</td>
</tr>
<tr>
<td align="right" valign="top" width="15%">Source Code</td>
<td width="50%">LetterInventory.java A class that represents a collection of letters from the English alphabet.&nbsp;<b>You must add the standard header with your information and the academic honesty statement. Failure to do so will cause you to lose points on the assignment.</b></td>
<td width="50%">Provided by you.</td>
</tr>
<tr>
<td align="right" valign="top" width="15%">Source Code</td>
<td width="50%"><a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A7_Anagrams/AnagramFinderTester.java">AnagramFinderTester.java</a>. A class with tests for the LetterInventory and your AnagramSolver classes. Add at least 2 tests per public method and the constructor in LetterInventory.java. (Delete the provided tests after you are sure you code passes them.)The tester requires the&nbsp;<a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A7_Anagrams/d3.txt">d3.txt</a>&nbsp;file for the dictionary and&nbsp;<a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A7_Anagrams/testCaseAnagrams.txt">this file with the expected results</a>.

Here is the&nbsp;<a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A7_Anagrams/tester_expected_output_trimmed.txt">expected output of the tester without the anagrams shown&nbsp;</a>and&nbsp;<a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A7_Anagrams/tester_expected_output_all.txt">with the anagrams shown</a>. You times will vary.&nbsp;<strong>Any of the given tests that complete in less than 0.2 seconds should take less than 1 second on the CS department machines. Any of the given tests that take &gt;= 0.2 seconds should take no more than 5X my time when run on the CS department machines.</strong>

Sometimes solutions are slow because you have missed a base case and made too many calls to your recursive helper method.&nbsp;<a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A7_Anagrams/tester_output_num_calls.txt">Here is some test output with the number of calls made to the recursive helper method.&nbsp;</a>Note, your number of calls DOES NOT have to match those shown.

Finally, there is a very clever solution that can significantly improve the time it takes to find some anagrams.&nbsp;<a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A7_Anagrams/tester_output_num_calls_clever.txt">Here is the test output for that approach and the number of calls made to the recursive helper method.</a>

<strong><span class="auto-style1">It is up to you to explore various approaches to try and speed up your algorithm. There is no one right way to do this. It is up to you to try different things. Neither the TAs, nor the instructor, have a “magic answer” that works for all cases. I want to stress this. Don’t come to lab hours expecting us to tell you exactly how to speed up your program. We will give high level suggestions, not detailed advice.</span></strong>
</td>
<td width="50%">Provided by me.</td>
</tr>
<tr>
<td align="right" valign="top" width="15%">Source Code</td>
<td width="50%"><a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A7_Anagrams/AnagramSolver.java">AnagramSolver.java</a>. A class that solves and returns a list of anagrams for a given phrase and maximum number of words.</td>
<td width="50%">Provided by you</td>
</tr>
<tr>
<td align="right" valign="top" width="15%">Source Code</td>
<td width="50%"><a href="https://www.cs.utexas.edu/~scottm/cs307/javacode/utilities/Stopwatch.java">Stopwatch.java</a>. A class for calculating elapsed time when running other code. You may use this to see how long it takes to find anagrams and compare results on Piazza.</td>
<td width="50%">Provided by me.</td>
</tr>
<tr>
<td align="right" valign="top" width="15%">Dictionary Files</td>
<td width="50%"><a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A7_Anagrams/d1.txt">d1.txt&nbsp;</a>&nbsp;A small dictionary file with 56 words.

<a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A7_Anagrams/d2.txt">d2.txt</a>&nbsp; A medium size dictionary file with 3927 words.

<a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A7_Anagrams/d3.txt">d3.txt</a>&nbsp; A large dictionary file with 19911 words.<b>Note, when we test your program, we will use other dictionaries that contain one and two letter words. Do not assume all words in the dictionary will have a length of 3 or greater. There can and will be words of length 1 or 2 in the dictionaries we use to test your solution.</b></td>
<td width="50%">Provided by me.</td>
</tr>
<tr>
<td align="right" valign="top" width="15%">Sample Output</td>
<td width="50%"><a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A7_Anagrams/anagramSampleOutput.htm">Sample run of anagram solver using d1.txt</a>. Other than the timing results, your program must match this output given the same input. I have trimmed many of the anagrams for clarity, but when you run AnagramMain it prints out all the result. The output also shows the timing data for the sample solution and the tests in AnagramFinderTester.<a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A7_Anagrams/anagramSampleOutput_not_trimmed.txt">Here is a run of the anagram solver using d3.txt with all the output.</a></td>
<td width="50%">Provided by me.</td>
</tr>
<tr>
<td align="right" valign="top" width="15%">Submission</td>
<td width="50%">Turn in a7.zip with these three files: AnagramFindrerTester.java, AnagramSolver.java, LetterInventory.java.</td>
<td width="50%">Provided by you.</td>
</tr>
</tbody>
</table>
<b>Submission:&nbsp;</b>Complete the header in AnagramFinderTester.java and AnagramSolver.java. Copy it to LetterInventory.java a Replace &lt;NAME&gt; with your name. Note, you are stating,&nbsp;<u>on your honor</u>, that you did the assignment on your own.

Create a zip file name a7.zip with your AnagramFinderTester.java,&nbsp; LetterInventory.java, and AnagramSolver.java files. The zip file must&nbsp;<b>not</b>&nbsp;contain any directory structure, just the required file.

<a href="https://www.cs.utexas.edu/~scottm/cs314/handouts/creating_a_zip_file_via_eclipse.htm">See this page for instructions on how to create a zip via Eclipse.</a>

<p align="left">Turn in a7.zip&nbsp;<a href="https://guides.instructure.com/m/4212/l/41972-how-do-i-submit-an-online-assignment">via your Canvas account</a>&nbsp;to programming assignment 7.

<ul>
<li>
<p align="left">Ensure you files are named AnagramFinderTester.java,&nbsp; LetterInventory.java, and AnagramSolver.java. Failure to do so will result in points off.

</li>
<li>
<p align="left">Ensure AnagramFinderTester.java,&nbsp; LetterInventory.java, and AnagramSolver.java are part of the default package. Do not add a&nbsp;<code>package</code>&nbsp;statement to either file.

</li>
<li>
<p align="left">Ensure your zip has no internal directory structure. When the file is unzipped no directories (folders) are created. (Note, the built in unzip feature of some versions of Windows and Apple OS X “help” by adding a directory when you unzip with the same name as the file. The unzip we use on the CS Linux system does not do this. Neither do unzip programs such as 7zip.)

</li>
<li>
<p align="left">Ensure you submit the assignment under Programming Assignment 7 in Canvas.

</li>
</ul>
<hr>
<b>Checklist:&nbsp;</b>Did you remember to:

<ol>
<li>review and follow the&nbsp;<a href="https://www.cs.utexas.edu/~scottm/cs314/Assignments/index.htm">general assignment requirements</a>?</li>
<li>follow the specific requirements and restrictions for this assignment?</li>
<li>work on the assignment by yourself?</li>
<li>fill in the header in AnagramFinderTester and copy it to LetterInventory.java and AnagramSolver.java?</li>
<li>ensure your LetterInventory and Anagram Solver classes pass the tests in AnagramFindrerTestert? Add at least 2 tests per public method and constructor for LetteInventory?</li>
<li>complete the AnagramSolver and implement a recursive backtracking algorithm with the required efficiency improvements?</li>
<li>ensure your program matches the sample output file when run?</li>
<li>Turn in a file name a7.zip file with your Java source code files LetterInventory.java, AnagramSolver.java, and AnagramFinderTester.java to assignment 7 on Canvas by 11 pm, Thursday, April 1?</li>
</ol>
<hr>
<b>Specification:</b>

<b>The LetterInventory class:</b>&nbsp;Implement a class to model a letter inventory. A letter inventory object stores the number of times each English letter, ‘a’ through ‘z’ occur in a word or phrase. So for example the letter inventory of the word&nbsp;<b>“tall”</b>&nbsp;is

1 a, 2 l’s, and 1 t

The letter inventory for&nbsp;<b>“Isabelle M. Scott!!”</b>&nbsp;is

1 a, 1 b, 1 c, 2 e’s, 1 i, 2 l’s, 1 m, 1 o, 2 s’s, and 2 t’s

Notice the letter inventory ignores characters that are not English letters. Also notice that the letter inventory is case insensitive.&nbsp;<b>“Isabelle M. Scott!!”</b>&nbsp;has 2 s’s.

Implement the LetterInventory class.&nbsp;<b>You must use an array of ints to store the number of times each English letter occurs</b>. The inventory is case insensitive so the length of the array will equal the length of the alphabet being used, in this case 26. Use a class constant for the value 26. The class keeps track of the total number of letters in the inventory so this value can be returned quickly without adding up all the individual counters.

Provide the following constructors and methods:

<ul>
<li>a&nbsp;<b>constructor</b>&nbsp;that accepts a String. The precondition requires the String to not be null. A LetterInventory is constructed based on the String ignoring case. This method shall be no worse than O(N + M) where N is the number of characters in the String and M is the number of letters in the alphabet our LetterInventory is using. Recall you can test if a given character is a letter between ‘a’ and ‘z’ with the following boolean expression: ‘a’ &lt;= ch &amp;&amp; ch &lt;= ‘z’.</li>
<li>a method named&nbsp;<b>get</b>&nbsp;that accepts a char and returns the frequency of that letter in this LetterInventory. The precondition requires that the char be an English letter. It may be an upper or lower case letter. The answer returned must be the same given the upper or lower case version of a letter. This method shall be O(1).</li>
<li>a method named&nbsp;<b>size&nbsp;</b>that returns the total number of letters in this LetterInventory. This method shall be O(1).</li>
<li>a method named&nbsp;<b>isEmpty&nbsp;</b>that returns true if the size of this LetterInventory is 0, false otherwise. This method shall be O(1) with respect to the size of the alphabet.</li>
<li>a method named&nbsp;<b>toString</b>&nbsp;that returns a String representation of this LetterInventory. All letters in the inventory are listed in alphabetical order. For example if a LetterInventory is created from the String “tall” toString would return the String&nbsp;<code>"allt"</code>. If a LetterInventory is created from the String&nbsp;<b>“Isabelle M. Scott!!”</b>&nbsp;the method would return the String&nbsp;<code>"abceeillmosstt"</code>.</li>
<li>a method named&nbsp;<b>add&nbsp;</b>with one parameter, another LetterInventory object. The method returns a new LetterInventory created by adding the frequencies from the calling LetterInventory object to the frequencies of the letters in the explicit parameter. The precondition requires that the LetterInventory sent as an explicit parameter not be null. The postcondition requires that neither the calling object or the explicit parameter are altered as a result of this method call. This method shall be O(M) where M is the number of letters in the alphabet our LetterInventory is using.</li>
<li>a method named<b>&nbsp;subtract&nbsp;</b>with one parameter, another LetterInventory object. The methods returns a new LetterInventory object created by subtracting the letter frequencies of the explicit parameter from the calling object’s (<strong><code>this</code></strong>) letter frequencies.So l<strong><code>et1.subtract(let2)</code></strong>&nbsp;is analogous to&nbsp;<strong>let1 – let2</strong>
If any of the resulting letter counts are less than 0 the method shall return null. the precondition requires the LetterInventory sent as an explicit parameter not be null. The post-condition requires that neither the calling object or the explicit parameter are altered as a result of this method call. This method shall be O(M) where M is the number of letters in the alphabet our LetterInventory is using.
</li>
<li><strong>override</strong>&nbsp;[override, override, override! Do not overload equals.&nbsp;<strong>The parameter shall be of be Object.</strong>] the&nbsp;<b>equals</b>&nbsp;method from Object. Two LetterInventorys are equal if the frequency for each letter in the alphabet is the same.</li>
</ul>
You may add other private methods and constructors if you wish. Note,&nbsp;<code>LetterInventory</code>&nbsp;objects are immutable. There are no methods that alter a given&nbsp;<code>LetterInventory</code>&nbsp;object after it is created.

When you implement the anagram solver you will not use all of these methods, but you are required to complete the class. Your completed&nbsp;<code>LetterInventory</code>&nbsp;class must pass all of the tests in&nbsp;<code>AnagramFindrerTester</code>. You must add at least 2 tests per constructor and public method in&nbsp;<code>LetterInventory</code>&nbsp;to the&nbsp;<code>AnagramFindrerTester</code>&nbsp;class.

<hr>
<b>The Anagram Solver class:&nbsp;</b>Now that you have a LetterInventory class to handle the low level details, implement a class to find all possible anagrams for a given phrase. (Realize that the legal anagrams for a phrase will vary based on what dictionary is used, the maximum number of words allowed in the anagram, and whether words can be repeated in the anagram or not.) For example the anagrams of “Isabelle Scott” using the dictionary in file d3.txt and a limit of no more than 2 words per anagram are:

<code>best, oscillate

bestial, closet

bleat, solstice

blest, societal

closet, stabile

obstacle, stile

solstice, table</code>

<b>Note, there are two special cases your do not have to worry about.</b>

<ul>
<li>First, a given word or phrase<b>&nbsp;is</b>&nbsp;considered an anagram of itself if the word is in the dictionary. So “dog” is an anagram of “dog”</li>
<li>Second, you may use words more than once in the anagram. So for example one of the anagrams of “dog dog” is “god god”.</li>
</ul>
Provide the following for the&nbsp;<code>AnagramSolver</code>&nbsp;class:

<ul>
<li>a public constructor that has one parameter, a Set&lt;String&gt;. (A set of strings.) The set contains the dictionary this AnagramSolver is to use when forming anagrams. This constructor creates and stores letter inventories for each element of the set. Store the original words in the dictionary and their corresponding letter inventories inside the AnagramSolver class. You want to be able to access the letter inventory of a given word quickly, therefore store each word and its associated LetterInventory in a Map.- your class must create the&nbsp;<code>LetterInventorys</code>&nbsp;for a given word in the dictionary exactly one time. (Doing it more than once is an inefficiency you must avoid in this assignment.)
<b>Although none of the provided dictionaries contain words of length 1 or 2, your program must be able to handle dictionaries that do. This isn’t a special case, but in the past students have tried to optimize their code assuming there won’t be any words of length 1 and then failed tests on dictionaries that contained words with a length of 1 or 2. I recommend adding words to the dictionary files of length 1 and 2 to test your program. You can share results of these tests on Piazza.</b>
</li>
<li>a public method named<b>&nbsp;getAnagrams&nbsp;</b>that has two parameters: a String, and an int. The String is the target word or phrase and your method will form anagrams out of that word or phrase. The String sent as a parameter does not have to be in the AnagramSolver’s dictionary. It may contain characters which must be ignored. (Recall this is handled by the LetterInventory class already.) The int parameter indicates the maximum number of words allowed in the anagrams of the given String. If the int is 0 there is no maximum number of words for the anagrams being formed. The precondition requires the String not be null and the String contain at least one English letter. The int parameter must be greater than or equal to 0.The method returns a&nbsp;<code>List&lt;List&lt;String&gt;&gt;</code>. In other words a List of Lists of Strings.&nbsp;<code>List</code>&nbsp;is a Java interface The&nbsp;<code>ArrayList</code>&nbsp;class implements the&nbsp;<code>List</code>&nbsp;interface so you could return an&nbsp;<code>ArrayList&lt;ArrayList&lt;String&gt;&gt;</code>. Don’t alter the return type from&nbsp;<code>List&lt;List&lt;String&gt;&gt;</code>. Returning an&nbsp;&nbsp;<code>ArrayList&lt;List&lt;String&gt;&gt;&nbsp;</code>will work because&nbsp;<code>ArrayList</code>&nbsp;is a kind of&nbsp;<code>List</code>. It implements the&nbsp;<code>List</code>&nbsp;interface. Note, you will create a variable of type&nbsp;<code>ArrayList&lt;List&lt;String&gt;&gt;&nbsp;</code>and add new variables of type&nbsp;<code>ArrayList&lt;String&gt;&nbsp;</code>to it.</li>
</ul>
You can and should add private helper methods as necessary to break the problem up into manageable parts.&nbsp;<b>By way of comparison my AnagramSolver class, including a nested class for a Comparator, is roughly 135 lines including comments, blank lines and lines with a single brace.</b>

<hr>
&nbsp;

Finding the anagrams of a given String is a classic recursive backtracking problem similar to the N queens problem, the phone mnemonic problem, and the fair teams problem.&nbsp;<span class="auto-style1">&nbsp;</span><strong><span class="auto-style1">I think this problem is most similar to the phoneMnemonics problem from assignment 6. There are of course differences in the details, but the basic structure is quite similar.</span></strong>

You shall complete some preprocessing each time your anagram finding method is called. In most cases, many of the words in the dictionary cannot be part of an anagram for the given word or phrase. For example the word “queen” will not be in any anagram of “Isabelle Scott” because there is no ‘q’ in “Isabelle Scott”. Likewise the word “casa’ cannot be part of an anagram of “Isabelle Scott: because there are two ‘a’s in “casa” but only 1 ‘a’&nbsp; in “Isabelle Scott”. You will, of course, use the LetterInventory class to simplify the task of determining if a given word could possibly be part of an anagram. (The subtract method is VERY useful.)

Creating this smaller list of words from the dictionary (we can access the corresponding LetterInventories from our original map that is an instance variable) shall not alter the AnagramSolver’s main dictionary. Once this smaller list of words is created you are ready to carry out the recursive backtracking method to find all anagrams of the given String.&nbsp;<strong>I recommend using the smaller list of words as your “choices” for the recursive step.</strong>

You can also improve your efficiency by&nbsp;<strong>virtually</strong>&nbsp;shrinking the dictionary of possible words as your proceed deeper into the recursion. I don’t not recommend trying to actually shrink the dictionary at each step.

Note that the returned&nbsp;<code>List&lt;List&lt;String&gt;&gt;&nbsp;</code>must have the following properties:

<ul>
<li>The words in a particular anagram are in sorted order</li>
<li>The list does not contain duplicate anagrams</li>
<li>The list of anagrams is sorted with anagrams with the fewest words coming first. In other words all anagrams with 1 word come before all of the anagrams with 2 words which come before all the anagrams with 3 words and so forth. Also, the anagrams with the same number of words are sorted based on the Strings within the anagram. Refer to the&nbsp;<a href="https://www.cs.utexas.edu/~scottm/cs314/javacode/A7_Anagrams/anagramSampleOutput.htm">sample output&nbsp;</a>for examples.</li>
</ul>
Accomplishing all that sorting can be a chore. You might try to do it as you go or simply wait until you have found all the anagrams and then process it. The second option may be a cleaner solution, because it separates the recursive backtracking from the sorting. You are free to use methods from the&nbsp;<a href="http://docs.oracle.com/javase/7/docs/api/java/util/Collections.html">Collections</a>&nbsp;class (not the Collection interface, the Collections class. With an&nbsp;<b>s</b>. The Collections class contains a number of static methods that perform common task on various kinds of Collection objects.) to make this easier as well as other data structures.

Initially there is no way to sort a list of anagrams. Lists and ArrayLists are not Comparable. One approach would be to create a class that implements the&nbsp;<a href="http://docs.oracle.com/javase/7/docs/api/java/util/Comparator.html">Comparator</a>&nbsp;interface. The Comparator interface allows you to define how two objects should be compared if they are not Comparable. You will need a separate class, but don’t put in in a separate file. Instead, you can make your class that implements the Comparator interface a nested class, similar to the iterators you have implemented, except this class will be declared static because it doesn’t need to know about the outer class.

<p dir="ltr"><code>public class AnagramSolver {

// code for AnagramSolver</code>

<p dir="ltr"><code>&nbsp;&nbsp;&nbsp; // example of a nested class

private static class AnagramComparator implements Comparator&lt;List&lt;String&gt;&gt; {

public int compare(List&lt;String&gt; a1, List&lt;String&gt; a2) {

// code for compare

}

} // end of AnagramComparator</code>

<p dir="ltr"><code>} // end of AnagramSolver class</code>

The compare method for the Comparator interface is similar to the compareTo method for Comparable. If a1 is “less than” a2 return a negative int. If a1 “equals” a2 return 0. If a1 is “greater than” a2 return a positive int.

When you create a class that implements the Comparator interface correctly you can call the sort method in the Collections class that takes in a list and a comparator to sort the List of Lists of Strings.

<hr>
<p align="center">&nbsp;&nbsp;<a href="https://www.cs.utexas.edu/~scottm/cs314/index.htm">Back to the CS 314 homepage.</a>
