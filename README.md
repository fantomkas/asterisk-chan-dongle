Installation
apt-get install linux-headers-`uname -r` gcc g++ make libnewt-dev libncurses5-dev openssl libssl-dev zlib1g-dev
cd asterisk-chan-dongle
aclocal && autoconf && automake -a
