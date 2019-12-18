#QSDK_5.0.3_IPQ

Introduction
=======================
QSDK for IPQ40xx
https://downloads.pangubox.com/sources/
https://downloads.pangubox.com/lintel/qsdk-5.0.3.zip


Build
=======================
./scripts/feeds update -a
./scripts/feeds install -a -f
cp qca/configs/ipq.config .config
make defconfig
make V=s -j4

