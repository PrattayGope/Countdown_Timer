# Countdown_Timer
It is the Repository to store my project on Countdown Timer using Python.
Step by Step Approach:
1. Import the time module using import time
2. Get User Input for Countdown Duration(in Seconds)
3. Convert input to integer(as input() returns as string)
4. Define a function Countdown(t) to perform countdown
5. Use a while loop to run the countdown until t reaches 0.

6. Inside the loop:

a. Use divmod(t, 60) to convert seconds to minutes and seconds.
b. Format the time string using '{:02d}:{:02d}'.format(mins, secs).
c. Print the time on the same line using end='\r' to overwrite the previous output.
d. Pause the loop for 1 second using time.sleep(1).
e. Decrease t by 1 each iteration.
7. After the loop finishes, print "Fire in the hole!!" to indicate the timer has ended.
