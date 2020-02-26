Bootstrap: docker
From: debian:latest

%labels
    AUTHOR icaoberg
    EMAIL icaoberg@alumni.cmu.edu
    WEBSITE http://linus.cbd.cs.cmu.edu
    
%environment
    export LC_ALL=C
    export PATH=/usr/games:$PATH

%post
    apt-get update
    
####################################################################################
%appinstall cowsay
    apt-get -y install cowsay

%apphelp cowsay
    For more information visit 

    * https://en.wikipedia.org/wiki/Cowsay

%apprun cowsay
    cowsay "$@"
