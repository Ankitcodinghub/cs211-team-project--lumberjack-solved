# cs211-team-project--lumberjack-solved
**TO GET THIS SOLUTION VISIT:** [CS211 Team Project- Lumberjack Solved](https://www.ankitcodinghub.com/product/cs211-lumberjack-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;126852&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS211 Team Project- Lumberjack Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
Team project of CS2x1:Data Structures and Algorithms at IIT Dharwad

Problem statement

You are a lumberjack in a roadside forest. Every day you would like to cut down trees of the maximum value in the limited time that you have. We represent a forest as a rectangular grid of dimensions n by n points. Each edge between the neighboring grid points has a length of 1. At the position of each point, there could be a tree. Each tree is described using the following parameters:

height h thickness d unit weight c unit value p

We calculate the value of each tree according to the formula: p Ã‚Â· h Ã‚Â· d. To cut down the tree, you have to reach it first. You can move only along the edges between the neighboring grid points. To cut down the tree at the position that you occupy you have to select one of four directions (along grid lines) in which the tree will fall. At the beginning of the day, you start in the lower-left corner of the forest, which is located at the point (0,0). You can assume that there is no tree there. If the tree that you cut falls on the other tree, which is lighter than the one that is falling, then this tree will also fall without being cut directly. We say that the tree is heavier if the total weight calculated as c Ã‚Â· d Ã‚Â· h is greater than the total weight of the second tree. In this way, one can achieve a domino effect by pushing one tree onto another. We assume that a tree falls on the other when the distance between them is less the height of this tree. Weights of trees do not cumulate – we always take into account only the weight of the tree, which directly fell onto another. If for example tree A falls onto tree B and its weight is greater than weight of tree B then it can push tree B onto another tree C located in the same direction if the distance between B and C is smaller to height of B and, moreover, tree C is lighter than tree B. When comparing trees B and C we do not take into account tree A that lays on tree B. Moreover, if tree B is not lighter than tree A then it blocks tree A and it will not have a chance to fall onto tree C.

Calculate the biggest profit that you can reach during t time units and provide a corresponding sequence of movements. Assume that the walk between the two neighboring grid points takes 1 unit of time, and cutting the tree takes d units of time.

Input

The first line of input contains three integers: 0 &lt; t &lt;= 5,000 representing the time limit for the lumberjack, 0 &lt; n &lt;= 1,000 represending the size of the grid, and 0 &lt; k &lt;= 10,000 denoting the number of trees. In the following k lines there is a description of consequtive trees consisting of six integer numbers 0 &lt;= x, y &lt; n, 0 &lt; h, d &lt;= 20, 0 &lt; c, p &lt;= 500 representing the position of the trees on the grid, their height, thickness, weight and value.

Output

On the output specify a list of moves (using move prefix) and cuts (using cut prefix) with the suffix denoting the direction of the action (up, right, down or left), each on a separate line. Scoring

For each test case, your program will receive the score equal to the total value of trees that were cut down by the lumberjack. You should maximize this value. For each test with n &lt;= 25, your program should execute below 1 second, for 25 &lt; n &lt;= 100, your program should execute below 10 seconds, and for n &gt; 100 your program should execute below 60 seconds. For each test the available memory is limited to 1 GB.

Example Input

11 10 5

2 3 4 5 2 2

2 6 3 1 1 3

2 7 2 2 2 4

5 5 10 3 1 5

4 3 5 5 2 6

Example output

move right move right move up move up move up cut up move right
