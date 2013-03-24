Challenge: zz_repl

INSTALLATION - UBUNTU LINUX

Ruby is undoubtedly available in the apt-get packages.  You can simply
apt-get install the "ruby" package, but this may give you an older
version that you don't want.  To ensure that you get version 1.9.3,
for example, try:

>>> sudo apt-get install ruby1.9.3

When the installation script finishes, you can type the following
command to see what version of ruby you have installed:

>>> ruby --version

RUNNING COMMANDS FROM THE REPL

To invoke the repl, type "irb" from the command line.

To perform the calculation, simply type:

  irb(main):001:0> 2 + 3
