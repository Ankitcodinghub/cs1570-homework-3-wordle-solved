# cs1570-homework-3-wordle-solved
**TO GET THIS SOLUTION VISIT:** [CS1570 Homework 3-Wordle Solved](https://www.ankitcodinghub.com/product/cs1570-homework-3-wordle-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101951&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1570 Homework 3-Wordle Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="section">
<div class="layoutArea">
<div class="column">
This homework assignment requires you to modify your work done in HW02. The modifications will be primarily based on the new knowledge that you have acquired on C++ switch-case statements and functions.

</div>
</div>
<div class="layoutArea">
<div class="column">
Background

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Specifications:

Modification 1:

Previously, the Wordle bot needed to ask the players many questions throughout the game; sometimes, this can take away the aesthetic quality of our program. In order to fix this, we are going to create a more structured menu to present to players. The menu should resemble the one shown below, and you must implement it using a switch-case statement:

The Wordle’s Menu

——————-

1. Start a new game (with new players)

2. Start a new round (with existing players) 3. Print game summary (of existing players) 4. Share result (of last round)

5. Exit the game (are you sure?)

Do not forget to implement the proper input validation for the menu! Additionally, if no rounds have been recorded yet, then option 3 and option 4 should not be allowed to be chosen. Your program should produce an error message when the user tries to select one of these options.

Modification 2:

The second major modification would be to add some functions to your new program such that the overall code organization could be improved.

Functional requirement 1: The greet() function

This function’s only purpose is to greet the users when the program is first run.

It should not need any parameters or return anything. Also, it should only be called once throughout the program. A sample greet message that would be appropriate is provided as followed:

Welcome to Wordle For Friends! ≤^.^≥

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Functional requirement 2: The printGameSummary() function

The purpose of this function is to output the current game summary for the

existing players. This function should have five parameters: one for Player 1, one for Player 2, one for the number of rounds played, one for the original friendship level, and one for the current friendship level. A sample output from this function is provided below. Besides printing out the overall game summary, this particular function can get sympathetic sometimes whenever the current friendship level is lower than 20. In that case, the function will add a two-level bonus to the friendship of the existing players, and then print it out. For instance, if the actual current friendship level passed into this function is 19, then the new value to be printed out would be 21.

<pre>Game Summary
     Player 1: Frank
</pre>
<pre>     Player 2: Fiona
     Number of rounds played: 50
     Initial friendship level: 10
     Current friendship level: 21
</pre>
The update made to the current friendship level should be persistent outside of this function as well. For example, if the existing players choose to play another round, then the game should start out with the updated friendship level of 21 too.

Functional requirement 3: The shareWordle() function

The purpose of this function is to share the last round’s result of existing

players. A sample output is provided below. The sample is for Player 1 = Frank, Player 2 = Fiona, last round number = 1, and Fiona took 4 attempts to guess the key word (SOUND) correctly (KITTY -&gt; CLOTH -&gt; PONDS -&gt; SOUND). Note that there is a minor change for one of the notations as well. When a correct letter is entered but at a wrong position, we will use the abridged notation ^-^ rather than the previous one ^(‘-’)^ (so that the output for sharing can be tidier). For this function, we are not going to tell you what parameters it needs. So plan for it carefully.

Wordle For Friends (Frank and Fiona)

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
@.@ @.@ @.@ @.@ @.@ @.@ @.@ ^-^ @.@ @.@ @.@ ^o^ ^-^ ^-^ ^-^ ^o^ ^o^ ^o^ ^o^ ^o^

Wordle Round 1 4/6 This is your Wordle

</div>
<div class="column">
journey for the day to be shared!

</div>
</div>
<div class="layoutArea">
<div class="column">
Hint:

If you have a string variable and you want to add more data to it, you may

simply use the addition operator to do that.

<pre>     string aBeautifulPhrase = “Cup of Joe”;
     aBeautifulPhrase += “ is ”;
     aBeautifulPhrase += “Easy as Pie”;
     cout &lt;&lt; aBeautifulPhrase; // this will print “Cup of Joe is
</pre>
Easy as Pie”!

Sample Outputs

Coming soon… In the meantime…

</div>
</div>
</div>
</div>
