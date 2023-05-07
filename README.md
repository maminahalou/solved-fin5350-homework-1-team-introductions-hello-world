Download Link: https://assignmentchef.com/product/solved-fin5350-homework-1-team-introductions-hello-world
<br>
Part I




Please create a slide deck presentation to introduce yourself to your fellow classmates. You will present these in a Zoom session to your group. The session will be recorded and uploaded as Part I of this assignment. Your slide deck should include the following:




* A recent picture of yourself.

* Your major and why you chose it.

* Your current career goals. If uncertain: what are some possbilities you are considering?

* Your reason for taking this class. What have you heard about it?

* One idea that has profoundly influenced your life and thinking.

* The title of a recent book that you have read (or are currently reading). What is one thing you learned from it? (More if you wish to share).

* A Q&amp;A slide at the end.




You may produce your slide deck in any presentation software that you like. The only requirement is that you must deliver your slide deck to your Team Leader in the Adobe PDF file format. Your Team Leader will be setting up a Zoom session. You must deliver your slide deck to them prior to this session.




&lt;br&gt;




### Part II




In this part of the assignment you will be working in pairs of two.




___NB:___ the only exception is that if you have a three-person team you will be working together as a whole team for this portion of the assignment instead of in pairs of two.




&lt;br&gt;




Your Team Leader will assign pairs for the team. You will complete this portion of the assignment with your counterpart assigned to your pair.




To complete this portion of the assignment, you will need the following:




* Git installed locally on your computer.

* A GitHub account.

* The Anaconda distribution of Python installed locally on your computer.

* The Jupyter-Lab extension installed in your Python distribution. (More on this later).




&lt;br&gt;




In the programming world, it is a tradition to begin learning a new programming language by writing a `Hello World` program (a simple program that prints the message “Hello, World!” out to the console or other output). This is what we will be doing here.




To complete this portion of the assignment each student must do the following:




* Coordinate with your pairs teammate and schedule a Zoom session to complete the exercise.

* Create a remote repository on your GitHub account.

* Clone the repository to your local computer.

* Within the repository, create a Jupyter notebook.

* In the notebook write the `hello-world` program that prints the message: “Hello, World! The value of Pi to 16 decimal places is: 3.141592653589793″




&lt;br&gt;




In order to do this you will need to use the `numpy` module in Python as follows:







“`python

import numpy as np

“`







“`python

np.pi

“`













3.141592653589793










You will also want to use a formated string. You can do this as follows:







“`python

print(f”The value of Pi to eight decimal places is: {np.pi : 0.8f}”)

“`




The value of Pi to eight decimal places is:  3.14159265







Notice the “f” at the beginning of the string. I’ll cover strings much more in-depth in future lectures




### Note on Pair Programming




Here is the entry from [Wikipedia on Pair Programming](https://en.wikipedia.org/wiki/Pair_programming#:~:text=Pair%20programming%20is%20an%20agile,two%20programmers%20switch%20roles%20frequently.).




The introductory paragraph from the article is the following:




&gt; Pair programming is an agile software development technique in which two programmers work together at one workstation. One, the driver, writes code while the other, the observer or navigator, reviews each line of code as it is typed in. The two programmers switch roles frequently.




&gt; While reviewing, the observer also considers the “strategic” direction of the work, coming up with ideas for improvements and likely future problems to address. This is intended to free the driver to focus all of their attention on the “tactical” aspects of completing the current task, using the observer as a safety net and guide.




&lt;br&gt;




Pair programming is a very popular methodology used in software engineering and increasingly in data analytics and data science teams. The evidence shows that it helps to produce more correct software more efficiently. The evidence on its use in education is also strong. The consensus view is that it helps students more rapidly integrate the new concepts they are learning and to retain them longer. These two pieces of evidence together lend themselves to highly recommending their use for this course!




&lt;br&gt;




To complete the exercise above using pair programming do the following:




* Choose a student to work first in the role of the _driver_ and the other as the _navigator_. If all else fails – flip a coin.

* The driver will complete the assignment above while the navigator will help guide them through the exercise, help catch errors, and have the written assignment readily at hand to consult.

* When the first student has successfully completed the assignment, switch roles and repeat for the second student.

* Keep a logfile. The logfile should be a plain text file that contains information about the session.




Here is an example log file:




“`

09.09.WE, 9:30a – 11:30a Alan and Jacob, 2 hours

Driver order and time length:

Jacob, 30 minutes

Alan, 30 minutes

Jacob, 30 minutes

Alan, 30 minutes




09.11.FR, 7:00p – 8:30p Alan and Jacob, 1.5 hours

Driver order and time length:

Alan, 30 minutes,

Jacob, 30 minutes

Alan, 15 minutes

Jacob, 15 minutes




09.12.SA 10:30a – 11:20a Alan and Jacob, 50 minutes

Driver order and time length:

Jacob, 20 minutes

Alan, 20 minutes

Jacob, 10 minutes

“`




Your log file should be named `pair_programming_log.md`. Ordinarily for most assignments you will require multiple sessions to complete the assignment. Probably for this particular assignment you will only require a single session. Each student in the pair should hand in a copy of this file separately.




Note: in pair programming the driver and the navigator usually switch every 30 or so minutes.




You may also wish to keep notes in this file at points where you get stuck or have questions. This will make your time with me in office hours much more productive.




&lt;br&gt;