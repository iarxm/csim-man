---
id: org
aliases: []
tags: []
---

Make heat titles in 'Live' dynamic, to reflect dynamic setting of heat formats, without req of re-running script during contest

Separate technical dev of app from principles book

gpt on codes and creeds; gpt on simulation names
https://en.wikipedia.org/wiki/Olympic_Games_ceremony#Ancient_forerunners
https://en.wikipedia.org/wiki/Olympic_symbols#Kotinos
https://www.army.mil/values/index.html

Remove expectation and rule orientated language to suggestions and principles. Do this for briefing section

TODO - ORGANISATION

Goals and logic of each format
Protest protocol improvements
Clarify formats via detailed descriptions
Precision in jersey usage
More breaks for improving judging focus and simulating real contest gaps
Experiment with shorter sessions. And with multiday simulation
Keep to specific times for gaps between heats
6 heats either over 1 or 2 days
or 9 over 3



Increase stock of jerseys
Yellow for winner
Yellow for prize of whole series?
Small prizes per simulation?
Team based approach



NOTES TO MENTION IN DEBRIEF/CHECKIN

Start with reading the olympic values
Judging Criteria - Major Maneuver
Bonus Heat - 
Phone to check scores
Schedulin Q - dual heats or 1 at a time?
Covering other business on rules?


CONTEST SIMULATOR PLANNING

Download offline contingency documents for situations where the location may be out of range of mobile internet
For each location, optimize for weather sheltering that enables high quality judging
Keep seeding codes formal and consistent
Vertical layouts enables simple navigation and natural understanding
And relational data structures can naturally develop
Ensure a simple spreadsheet is ready for deployment in the case of technical issues with the main document


DEV TODO
TODO - set initial seed code to R# for 'Rank' X - make a glob to retrive number and discard letter




How does this document work?
The data workflow of a contest is surprisingly simple
The leaderboard sheet contains seeding which inputs into the round 1 draw
the draw feeds into the meta data of the judging scorecards per judges sheet
The scores across the judges sheets are fed into tally sheet for averaging
The averages are fed into the results sheet
The results sheet feeds back into the draw sheet to calculate the next progression
The draw and the results are filtered into the live sheet for a more compact and readable format. Also providing quick access to any active heats



Opponent simulation via random number generator
Simulate specific surfers like a chess engine
Draw up alts per draw format for addition or subtraction of athlete numbers



Github pages version of the manual
Sidebar injection of the html code

Stabilize v4 with the circular and visual-data mixed logic
Deploy v4 and integrate feedback of use into development of v5
v5 will be with a database sheet as the master source of all data
input views will create datapipelines into it
reading views will pull data out of it
one source of data facts
necessary for more complicated concepts to be implemented such as algorithmic score parity and athlete simulation


