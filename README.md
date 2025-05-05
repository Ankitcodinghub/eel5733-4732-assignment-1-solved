# eel5733-4732-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [EEL5733/4732 Assignment 1 Solved](https://www.ankitcodinghub.com/product/eel5733-4732-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101508&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EEL5733\/4732 Assignment 1&nbsp;Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
You are going to implement <strong>three programs</strong> using the C programming language:

<ol>
<li><strong>Email Filter:</strong> Input: A sequence of emails, Output: A sequence of calendar events</li>
</ol>
The input will be read from the standard input and the standard output will be used for output. Each line of the input will represent an email, which will be in the following format (we are abstracting away other fields such as from, to, etc.):

&nbsp;

Subject: String

&nbsp;

If the subject string is in one of the following formats, then it is considered a calendar relevant event. The types of calendar events are as follows:

&nbsp;

C,title,MM/DD/YYYY,HH:MM,location -&gt; Create an event with the given title, date, and time

D,title,MM/DD/YYYY,HH:MM,location -&gt; Delete an event with the given title, date, and time&nbsp; X,title,MM/DD/YYYY,HH:MM,location -&gt; Change the event with the matching title using the provided date, time, and, location

&nbsp;

Both the title and the location are required to be of length 10. If the actual string is shorter, it must be padded with the space character. Note that the Email Filter program will not take any of the actions specified above. Instead, it will write the subject string if it matches one of the event types and well-formed.

&nbsp;

As an example:

&nbsp;

Sample Input (each email is on a separate line and note the white space used for the padding): Subject: Hello

Subject: Greetings

Subject: C,Meeting&nbsp;&nbsp; ,01/12/2019,15:30,NEB202

Subject: Change in plans

Subject: X,Meeting&nbsp;&nbsp; ,01/12/2019,15:45,Larsen239

Subject: D,01/12/2019,15:45,Larsen239

&nbsp;

Expected Output:

C,Meeting&nbsp;&nbsp;&nbsp; ,01/12/2019,15:30,NEB202

X,Meeting&nbsp;&nbsp;&nbsp; ,01/12/2019,15:45,Larsen239

&nbsp;

&nbsp;

&nbsp;

Please note that the last email with the delete event is not well-formed as the title is missing. Therefore, it is not included in the output.

&nbsp;

<ol start="2">
<li><strong>Calendar Filter</strong>: Input: A series of calendar events, Output: A sequence of tuples of dates, times, and locations</li>
</ol>
&nbsp;

The goal of this program is to inform the user about the changes in the time or location of the earliest event of the days that have been edited in the calendar so that the user can plan when to leave home and choose the most convenient parking lot for a given day. The input will be read from the standard input and the standard output will be used for output.

&nbsp;

We will assume that the calendar is empty (no events) when the program starts. It processes each calendar event (each on a separate line) one by one and if an output needs to be generated then it must be written to the standard output immediately before moving on to processing the next calendar event.&nbsp; <strong>When it processes a calendar event, in addition to updating the calendar it also outputs the date, time, and location of the earliest event if the time or the location of the earliest event changes</strong>. So, if a calendar event does not change the location or the time of the earliest event then nothing should be output as a result of processing that calendar event. In the special case of deleting all the events on a date, the time will be displayed as –:– and the location will be displayed as NA. Each line of the output will be in the following format:

&nbsp;

MM/DD/YYYY,HH:MM,location

&nbsp;

Sample input 1:

C,Meeting&nbsp;&nbsp; ,01/12/2019,15:30,NEB202

X,Meeting&nbsp;&nbsp; ,01/12/2019,15:30,Larsen239

&nbsp;

Expected Output:

&nbsp;

01/12/2019,15:30,NEB202

01/12/2019,15:30,Larsen239

&nbsp;

Sample input 2:

C,Class&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ,01/13/2019,10:30,NEB102

C,Meeting&nbsp;&nbsp; ,01/12/2019,15:30,NEB202

X,Meeting&nbsp;&nbsp; ,01/12/2019,15:30,Larsen239

C,Lab&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ,01/12/2019,11:30,Larsen239

&nbsp;

Expected Output:

&nbsp;

01/13/2019,10:30,NEB102

01/12/2019,15:30,NEB202

01/12/2019,15:30,Larsen239

01/12/2019,11:30,Larsen239

&nbsp;

&nbsp;

&nbsp;

Sample input 3:

C,Class&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ,01/13/2019,10:30,NEB102

C,Meeting&nbsp;&nbsp;&nbsp; ,01/12/2019,15:30,NEB202

D,Meeting&nbsp;&nbsp;&nbsp; ,01/12/2019,15:30,NEB202

C,Lab&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ,01/12/2019,17:30,Benton321

&nbsp;

Expected Output:

&nbsp;

01/13/2019,10:30,NEB102

01/12/2019,15:30,NEB202

01/12/2019,–:–,NA

01/12/2019,17:30,Benton321

&nbsp;

Sample input 4:

C,Class&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ,01/13/2019,10:30,NEB102

C,Meeting&nbsp;&nbsp;&nbsp; ,01/12/2019,15:30,NEB202

C,Lab&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ,01/12/2019,15:30,Benton321

&nbsp;

Expected Output:

&nbsp;

01/13/2019,10:30,NEB102

01/12/2019,15:30,NEB202

01/12/2019,15:30,Benton321

&nbsp;

Sample input 5:

&nbsp;

C,Class&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ,01/13/2019,10:30,NEB102

C,Meeting&nbsp;&nbsp;&nbsp; ,01/13/2019,15:30,Larsen239

&nbsp;

Expected Output:

&nbsp;

01/13/2019,10:30,NEB102

&nbsp;

As in the case of Email Filter, location must have exactly 10 characters (padded with whitespace if needed).

&nbsp;

Both the Email Filter and the Calendar Filter programs should check for the end of file (EOF) character while reading from the standard input. When testing your programs, if you enter the input on the terminal you can use CTRL-D to simulate the EOF. Alternatively, you can save your input file and redirect it to your executable as follows:

&nbsp;

$ ./myprog &lt; inputfile

&nbsp;

<ol start="3">
<li><strong>Location Updater</strong>: Input: A sequence of emails, Output: A sequence of tuples of dates, times, and locations</li>
</ol>
The input will be read from the standard input and the format is the same as that of the input for the Email Filter program. The output will be on the standard output and the format for the output is the same as that of the output for the Calendar Filter program. The program will process the incoming emails and update the calendars, which is assumed to be empty initially.

When it processes a calendar event that sets/changes the location/time of the earliest event for that date, in addition to updating the calendar it also outputs the date, time, and the location of the earliest event. <strong>&nbsp;</strong>

&nbsp;

<strong>Your solution must reuse Email Filter and Calendar Filter programs via the system calls fork, exec, pipe, and dup/dup2 to implement the Location Updater program</strong>. Please note that using these two programs via copying &amp; and pasting into the Location Updater program will not receive any credit. <em>The goal of this assignment is to show you how independently written programs with well-defined behavior, e.g., Email Filter and Calendar Filter, can be combined to implement new programs, e.g., Location Updater, with minimal effort with the help of various system calls. </em>So, you should implement three separate programs for this Assignment and your Makefile should generate three executable files. Please see the supplemental data for submission instructions and a test input. Your solution will be tested on a Linux machine. So please make sure to test your solution on a Linux platform and feel free to reach out to the Instructor and the TA for any questions/issues. Good luck!

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;
