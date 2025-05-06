# comp2017-assignment-4-scheduling-trains-solved
**TO GET THIS SOLUTION VISIT:** [COMP2017 Assignment 4-Scheduling-Trains Solved](https://www.ankitcodinghub.com/product/comp2017-assignment-4-scheduling-trains-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97342&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP2017 Assignment 4-Scheduling-Trains Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Problem Description

You have been given the task to create a program that will find the next earliest train departure after your arrival at the station. This program will notify the user of the next train departure they should board using information from a timetable containing multiple entries of the starting station, destination station and the time the train is departing the starting station. The timetable will be in the form of a text file which will contain the source, destination and departure times of all trains on the rail network. The timetable information will be read by your program from standard input. The user will provide command line arguments, providing the source, destination and time of arrival at the source station.

Program Structure Timetable Data

The train network timetable will be presented in a double colon separated format. The format will specify the source, destination and leaving time from the source station.

The source and destination component may contain spaces and will be sub-strings of the line entry. Each entry in the timetable is separated by a new line. Following the &lt;time&gt; , a new line character is expected. Each entry will not exceed the maximum number of characters (4096), however, in the event your submission encounters an entry greater than the maximum string length, your program must skip this entry.

The data is formatted in the following form.

The following is an example schedule.

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>&lt;source&gt;::&lt;destination&gt;::&lt;time&gt;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Paterson::Werris Creek::23:22:23
Paterson::Werris Creek::00:01:23
Paterson::Werris Creek::00:55:23
Paterson::Lochinvar::01:06:11
Paterson::Lochinvar::02:01:11
Paterson::Lochinvar::02:56:11
Condobolin::Wangaratta::11:56:26
Condobolin::Wangaratta::12:01:26
Condobolin::Wangaratta::12:58:26
Condobolin::Maitland::09:30:22
Condobolin::Maitland::10:01:22
Wangaratta::Maitland::10:58:22
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Your submission must be able to handle erroneous data that is contained within the schedule. This may include entries that contain an inappropriate number of colons or breaks, missing source, destination and time information as well as invalid time formats.

To clarify, You do not need to handle intermediate stations

Standard Input

Your program will need to accept the train network schedule via standard input. The data will be pushed into standard input via redirection and you will be able to use any allowed function that can operate directly on standard input such as fscanf , .

Do note, your program cannot hold all the data from the file in main memory as per the restrictions of this assignment, you will need to process it, line by line. If no data is supplied, your program should output to standard error No timetable to process .

You should only read through the file once, your program should not attempt to re-read the data after it has been read. Please do not attempt to use or on standard input.

Command Line Arguments

The search criteria is passed to the program via command line arguments, your program will need to accept all three command line arguments or it should otherwise quickly exit and output how to use the program. Refer to to the Not Enough Arguments section.

The command line arguments are given in the format and order:

The following is an example of program execution with command line arguments.

The time format must be supplied in 24 hour format and in the following format

, where hh represents the hour, mm represents the minutes and ss , the number of

seconds.

Examples

Each example will contain the timetable contents, specified as timetable.list, program execution

Single Station 1

timetable.list

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
fgets , fread

rewind fseek

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>./timetable &lt; timetable.csv
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>./timetable &lt;source&gt; &lt;destination&gt; &lt;time&gt;
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>./choochoo Sydney Melbourne "11:59:59" &lt; timetable.csv
The next train to Melbourne from Sydney departs at 12:05:40
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
&lt;hh&gt;:&lt;mm&gt;:

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
&lt;ss&gt;

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Wirragulla::Cardiff::09:38:23
Wirragulla::Cardiff::10:01:23
Wirragulla::Cardiff::10:30:23
Wirragulla::Cardiff::10:59:23
Wirragulla::Cardiff::11:01:23
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Single Station 2

timetable.list

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Coffs Harbour::Morisset::19:09:14
Coffs Harbour::Morisset::19:54:14
Coffs Harbour::Morisset::20:01:14
Coffs Harbour::Morisset::20:46:14
Coffs Harbour::Koolewong::19:43:40
Coffs Harbour::Koolewong::20:01:40
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>./timetable "Coffs Harbour" Koolewong "19:45:15" &lt; timetable.list
The next train to Koolewong from Coffs Harbour departs at 20:01:40
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Multiple Stations

timetable.list

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Sydney::Melbourne::08:05:00
Sydney::Melbourne::09:32:45
Sydney::Melbourne::11:45:32
Sydney::Melbourne::13:12:19
Sydney::Melbourne::19:59:15
Sydney::Melbourne::22:32:21
Melbourne::Sydney::14:13:12
Melbourne::Sydney::16:55:12
Melbourne::Sydney::18:33:12
Melbourne::Sydney::20:25:12
Melbourne::Sydney::22:22:12
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>./timetable Sydney Melbourne "19:40:59" &lt; timetable.list
The next train to Melbourne from Sydney departs at 19:59:15
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Missing Station

timetable.list

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Sydney::Melbourne::08:05:00
Sydney::Melbourne::09:32:45
Sydney::Melbourne::11:45:32
Sydney::Melbourne::13:12:19
Sydney::Melbourne::19:59:15
Sydney::Melbourne::22:32:21
Melbourne::Sydney::14:13:12
Melbourne::Sydney::16:55:12
Melbourne::Sydney::18:33:12
Melbourne::Sydney::20:25:12
Melbourne::Sydney::22:22:12
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>./timetable Wirragulla Cardiff "10:20:05" &lt; timetable.csv
The next train to Cardiff from Wirragulla departs at 10:30:23
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
Not enough arguments

Restrictions

Below are a list of restrictions on your submission. An aim of this assignment is to efficiently use memory and construction an application within these fixed boundaries.

You are not allowed to use any dynamic memory of any kind, this includes any alloc family functions, brk, sbrk and mmap. You are not allowed to use any temporary files or or variable length arrays. Static and global variables need to be rationalised when using them.

You are not allowed to use any function that belongs in string.h directly.

You are allowed to reimplement any function that you want to use in string.h such as finding the length of a string, tokenising a string or copying a string from one location to another. You can safely assume the largest line is 4096 characters.

You cannot use static or global memory, utilise the preprocessor #define mechanism for your constants.

Your submission must successfully compile with the submission system’s compilation command.

Your program will be compiled using the provided Makefile. You can make modifications to the file, but cannot remove flags from CFLAGS , or change the compiler being used.

If your submission violates any of these restrictions, your submission will receive 0 marks.

Error Handling and Test Cases

The public test cases will only include valid data and you will need to ensure that your program can handle invalid test data. You are tasked with developing your own set of test cases that will need to test both valid input and invalid input. You must document your test cases in a file named

, this file must contain a brief description of each test case you have created. Please keep in the root of your assessment repository. The make test command must successfully execute your test cases and provide human readable output to the user.

Consider the following scenarios when testing your code.

Error cases and return codes

Timetable file that can exceed stack memory limit

Cross-day times (when the closest time is the next day, candidate train may be available on the next day)

Time format

Lines longer than the maximum limit

Unsorted data

</div>
</div>
</div>
</div>
