# gator-avl-project-solved
**TO GET THIS SOLUTION VISIT:** [Gator AVL Project Solved](https://www.ankitcodinghub.com/product/gator-avl-project-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;61968&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Gator AVL Project Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (5 votes)    </div>
    </div>
<strong>Gator AVL Project</strong>

Problem Statement

Binary Search Trees (BST) can often be an efficient and useful way to store and retrieve sorted data. However, the efficiency of these data trees relies heavily on how balanced a BST is. For example, searching through the BST on the left is much more efficient than searching through the BST on the right, despite both figures showing valid BST with the exact same elements.

<img data-recalc-dims="1" decoding="async" class="size-full wp-image-61970 aligncenter lazyloading" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/02/631.png?resize=230%2C164&amp;ssl=1" alt="" width="230" height="164" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/02/631.png?resize=230%2C164&amp;ssl=1" style="--smush-placeholder-width: 230px; --smush-placeholder-aspect-ratio: 230/164;">

<p style="text-align: left;"><strong>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Fig.1 : A nearly balanced BST</strong>

&nbsp;

<img data-recalc-dims="1" decoding="async" class="wp-image-61972 aligncenter lazyload" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2021/02/995-246x300.png?resize=104%2C127&amp;ssl=1" alt="" width="104" height="127" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" style="--smush-placeholder-width: 104px; --smush-placeholder-aspect-ratio: 104/127;">

<p style="text-align: center;"><strong>Fig.2 : A skewed BST</strong>

To avoid inefficient binary search trees, we use balanced Binary Search Trees. A balanced BST has a balance factor of less than <em>±threshold, </em>where the balance factor is the difference in heights of the left and right subtrees at any given tree node. One such balanced tree is an AVL tree that maintains a <em>threshold </em>of 1. As soon as a node in an AVL tree hits a balance factor of +2/-2, “tree rota<sup>–</sup>dons” will be performed to maintain balance in the tree.

In this project, you will be designing a custom AVL tree to organize UF student accounts based on GatorlDs. You will write methods for the insertion, deletion, search, and traversal for an AVL tree data structure. These methods would be called based on certain commands that are invoked in the main method. You are responsible for

&nbsp;

<ul>
<li>Designing the interface/modules/functions of the standard AVL Tree and the operations required to execute the respective commands.</li>
<li>Parsing the input and ensuring the constraints are met.</li>
<li>Building the main function to parse the inputs and calling the respective functions to match the</li>
<li>Testing your code within the constraints.</li>
</ul>
Functionality

Your program must support the following commands:

<table>
<tbody>
<tr>
<td width="118"><strong>Command</strong></td>
<td width="87"></td>
<td width="371"><strong>Function</strong></td>
</tr>
<tr>
<td width="118"></td>
<td width="87"></td>
<td width="371"></td>
</tr>
</tbody>
</table>
&nbsp;

&nbsp;

<ul>
<li>Add a Student object into the tree with the specified name, NAME and GatorlD number, ID.</li>
<li>Balance the tree automatically if necessary.</li>
<li>The ID must be unique.</li>
<li>The ID and <em>NAME </em>must satisfy the constraints stated below.</li>
<li>Also, prints “successful” if insertion is successful and prints “unsuccessful”</li>
<li><em>NAME </em>identifier will be separated by double inverted commas for parsing, e.g. “Josh Smith”.</li>
</ul>
&nbsp;

&nbsp;

&nbsp;

<ul>
<li>Find and remove the account with the specified ID from the tree.</li>
<li>[Optional: Balance the tree automatically if necessary. We will test your code only on cases where the tree will be balanced before and after the deletion. So you can implement a BST deletion and still get full credit]</li>
<li>If deletion is successful, print “successful”.</li>
<li>If the <em>ID </em>does not exist within the tree, print “unsuccessful”.</li>
<li>You must prioritize replacing a removed node with its inorder <em>successor </em>for the case where the deleted node has two children.</li>
</ul>
&nbsp;

<table>
<tbody>
<tr>
<td width="10"></td>
</tr>
<tr>
<td></td>
<td></td>
</tr>
</tbody>
</table>
&nbsp;

&nbsp;

<ul>
<li>Search for the student with the specified ID from the tree.</li>
<li>If the ID was found, print out their</li>
</ul>
&nbsp;

<table>
<tbody>
<tr>
<td width="119">search ID</td>
<td width="462">·&nbsp;&nbsp;&nbsp;&nbsp; Search for the student with the specified ID from the tree.

·&nbsp;&nbsp;&nbsp;&nbsp; If the <em>ID </em>was found, print out their <em>NAME.</em>

·&nbsp;&nbsp;&nbsp;&nbsp; If the <em>ID </em>does not exist within the tree, print “unsuccessful”.
</td>
</tr>
<tr>
<td width="119">search NAME</td>
<td width="462">·&nbsp;&nbsp;&nbsp;&nbsp; Search for the student with the specified name, NAME in the tree.

·&nbsp;&nbsp;&nbsp;&nbsp; If the student name was found, print the associated <em>ID.</em>

■ If the tree has more than one object with the same <em>NAME, </em>print each <em>ID </em>on a new

line with no other spaces and in the same relative order as a pre-order traversal.

·&nbsp;&nbsp;&nbsp;&nbsp; If the name does not exist within the tree, print “unsuccessful”.

·&nbsp;&nbsp;&nbsp;&nbsp; NAME identifier will be separated by double inverted commas for parsing, e.g. “Josh Smith”.
</td>
</tr>
<tr>
<td width="119">printlnorder</td>
<td width="462">·&nbsp;&nbsp;&nbsp;&nbsp; Print out a comma separated inorder traversal of the names in the tree.</td>
</tr>
<tr>
<td width="119">printPreorder</td>
<td width="462">·&nbsp;&nbsp;&nbsp;&nbsp; Print out a comma separated preorder traversal of the names in the tree.</td>
</tr>
<tr>
<td width="119">printPostorder</td>
<td width="462">·&nbsp;&nbsp;&nbsp;&nbsp; Print out a comma separated postorder traversal of the names in the tree.</td>
</tr>
<tr>
<td width="119">printLevelCount</td>
<td width="462">·&nbsp;&nbsp;&nbsp;&nbsp; Prints the number of levels that exist in the tree.

·&nbsp;&nbsp;&nbsp;&nbsp; Prints 0 if the head of the tree is null. For example, the tree in <strong><em>Fig. </em></strong><strong>1 </strong>has 4 levels.
</td>
</tr>
<tr>
<td width="119">removelnorder <em>N</em></td>
<td width="462">·&nbsp;&nbsp;&nbsp;&nbsp; Remove the N<sup>th</sup> GatorlD from the inorder traversal of the tree <em>(N = </em>0 for the first item, etc).

·&nbsp;&nbsp;&nbsp;&nbsp; If removal is successful, print “successful”.

·&nbsp;&nbsp;&nbsp;&nbsp; <strong>[Optional: </strong>Balance the tree automatically if necessary. We will test your code only on cases where the tree will be balanced before and after the deletion. So you can implement a <strong>BST </strong>deletion and still get <strong>full </strong>credit]

·&nbsp;&nbsp;&nbsp;&nbsp; If the N<sup>th</sup> GatorlD does not exist within the tree, print “unsuccessful’.
</td>
</tr>
</tbody>
</table>
&nbsp;

AVL Tree Data Structure

In order to receive full credit for this project, you must attempt to create an AVL Tree data structure/object class that is used in your main program. Additionally, this AVL tree should:

&nbsp;

<ul>
<li>Also meet the requirements for a Binary Search Tree (BST)</li>
<li>Be sorted by the numerical GatorlD, not the lexical Name</li>
<li>Be sorted from least to greatest (nodes of lesser value are in the left subtree, nodes of greater value are in the right subtree)</li>
<li>Make appropriate use of public and private methods</li>
</ul>
Constraints

<ul>
<li>Tests</li>
<li>1 &lt;= No. <em>of Commands &lt;= </em>200,000</li>
</ul>
c 1 &lt;= <em>Unique UFIDs &lt;= </em>100,000

<ul>
<li>Data</li>
<li>UFIDs are strictly 8 digits long.</li>
<li>Name must include only alphabets from [a-z, A-Z, and spaces]</li>
<li>Commands: We will stick to the input format and will not test misspelled commands.</li>
<li>Design/Implementation</li>
</ul>
You must design your own AVL tree from scratch.

You must use the four standard AVL rotations to keep all results standardized for our test cases.

You must use C++11 and ensure that your code runs on Stepik. <strong>You will get a 0 on the coding </strong><strong>points if your code does not execute on Stepik.</strong>

Sample Input/Output <strong>Input</strong>

&nbsp;

8

insert “Brandon” 45679999 insert “Brian” 35459999 insert “Briana” 87879999 insert “Bella” 95469999 printInorder

remove 45679999

removeInorder 2

printInorder

Note: Line 1 denotes the number of lines or the total number of commands that follow.

<strong>Output</strong>

successful successful successful successful Brian, Brandon, Briana, Bella

successful successful Brian, Briana

Testing

Test your code on Stepik before submitting your implementation. You have five available test cases and you can submit any number of times. The <strong>sixth </strong>test case is fake to prevent you from accessing your peers’ code. <strong>Link to Stepik:</strong> <a href="https://stepik.org/lesson/486088/step/1?unit=477268">https://stepik.org/lesson/486088/step/1?unit=477268</a>

<strong>In addition </strong>to the 5 public test cases, after the due date your submission will be tested with 10 additional test cases. In order to maximize your grade, you should <strong>create your own test cases </strong>and run them against your code <strong>on Stepik. In particular, you </strong>should test your code with test cases that include over <strong>100 insertions </strong>into your tree.

&nbsp;

Grading

<ul>
<li><strong>Implementation [75 points] </strong>Your code will be tested on 15 test cases each worth 5 points:</li>
<li>5 publicly available test cases</li>
<li>10 test cases that will be added by the course staff during grading</li>
<li>On Stepik, test case 6 is fake. So if your code passes test cases 1-5. That means you will get 25/75 points automatically.</li>
<li><strong>Documentation [15 Points] </strong>Submit a document addressing these prompts:</li>
<li>What is the computational complexity of each method in your implementation? Reflect for each scenario: Best, Worst and Average. [10 points]</li>
<li>What did you learn from this assignment and what would you do differently if you had to start over? [5 points]</li>
<li><strong>Code Style and Design [10 Points]</strong></li>
<li>5 points for design decisions and code modularity</li>
<li>5 points for appropriate comments</li>
<li>5 points for whitespaces</li>
<li>5 points for consistent naming conventions</li>
<li><strong>Bonus [5 points] – Capped to 100 points</strong></li>
</ul>
You can receive 5 bonus points if you submit a separate file containing 5 test cases (1 point/test) using the Catch Framework. These tests should be different than the public test cases. <strong>Your score is however capped to 100 points for this project. </strong>This means if you pass 14 tests and submit the bonus test files, you can get a 100 provided you score full points on the documentation. Also, if you pass 15 tests and score 23 on documentation and design + 5 points on bonus, you will still score 100 points.

TA’s Hamish and Ori have created a GitHub repository with starter files to help enable students to get started with Catch2. The repository link: avl-project.
