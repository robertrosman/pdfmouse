Pdfmouse
========

With Pdfmouse you can easily control your pdfs with only your mouse as a kind of 
remote control. This is handy when you want to take a step back from the 
computer, or just don't want to reach for the keyboard every now and then. Use 
the scroll wheel as usual, scrolling the pdf up and down, *but also* move the 
pdf sideways by clicking the left and right buttons.  

Usage
-----

Open your pdf. Run the command `pdfmouse` and the focus will switch to the pdf 
(hopefully). Now the left and right buttons on the mouse will act as the left 
and right arrow keys, and thus scroll the pdf horizontally. Ctrl + scroll wheel 
will zoom in and out in most pdf viewers.

To make the mouse buttons function as you're used to, press ctrl as you click.

Whenever your want to exit the application, and get your good old mouse behave 
as intended, press `ctrl` + `alt` + `c`.


Installation
------------

First make sure you have the dependencies installed:

  * Xbindkeys
  * Xautomation
  * Wmctrl

Next, open a terminal, cd to the folder where you've cloned this repo, or 
unpacked the archive containing these files. Run these commands:

    ln -s $(pwd)/xbindkeys-pdfmouse ~/.xbindkeys-pdfmouse
    sudo ln -s $(pwd)/pdfmouse /usr/local/bin/pdfmouse

Licence
-------

[MIT](http://en.wikipedia.org/wiki/MIT_License)
