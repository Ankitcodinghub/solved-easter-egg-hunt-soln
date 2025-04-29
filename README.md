# solved-easter-egg-hunt-soln
**TO GET THIS SOLUTION VISIT:** [SOLVED:Easter Egg Hunt soln](https://www.ankitcodinghub.com/product/solvedeaster-egg-hunt-soln/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;2585&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;SOLVED:Easter Egg Hunt soln&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Lab Overview This lab uses an Easter egg hunt to review the use of ﬁles. Please download the ﬁle lab07_files.zip from the Piazza site. This includes a set of large text ﬁles named 1.txt, 2.txt, etc. Inside these ﬁles are hidden Python programs, total 6 of them. To hunt them down, you need to recover the individual lines and write them down into a program ﬁle. Then, you must execute that ﬁle within Wing. You will have to do a bit ﬁle parsing to get there. Collect them all! Checkpoint 1: Simple text processing This checkpoint is very easy, should take you less than 10 minutes to do. Write a simple function called parse_line that takes as input a line of text such as: 12/3/4/Here is some random text, like 5/4=3. You should then convert this to a four tuple of the form: (12,3,4,”Here is some random text, like 5/4=3″) where the ﬁrst three values are converted to integer, and the remainder of the text is a string. The ﬁrst values are always assumed to be separated by a slash. You must however do some error checking. If you do not have a line in this given format, or the values contained in the ﬁrst three slots are not integers, then your function should return None. Here are some example runs of this function: parse_line(“12/3/4/Here is some random text, like 5/4=3”) (12, 3, 4, ‘Here is some random text, like 5/4=3’) parse_line(“as12/3/4/Here is some random text, like 5/4=3”) None parse_line(“12/a/412/3/4/Here is some random text, like 5/4=3”) None parse_line(“12/32/4 Here is some spaces “) None parse_line(“12/12/12/ Again some spaces\n”) (12, 12, 12, ‘ Again some spaces\n’) Some advice here. You can use a limited version of split for this or use more complex processing using find. To complete Checkpoint 1: Show your code and output once you are ﬁnished. Checkpoint 2: Parsing some ﬁles Copy your ﬁle from checkpoint 1 to a new ﬁle called check2.py. We will not use the function you have just implemented in this part, but it is good to keep it around for the next checkpoint. Make sure you save the program ﬁle into the same folder as the text ﬁles given in the ZIP folder. This checkpoint is the second step to building your Easter egg hunt code. This is probably the most complex part of your lab. You will write a new function: get_line(fname,parno,lineno) which takes as input a ﬁle name and two numbers. Basically, the two numbers tell you which paragraph and which line your Easter egg hunt lies. Paragraphs are separated by any number of blank lines, containing nothing but the new line character and spaces. You must open the given ﬁle, skip all the paragraphs up to the requested one (parno), skip all the lines until the given line (lineno), read and return the requested line. For example, suppose a ﬁle contains the following text: I love deadlines. I love the whooshing noise they make as they go by. I refuse to answer that question on the grounds that I don’t know the answer. If we are looking of paragraph 2 and line 3, your function should return the string grounds that\n. Do not remove the newline, that will be important for the next checkpoint. Write a program that asks the user a ﬁle number, a paragraph number and a line number. Then, call this function to ﬁnd the line at this given location. For example, using the ﬁles given to you, here are some example runs: Please file number == 1 Please enter paragraph number == 5 Please enter the line number == 5 2/3/3/import webbrowser Please file number == 2 Please enter paragraph number == 3 Please enter the line number == 3 2/4/4/webbrowser.open(“http://hackertyper.com/”) Please file number == 2 Please enter paragraph number == 4 Please enter the line number == 4 0/0/0/END 2 To complete Checkpoint 2, show a TA or mentor your code once you have checked it for these test cases. Now for the Easter egg hunt! If we look at the above examples, we can see the following. File 1, paragraph 5, line 5 contains the line: 2/3/3/import webbrowser This means two things: • The ﬁrst line of the program you are reading is: import webbrowser • The next line of your program is at ﬁle 2.txt, paragraph 3 and line 3. The line at 2/3/3/ contains the content: webbrowser.open(“http://hackertyper.com/”) This line points you to the next line, which is at 2/4/4. The line at this location has the content: 0/0/0/END This means, you are at the end of the program. By following these clues about where the next line is, you have read a program with the following lines: import webbrowser webbrowser.open(“http://hackertyper.com/”) Your Easter egg hunt starts at a given line and continues to ﬁnd the next line until you reach the end. All the lines you found are part of a small Python program. Checkpoint 3: Putting it all together Now, we are going to put these together. Copy your code from the previous checkpoint to a ﬁle called check3.py. As in checkpoint 2, you will ask from the user a starting point: ﬁle number, paragraph number and the line number. You will ﬁrst ﬁnd the ﬁrst line of the program. Then, you will construct the program using a WHILE loop, until you reach the line 0/0/0/END. Write the lines you found in a ﬁle called program.py. When done, execute the recovered program. Try the following starting points: 1/5/5 8/27/6 1/82/10 You program must report failure if your parsing fails, which would happen if you have a bug in your code for counting paragraphs and lines or an incorrect starting point is given. To complete Checkpoint 3, show your code to the TA who will test it with a given Easter egg. 3 Things to think about Well, you actually do not need to be told where the eggs are. There is an algorithm to recover them. Can you outline it or even better write it? Hint: it involves a type of while loop and very doable at your current level of programming. There is a very easy algorithm that works for some eggs. But you need to get more sophisticated to ﬁnd all of them. Remember: they are not all that well hidden. Please post to Piazza your ideas of how to discover all the eggs, but do not post the locations. See if others can ﬁgure out where they are or how to ﬁnd them. Some of these eggs are actually quite elaborate programs, so happy hunting! 4
