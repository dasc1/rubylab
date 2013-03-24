Challenge: zz_helloworld

INSTALLATION - UBUNTU LINUX

Ruby is undoubtedly available in the apt-get packages.  You can simply
apt-get install the "ruby" package, but this may give you an older
version that you don't want.  To ensure that you get version 1.9.3,
for example, try:

>>> sudo apt-get install ruby1.9.3

When the installation script finishes, you can type the following
command to see what version of ruby you have installed:

>>> ruby --version

RUNNING THE COMMAND IN THE REPL

Since the helloworld program is a one-liner, you can execute it from
Ruby's REPL.  This is installed when you install the main ruby
program - run it from the command line with "irb".

To run the program, simply type the following line:

  irb(main):001:0> puts "Hello, World!"

You can also run the program from the command line.  In this folder,
there is a ruby script called "helloworld.rb".  Run it by opening
a terminal in this directory, and typing:

>>> ruby helloworld.rb

