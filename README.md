# SAIT Assessment

Hello,

Here you will find my attempt at the assessment questions sent to me on the 22nd of June.

In an effort to have as little backend work as possible for these, the questions are being resolved in pure JavaScript.


## Question 1
The data provide in the assessment was placed into an object array for further processing, in a real world scenario this
would probalby come in as s JSON stream so this should simulate that adequately.

## Question 2
As I could not clearly understand the desired math with repect to the vacation and holiday days, i have not accounted 
for those in the calculations.  The math is easy enough, however its use in the question was not clear.

I have used vanilla JavaScript and Bootstrap for a "cleaner" UI in this question.  As well validation is being left up 
to the browser.  The script code does not perform any validation on its side and presumes all data coming in is sane 
(as validated on the browser end).  If compatibility with older browsers were needed the data validation could be 
implemented in the code obviously, however I felt in this instance that would be more work than necessary for an 
assessment.

## Question 3
Question 3 was a bit of a chore partialy due to my struggles with code pen, and the way they bundle things.  I'm sure 
the actual files store would be simple to find things.  I've included a .css file as well for just the CSS changes as 
I found it easier to manage css changes on their own for the css parts.

For the slick-slider part I have reverted to the monolithic html file from codepen - for ease of verification the
changes were only to the HTML part by wrapping the cards in g-slide divs (look around line 8982 in the bundled file 
please).


