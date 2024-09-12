---
layout: default
---



<link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.10.21/css/jquery.dataTables.min.css" />
<script src="https://code.jquery.com/jquery-3.5.1.js"></script>
<script src="https://cdn.datatables.net/1.10.21/js/jquery.dataTables.min.js"></script>  


# Autumn 2024

## Class Information

Item                     | Section 0020                
------------------------ | -----------                  
Schedule                 | Tue/Thursday 5:30 PM - 6:50 PM EST
Location                 | Zoom. Details on Carmen.
Professor                | Greg Ryslik / ryslik DOT 1 AT osu DOT edu
Professor Office Hours   | Fridays (2:20 - 3:40 PM) - via zoom. Contact me ahead of time if you plan to attend.
TA                       | Ziheng Zhang / zhang DOT 13617 AT buckeyemail DOT osu DOT edu
TA Office Hours          | Per request. Please reach out over slack/ email.
Slack Discussion Group   | See the link in Carmen! Say hello!

All classes will be recorded and posted for you to review online afterwards if you want to listen again. 

Some classes may need to be rescheduled earlier or later due to professor travel. They will of course be recorded as well if the new time doesn't work. 

<em> Please enable your camera if you're able. I understand it's not always possible but it's very helpful to the me! </em>


## Description: 
By the end of this course, students should be comfortable using propositional logic, first-order predicate logic, be familiar with basic mathematical proofs such as proof by contradiction and strong and ordinary mathematical induction, be familiar with using asymptotic notation, be able to analyze running time of simple iterative or recursive algorithms, and finally be familiar with basic definitions and algorithms in graph theory.

## Grading Plan: 
1. Midterm 1: 20%
2. Midterm 2: 20%
3. Final: 35%
4. HW: 20%
5. Participation/Retrospectives: 5%

There might be tentative bonus points assigned for harder math or cs problems. Max would be at most 3%. At the discretion of the professor :-). 

### Retrospectives
At the end of each week, I ask you to submit a very short writeup about how the week went. Essentially: <b>
 1) What went well <br> 
 2) What can be improved/did not go so well <br>
 3) What did you like learning. 

A few sentences is fine here -- I just want to keep an eye on how the course is progressing throughout the semester.

## Grading Scheme
Grades will follow the standard scale: 

--- 

A : 93 <= grade <= 100 <br>
A-: 90 <= grade < 93   <br>
B+: 87 <= grade < 90   <br>
B : 83 <= grade < 87   <br>
B-: 80 <= grade < 83   <br>
C+: 77 <= grade < 80   <br>
C : 73 <= grade < 77   <br>
C-: 70 <= grade < 73   <br>
D+: 67 <= grade < 70   <br>
D : 60 <= grade < 67   <br>
E : <60  

## Textbooks:
You might find the following books useful but I won't assign homework from them. 

1. Discrete Mathematics and Its Applications, Eighth Edition, By Kenneth Rosen.
2. Introduction to Algorithms, Third Edition, by Corman, Leiserson, Rivest and Stein.


## Class course

<table class="display" border=1 frame=sides rules=all>
  {% for row in site.data.Syllabus %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th>{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}

    {% tablerow pair in row %}
      {{ 	pair[1] }}
    {% endtablerow %}
  {% endfor %}
</table>

