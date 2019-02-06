This repository contains the code for the website required for my CS105 class.

#

The following is just to help me remember the steps:

To SSH into the server, only while connected to the university network:

    ssh -Y UNR\\bmonaco@compute0.cse.unr.edu

Enter your net ID password.

To add changes made to UNR-hosted site, use the following commands:

    cd public_html/
    rm -r index.html
    wget https://raw.githubusercontent.com/BryceDMonaco/CS105Site/master/index.html