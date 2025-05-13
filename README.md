# csc382-lab-2-average-case-solved
**TO GET THIS SOLUTION VISIT:** [CSC382 Lab 2-Average Case Solved](https://www.ankitcodinghub.com/product/csc382-lab-2-average-case-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94050&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC382 Lab 2-Average Case Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Average Case

</div>
</div>
<div class="layoutArea">
<div class="column">
In this project we will try to match the Average Case of algorithm A5 as we calculated in class and the “Real Average” of the algorithm.

</div>
</div>
<div class="layoutArea">
<div class="column">
A5: int Find (int x, int A[ ], int n) // array of size n {int j;

</div>
</div>
<div class="layoutArea">
<div class="column">
for (j=0; j &lt; n; j++) {

(1) if (x = = A[j]) {

} } return (j+1); //the position is 1 more than the index

</div>
</div>
<div class="layoutArea">
<div class="column">
} return0;//xisnotanelementofthearray

The project is composed of three steps: 1) (Calculated Average)

<ol>
<li>a) &nbsp;Letn=50.</li>
<li>b) &nbsp;Let bound be an integer.</li>
<li>c) &nbsp;Let x be an integer between 0 and bound.</li>
<li>d) &nbsp;Let hits=0.</li>
<li>e) &nbsp;Generate a sequence of n integers using a random number generator where the numbers
of the sequence are between 0 and bound. Save this new sequence in an array Sequence.
</li>
<li>f) &nbsp;If x is equal to any of the numbers generated in the sequence increment hits by one (if x
appears more than once do not increment hits every time).
</li>
<li>g) &nbsp;Repeat steps e and f 10,000 times (in other words create 10,000 sequences of 50 integers
each. Clearly Sequences is a 50 x 10,000 two-dimensional array.
</li>
<li>h) &nbsp;Let q=hits/10,000.</li>
<li>i) &nbsp;Calculate A(n) for algorithm A5 using the formula derived in class.</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2) (Real Average)

Using the sequences created in the previous step (two-dimensional array Sequences) run algorithm A5 10,000 times using each time an input of Sequences. Let total-steps be a variable that tells you the total number of steps executed so far, that is, initialize total-steps to zero, and add the number of steps executed by A5 on each of the inputs, to this variable. For example if A5 executes 25 steps on the first input, then add 25 to total-steps. Let say on second input A5 performs 15 operations, now total-steps = 40 (i.e. 25 + 15). Keep doing this until all the 10,000 inputs are executed by A5. To calculate the Real Average let A2(n)=total-steps/10,000.

3) On step 3 compare A(n) as calculated in step 1) to A2(n) calculated in Step 2.

Run steps 1), 2) and 3) for the following values of bound bound = 30, 50, 80, 100, 1000, 10,000, infinite

You final output should look like:

Bound Calculated Average Real Average

30 XX XX 50 XX XX .. .. .. 10,000 XX XX Infinite XX XX

</div>
</div>
</div>
