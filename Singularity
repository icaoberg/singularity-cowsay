Bootstrap: docker
From: ubuntu:16.04

IncludeCmd: yes

%labels
    AUTHOR icaoberg
    EMAIL icaoberg@alumni.cmu.edu
    WEBSITE http://linus.cbd.cs.cmu.edu
    
%runscript
    exec /bin/bash "$@"

%environment
    export LC_ALL=C
    export PATH=/usr/games:$PATH

%post
    /usr/bin/apt-get update
    
    if [ ! -d /images ]; then mkdir /images; fi
    if [ ! -d /projects ]; then mkdir /projects; fi
    if [ ! -d /containers ]; then mkdir /containers; fi
    if [ ! -d /share ]; then mkdir /share; fi
    if [ ! -d /scratch ]; then mkdir /scratch; fi
    if [ ! -d /webservers/pfenningweb ]; then mkdir -p /webservers/pfenningweb; fi

####################################################################################
%appinstall cowsay
    /usr/bin/apt-get -y install cowsay

%appenv cowsay
    APP=cowsay
    export APP

%apphelp cowsay
    For more information visit https://en.wikipedia.org/wiki/Cowsay

%apprun cowsay
    cowsay "$@"
