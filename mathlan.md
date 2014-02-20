Preparing your MathLAN Account for the Web
==========================================

Our Web server looks for your Web pages in `/home/username/public_html`.
Here are the commands for making that directory appropriately usable.
Don't type the dollar sign.

    $ cd
    $ chmod a+x .
    $ mkdir public_html
    $ chmod a+rx public_html

The first command moves to your home directory.

The second command makes it possible for anyone to look at the readable
files or directories in your home directory, provided they know the name
of those files.  (By default, even if the files are readable, people can't
read them.)

The third command creates the `public_html` directory.

The fourth command makes it possible for someone to look at the readable
files and directories within your `public_html` directory.  It also makes 
it possible for them to determine what files you have in that directory.  
(If you don't want the latter behavior, leave out the `r`.)
