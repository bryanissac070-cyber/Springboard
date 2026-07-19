bryaniss@DAL3-4ISX1CVMR4 :~ $ mkdir first
bryaniss@DAL3-4ISX1CVMR4 :~ $ cd first
bryaniss@DAL3-4ISX1CVMR4 :~ /first$ touch person.txt
bryaniss@DAL3-4ISX1CVMR4 :~ /first$ mv person.txt another.txt
bryaniss@DAL3-4ISX1CVMR4 :~ /first$ ls
another. txt
bryaniss@DAL3-4ISX1CVMR4 :~ /first$ cp another.txt copy.txt
bryaniss@DAL3-4ISX1CVMR4 :~ /first$ ls
another.txt copy. txt
bryaniss@DAL3-4ISX1CVMR4 :~ /first$ rm copy.txt
bryaniss@DAL3-4ISX1CVMR4 :~ /first$ ls
another. txt
bryaniss@DAL3-4ISX1CVMR4 :~ /first$ cd .
bryaniss@DAL3-4ISX1CVMR4 :~ /first$ cd ..
bryaniss@DAL3-4ISX1CVMR4 :~ $ cp first second
cp: -r not specified; omitting directory 'first'
bryaniss@DAL3-4ISX1CVMR4 :~ $ cp -r first second
bryaniss@DAL3-4ISX1CVMR4 :~ $ ls
Project first folder1 second
bryaniss@DAL3-4ISX1CVMR4:$ rm -rf second
bryaniss@DAL3-4ISX1CVMR4 :~ $ ls
Project first folder1

man command shows the manual, manual rm opens manual for rm you press arrow up or down and quit with a q
-l     use a long listing format, -a, --all
ctrl + arrow
ctrl + e
ctrl + a
alt + delete (backspase)
terminal is the window yoy type in and the sheel is the program running inside that window
An absolute path is the full address of a file
A relative path is the direction path to the file you are currently at and not the entire (absolute) path
A flag is an additional functionallity you can add to an existing command
r removes folders and everything in them, and f is a force to delete without confirmation 
