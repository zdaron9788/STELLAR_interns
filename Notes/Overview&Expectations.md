# Project Overview

We will use data from stars in the Southern Continuous Viewing Zone of the
TESS space telescope to try to measure the rotation periods of those stars.
Our dataset will come in the form of light curves, which is measurements of
the brightness of a star at consistant intervals over a long time period, 
in our case, 351 days. We will need to remove noise from our data signals 
due to the spacecraft's motion, how the instrument operates, and other stellar 
signals. We will need to build a custom moving median function to help us clean 
the data. We will need to stitch together our time series observations for each 
target star. Then we will transform our data with an AutoCorrelation Function to 
detect the periodic signal from rotation. We will use this rotation period to
phase fold our data to verify the signal is due to rotation. If we do this 
for enough stars (some will not have measurable signals) then we can use this
catalog as a training set for machine learning. If not, we will use another
available catalog from the Kepler telescope. Regardless of the training set we use, 
we will learn the machine learning method of random forest to have the computer
decide if we are likely to be able to measure a rotation period from looking at 
the initial light curve before processing.








# Internship Expectations

Please cc drowland@amnh.org for all anticipated absences/lateness.

1. Be present and active from 4:30pm-6:30pm on Tuesdays/Thursdays
2. Every Tuesday a pull must be made to download that week's syllabus
3. One person speaks at a time, everyone's voice is valuable
4. Ask for help!
5. Please no cell phones unless its an emergency
6. Clean up after yourself - our use of the Perkins Room is a privilege. 
7. Take a bathroom break whenever you need one (just let us know you're stepping out)
8. Put a post it on the top of your computer screen if you get stuck
9. An exit survey is required at the end of every session