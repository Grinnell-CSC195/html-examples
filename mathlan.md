Preparing your MathLAN Account for the Web
==========================================

Our Web server looks for your Web pages in the directory
`/home/username/public_html`.  It then serves those pages at the URL
`http://www.cs.grinnell.edu/~username/`.  So, if you had a file called
`csc195.html` in that directory, it would be at
`http://www.cs.grinnell.edu/~username/csc195.html`.

- - -

Here are the commands for creating the `public_html` directory and making
it appropriately usable.  Don't type the dollar sign.

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

- - -

Note that we referred to "readable files and directories".  You make a file
readable with `chmod a+r FILE`.
