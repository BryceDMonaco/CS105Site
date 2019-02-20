This repository contains the code for the website required for my CS105 class.

#

The following is just to help me remember the steps:

To SSH into the server, only while connected to the university network:

    ssh -Y UNR\\bmonaco@compute0.cse.unr.edu

Enter your net ID password.

To add changes made to UNR-hosted site, copy/paste the following commands in the root directory:

    rm -r public_html/*
    wget https://github.com/BryceDMonaco/CS105Site/archive/master.zip
    unzip master.zip
    mv CS105Site-master/* public_html/
    rm -r master.zip
    rm -r CS105Site-master/

