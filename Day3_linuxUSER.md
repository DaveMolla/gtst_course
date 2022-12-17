# Linux For User
1. Tools for Information gathering :- nmap, legion...
2. Tools for Vulnerability Analysis :- nmap, Legion...
3. Tools for Web Application Analysis :- wpscan, httrack...
4. Tools for Database Assessment :- sqlmap, oscanner...
5. Tools for Password Attacks :- crunch, ncrack...
6. Tools for Wireless Attacks :- chirp, kismet...
7. Tools for Revesre Engineering :- apktool, ghidra...
8. Tools for Exploitation :- armitage, searchsploit...
9. Tools for Sniffing & Spoofing :- driftnet, hamster...
10. Tools for POST exploitation :- powersploit, weevely...
11. Tools for Forensics :- autopsy, binwalk, foremost...
12. Tools for Reporting preparation:- cutycapt, pipal... 
13. Tools for Social Engineering :- maltego,
14. Tools for System Services :- beef start, beef stop, dradis start, dradis stop
15. Softwares for some basic purpose :-programming, system tools...

# Folder MAnagers
1. Dolphin
2. Thunar
3. Nautilus

# Linux Commands
- Linux system uses shell. The shell help us to Communicate with the kernel and helps to execute codes.
- Shell is called "Terminal"
* the terminal has 5 parts
      - Username
      - Hostname
      - Current Directory
      - Priviledge and
      - Command Place
## linux command basics
* On linux ther are over 100 commands.
* Also those commands have their own options and arguments.

## What is command
- Small Programs that do one task well.
     - ls [Option]...[FILE]... :- List information about the Files(the current directory for default).
         - ls -l :- list
         - ls -a :- shows the hidden files
         - ls -R :- recursive
     - cd change directory :- used to change the current working directory
     - cd / root
     - cd home
     - cd .. 1x back
     - cd ../.. 2x back
     - cd foldername, if folder name have a space we use quotation 
     - cd "folder name"
     - pwd prints name of the working directory
     - echo used to display text/string that are passed by the argument
     - echo "text" > file.txt writes text into files
     - echo "text" >> file.txt appends (add) texts
     - cat -> opens file eg :- cat file.txt
     - touch creats any kind of file with the name we gave eg:- touch code.py
         - eg :- touch [File1][File3][File3]
     - mkdir :- creates a folder with the name we gave 
     - clear clears your screen
     - rm removes file
         - rm [File1][File2][File3]
         - rm -r recursive (for folders)
         - rm -i for prompt(ask)
         - rm -f force delete
         we can combine them like
         - rm -rf
     - cp copy the file or folder
         - [oldfileplace][newfileplace]
     - mv move the file or folder
         - [filename][newfileplace]
     - grep global search for regular expressions
         - grep [options]pattern[files]
         - grep "my" grep text.txt highlites only the word my in text.txt file
         - grep -i "search" file :- case insensitive
         - grep -c "search" file :- count numbers
         - grep -l "search" * :- displays filename
         - grep -R "search" foldername :- search text in folders
     - wc word count
         - wc [Option]...[File]...
         - -l :- line
         - -w word
         - -c byte
         This finds out number of lines word count in the text and byte of the file
    ## Multiple commands 
    ### We can ran multiole commands
    - AND (&)
    - OR (||)
    - pipeing (|)
    ## AND (&)
    - On AND all will be executed If both the conditions are working without error
    ## OR(||)
    - On OR the command will be executed if it have error or not.
    ## Pipeing (|)
    - Will help you run commands by using the output of the first command as the inout for the next one.
     