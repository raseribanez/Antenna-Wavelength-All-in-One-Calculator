# Antenna-Wavelength-All-in-One-Calculator
Before I knew how to do this, I did each calculator seperately. Now they are merged into 1

Written in Python and Tkinter

This app will allow you to enter a Radio frequency
And it returns a Length, or Vertical Wave Length. To be used as a rough guide for antenna design across frequencies.

No additional modules needed

When I get this completed I will look at something like py2exe to make it distributable to non-python users as-well

Where I am so far:
------------------
Each size ratio used to be a seperate program. I figured out how to assign different calculations to functions, then assign the different functions to each button.

NOTE I tested the output against online wavelength calculators and it seems safe to say it is accurate.
I haven't fully tested how many decimal points you can really try, but it will be as accurate as the data you enter - if you really want to try it out you cuold enter something like 1.9999999999 and I am confident it would work.


What I have left to do:
-----------------------

* Package as an exe for non-Python users
* Merge METERS and FEET into the 1 app

(As it is now, ALL of the meters and feet calculations are programmed into functions, but only the meters are assigned to the buttons. I wanted to put a checkbox or radio box for the meters or feet selection, this proved a bit awkward for my level of knowledge in Tkinter, so my plan is to just have BOTH values returned to the cvt_to.set label somehow.

Problem is, I can't assign 2 functions to one button, and having different buttons would double up on the total so far which would get a bit cramped...so I am going to have a mess around and if I come up with something I wil update this version.

I thought maybe having the result in Meters as it is already...then having one other button for "convert result to feet" and do it that way. Here it is anyway, if you wanted you could rearrange the functions to the feet calculations - as I said, both sets of calculations for each size ratio are written into their own functions.)
