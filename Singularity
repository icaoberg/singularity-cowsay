Bootstrap: docker
From: ubuntu:16.04

IncludeCmd: yes

%runscript
    exec /bin/bash "$@"

%environment
    export LC_ALL=C
    export PATH=/usr/games:$PATH

%post
    /usr/bin/apt-get update && /usr/bin/apt-get -y upgrade
    /usr/bin/apt-get install -y build-essential

%appinstall cowsay
    /usr/bin/apt-get -y install cowsay

%appenv cowsay
    APP=cowsay
    export APP

%apphelp cowsay
    For more information visit https://en.wikipedia.org/wiki/Cowsay

%apprun cowsay
cowsay "$@"
