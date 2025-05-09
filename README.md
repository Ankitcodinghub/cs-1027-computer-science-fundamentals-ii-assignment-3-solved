# cs-1027-computer-science-fundamentals-ii-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CS 1027 (Computer Science Fundamentals II) Assignment 3 Solved](https://www.ankitcodinghub.com/product/cs-1027-computer-science-fundamentals-ii-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;50088&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS 1027 (Computer Science Fundamentals II)  Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<h1>Description</h1>
The purpose of this assignment is to get experience working with several topics presented in the course, including recursion, iterators, lists, binary trees and tree traversal.

<strong>Provided Files </strong>

Asn3ProvidedFiles.zip

Assignment3_Tutorial (Includes helpful tips)

You are provided with a number of files to use for the assignment, including a TreeBuilder that builds LinkedBinaryTrees from text files written in a simplified Newick postorder format. There are two tree files provided: small_tree.txt and larger_tree.txt

<strong>Small Tree &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Larger Tree </strong>

&nbsp;

You must complete three methods in LinkedBinaryTree, and two programs TestPathToRoot.java and FindCommonAncestor.java We will separate this into two parts.

<h1>Part 1 – Path to Root</h1>
In the first part you will write a method, pathToRoot, that finds the path from any element in the tree to the root node. If the element is not in the tree, an exception must be thrown (an ElementNotFoundException).

This method will call a recursive method, pathToRootAgain (which you must also write), to actually find the element, and then add the elements on the path to a list (the one passed as a parameter to the recursive method) after it finds the element.

After the method executes, the iterator returned <sup>&nbsp;</sup>by the pathToRoot method must iterate over the elements found on the path from the target element to the root, <em>including</em> the target element and the root.

You will find that these methods have similarities to both the find method as well as the traversal methods in LinkedBinaryTree.java.

The headers of each method are present in the LinkedBinaryTree.java file that was provided to you. You will need to complete these methods.

You will also complete a program called TestPathToRoot.java, which will read a file from the command line, build a tree from the file using the TreeBuilder class, then, for all elements in the tree, print the path from that element to the root.

You must use an iterator to step through each element in the tree. You must also use an iterator to print each path.

This program has been started for you in the provided code.

<strong>Sample output for small_tree.txt </strong>

For element: D – the path to the root is: D B A

For element: B – the path to the root is: B A

For element: E – the path to the root is: E B A&nbsp; For element: A – the path to the root is: A

For element: F – the path to the root is: F C A

For element: C – the path to the root is: C A

For element: G – the path to the root is: G C A

<strong>You must catch and print a useful message for the following exception types: </strong>

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Thrown by the buildTree method: o &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; IOException

<ul>
<li>MalformedTreeFileException  Thrown by the pathToRoot method:</li>
<li>ElementNotFoundException</li>
</ul>
Your program should also catch the exceptions as close to the possible source of the exception as possible, and try to recover. For example, if for some reason it can’t find an element in the tree, it should inform the user, but then continue trying to go through the other elements.

Note: If everything is working properly, it should not be possible to throw the

ElementNotFoundException, as you are iterating over elements you got from the tree structure.

<h1>Part 2 – Lowest Common Ancestor</h1>
Once you have completed Part 1, you can now use those methods to find the lowest common ancestor of two elements. In this part, you will complete the lowestCommonAncestor method which takes two elements as parameters, finds the paths from each element to the root (if the element is in the tree), and then finds the maximal-level node that is shared by these paths.

The method header has been given in the

LinkedBinaryTree.java file. The approach you

use is up to you. You can call either of the &nbsp;&nbsp;&nbsp; <sub>&nbsp;</sub>methods you wrote for the first part. If you are working with a ListADT type, you must use a “for each” loop to go through it, which takes advantage of the Iterable interface.

If either of the two elements passed as parameters cannot be found in the tree, you must throw an ElementNotFoundException.

For this part, you will also complete the program FindCommonAncestor.java.

This program will:

<ol>
<li>read a tree file from the command line</li>
<li>display the contents of the tree</li>
<li>ask the user for two string inputs</li>
<li>output the lowest common ancestor to the console, or an error message informing the user that the element could not be found in the tree</li>
</ol>
This program has been started for you in the provided code, with an example of how to prompt the user for information.&nbsp; <strong>Sample runs with small_tree.txt </strong>Example 1:

The tree contains: DBEAFCG

Enter first element: D

Enter second element: G

The lowest common ancestor is: A

Example 2:

The tree contains: DBEAFCG

Enter first element: F

Enter second element: G The lowest common ancestor is: C Example 3:

The tree contains: DBEAFCG

Enter first element: D

Enter second element: D

The lowest common ancestor is: D

<strong>You must catch and print a useful message for the following exception types: </strong>

<ul>
<li>Thrown by the buildTree method: o IOException
<ul>
<li>MalformedTreeFileException  Thrown by the readLine method:</li>
<li>IOException</li>
</ul>
</li>
<li>Thrown by the lowestCommonAncestor method:
<ul>
<li>ElementNotFoundException</li>
</ul>
</li>
</ul>
For this program, these exceptions are all “fatal”, in that we cannot continue if they occur. Here, you can use a single try/catch/finally structure for the bulk of the functionality, but make sure to clean up any resources you can in the finally block.

<h1>What to hand in</h1>
You will submit, via OWL:

<ul>
<li>java</li>
<li>java</li>
<li>java</li>
</ul>
<h1>Functional Specifications</h1>
<ul>
<li>Your program has to be compliable under Eclipse.</li>
<li>Use Javadoc-style comments for each class and method. All significant variables must be commented.</li>
<li>You do not need to submit the html files generated by running javadoc</li>
<li>Use Java conventions and good Java programming techniques (meaningful variable names, conventions for variable and constant names, etc). Indent your code properly.</li>
<li>Remember that assignments are to be done individually and must be your own work.</li>
</ul>
&nbsp;
