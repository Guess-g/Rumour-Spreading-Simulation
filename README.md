# Rumour-Spreading-Simulation
So basically...I was trying to apply for the Princeton Math Program until I realised, wait, that's expensive! And between when I started and when it was due, I didn't have enough time to build a convincing application.
Anyway, before giving up, I created a simulation in response to one of the application questions. 
The question goes as follows:

"A single person in a group of N people starts a rumour. The rumour spreads day by day according
to the following rule:
On each day, every person who currently knows the rumour independently picks one
other person in the group, chosen uniformly at random, and tells them. Anyone told
the rumour now knows it (and starts spreading it the next day); telling someone who
already knew it has no further effect.

Write a Python program that models this process, and use it to answer the following:

(a) Estimate the average number of days it takes for the entire group of N = 100 people to
learn the rumour. (You will need to run the simulation many times and average; explain
how many runs you used and why you trust the estimate.)

(b) Investigate how this average number of days grows as the group gets larger — for example
at N = 100, 1000 and 10,000. Describe the pattern you observe as clearly as you can, and
give an intuitive explanation for why the number of days grows the way it does rather than,
say, in proportion to N."

I wasn't going to post this, but apparently it's a simplistic example of "network simulation", so I guess it must count for something.
