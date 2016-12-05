FROM docker/whalesay:latest
RUN apt-get -y update && apt-get install -y fortunes

RUN apt-get -y install git gawk wget git-core diffstat unzip texinfo gcc-multilib g++-multilib build-essential chrpath libsdl1.2-dev xterm gyp
RUN apt-get -y install build-essential emacs subversion openssh-server gparted  python-scipy python-matplotlib libsamplerate0-dev python-pip python-opengl buildbot buildbot-slave python-qt4-gl python-tk libsndfile-dev libncurses5-dev libusb-1.0-0-dev libmicrohttpd-dev libasound-dev fftw3-dev subversion screen valgrind
RUN apt-get -y install tightvncserver
RUN apt-get -y install openssh-server
RUN apt-get -y install gdb
RUN adduser caleb --disabled-password 
# CMD /usr/games/fortune -a | cowsay
