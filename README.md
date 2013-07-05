startup-1
=========

Coursera startup eng. - 1st repo for training

This repo was used to learn how to publish a repo into github using the Linux command line. 
It didn't work so far: 

    ubuntu@ip-10-164-71-197:~/myrepo$ git remote add origin git@github.com:juanlanus/startup-1
    ubuntu@ip-10-164-71-197:~/myrepo$ push -u origin master
    The program 'push' is currently not installed.  You can install it by typing:
    sudo apt-get install heimdal-clients
    ubuntu@ip-10-164-71-197:~/myrepo$ git push -u origin master
    The authenticity of host 'github.com (204.232.175.90)' can't be established.
    RSA key fingerprint is 16:27:ac:a5:76:28:2d:36:63:1b:56:4d:eb:df:a6:48.
    Are you sure you want to continue connecting (yes/no)? y
    Please type 'yes' or 'no': yes
    Warning: Permanently added 'github.com,204.232.175.90' (RSA) to the list of known hosts.
    Permission denied (publickey).
    fatal: The remote end hung up unexpectedly
    ubuntu@ip-10-164-71-197:~/myrepo$ git push -u origin master
    Permission denied (publickey).
    fatal: The remote end hung up unexpectedly
    ubuntu@ip-10-164-71-197:~/myrepo$ 

But it isn't hung: this text was happily added. 
