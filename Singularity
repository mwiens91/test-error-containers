Bootstrap: debootstrap
OSVersion: xenial
MirrorURL: http://us.archive.ubuntu.com/ubuntu/

%files
    error_raise.py /error_raise.py

%post
    apt-add-repository universe
    apt-get update
    apt-get install python

    cd /
