How to compile for Miyoo:

export CC=/opt/miyoo-toolchain/bin/arm-buildroot-linux-musleabi-gcc
export CXX=/opt/miyoo-toolchain/bin/arm-buildroot-linux-musleabi-g++
export AS=/opt/miyoo-toolchain/bin/arm-buildroot-linux-musleabi-as
export STRIP=/opt/miyoo-toolchain/bin/arm-buildroot-linux-musleabi-strip
./configure --platform=miyoo
make
