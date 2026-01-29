

This is the repository for the Vrangesync Officialtoolbox for public learning and school .

https://www.1range1.com

VRangeSync is a command-line utility which copy and move data from one location to another on a storage device. It is a data migration, cloner, file replication and synchronization software. VRangeSync is able to provides four-ways sync. It aims to be your system 'Swiss Army knife', handling a wide variety of data security backup and administration tasks. It include  deltacopy algorithm that transfer new changes without copy the whole file (eg. transfer only 3GB of new data out of the 2TB file) .  It support resume of partial file transfer. It had the ability to 'move' files within 'Destination machine' which skip the hassle of transfer the same file again. It significantly reduces the costs and technical expertise required to manage data migration activities. Through automation, you can dramatically reduce administration time. Every single features found on vrangesync are free for public use. Advanced feature are for commercial entity only. For more indepth details what vrangesync offer, visit official vrangesync site.


Individual, student and startup that like to keep cost within your budget, feel free to get our free version of the Free system sync,clone,mover tool at - Free system sync,clone,mover tool.
https://www.1range1.com/free.php



What's Included
============================================

The repository contains the following items. Each of which is explained in further detail below:

    -A collection of static binary files(64bit) for 32bit and 64bit unix/linux machine
    -Vrangesync startup script (vr) with 'autoview log' feature
    -An example how to use Vrangesync startup script (vr), a wrapper to run the 'vrex' 
  

A collection of static binary files
=============================================

What are 'static binary' file?
------------------------------
It is an independent, standalone executable file which can be startup from any 32bit/64bit unix/linux system. It do not require any dynamic loader or library.
Vrangesync officialtoolbox include static binary files that can be run from any 32bit/64bit unix/linux distro system such as debian, alpinelinux, opensuse, gentoo etc
Think it like 'swiss toolbox' where you can bring it anywhere and use it for your own work.


'xxh' file contain xxhsum calculation of the static binary files ($ xxhsum -H2 )

$ xxhsum -H2 utilities.tar.xz
181d68cdf7143c0b62efa11ebce01f1e  utilities.tar.xz

Vrangesync officialtoolbox include static binary files for your project and school
------------------------------

It is recommend to validate the checksum before using them.

1110213de142270b4160c7cedaa8429c  awk

4df7e43e97c1dde65d9aa0affbe646c5  base64

1020568c9064fcb662bbbb13be3413de  bash

14e2c7fe6175cd172ee45a267e5090e9  cat

0a4270b4f68e40fb823123f62bae3121  chmod

d31261f511ca5227f7970bf192dd4493  chown

0b3d1f84607f85f2435713e93a155235  comm

8508c9b5a769d1a968760b27ec618b53  date

14e7252aba9c95b016d9801c5a51d083  dd

73f5a92e850ebff9b50849f1dcc0735e  dirname

88be0cdd3ec079fee6bedbe98de6fa24  du

dffbab30efe10b94eb92af4dae1077d8  echo

c09ce3b1736f8d34d3cd0876f21afd46  find

c9f864d0e9624a9b0c799fd51df45aa2  gpg

06da328094fc65f7f504585acfcb10c9  grep

5a1f604b253f28e96e4ddb591e2764bf  head

350911f3cc31f4250edd712705ac54f6  ifconfig

86872e5500b36eab83f633dfeba98689  ip

a257690aec46a1e6d5bdeabcd232b7f6  kill

471fdc06b1db0d4bd9328807acb5fd5d  ls

273f6e1bd41c445cb8e18f53107a64be  lz4

575025dd1c7139c0cdd31fd04d373e6d  md5sum

52c5e8cd6fd37ef94393f15a71ac5f22  mkdir

d106c34e94962e6f376b4895848a5f86  mkfifo

7105c89bfe1e6dd721db7a127af38544  mv

4f7ce424bd78a9a27225a02da75f9878  ncat

8347649f0b03d40e44a56ddc45237c5c  numfmt

9095a5369de4a1f51f6707eb9ddb3ca0  openssl

165933130cff92ed134d1817f30cbb2d  pgrep

b6f502f217f256d6ae443028faf8c78b  pigz

165933130cff92ed134d1817f30cbb2d  pkill

4712b44d9fb8f1427c81973ca335f2a3  printf

f1483151d32b8671795dd1e21a2d5aaa  rm

54de2e82f8509d1a6c1d15fb1265de69  screen

8083a100a600b430252209b54685f0ab  sed

847bb590283ca4f8ff29fab6a735e949  shuf

f7086cca57d0fa358455ea593c9218c9  sleep

1b2267c59e6b4ba99afd8029fa42fcca  sort

01faa0757a9dd71ef3c9b7c3543a00f2  stat

0352ada1937033d606d122fa8e71f958  tail

5a246c0305ad179fc219f6935f6f14eb  tar

d0bd9ada73137d2ade81782bd08c8f42  touch

aa633467788a713b4180eb06e933e370  tr

13d9239bc118d6c05358a936a6bc2bff  uname

99c622dee9b44f4c7c48b4f4a9ec72f7  wc

f5ab482b4a12e662071726611ec6170f  wget

e0aea2d4ad96533bffbee4fd39fee778  whoami

e2f1e0fcdf3032af16a642bd56b2f5f2  xargs

0b261acf8611e3149c3a1dc01c6418d2  xxhsum

18236ad05458e785d4768e65005566b2  zstd



Vrangesync startup script(vr) with 'autoview log' feature
=============================================
Official executable file is 'vrex' . vr is a wrapper for 'vrex' which include 'autoview log' which allow operator to review activity while vrangesync is running.

An example how to use Vrangesync startup script (vr)
=============================================
./vr -i "/path/inputfile" -o "/path/outputfile"

./vr -i "/path/inputdirectory" -o "/path/outputdirectory"


Links
==========

lz4(include multi-threads) (https://github.com/lz4/lz4  developed by Yann Collet & 'multi-thread edition' developed by T-mat https://github.com/t-mat)

zstd (include multi-threads) (https://github.com/facebook/zstd  developed by Yann Collet)

ncat - nmap official ncat (different from the 'netcat' found on the internet) (https://github.com/nmap)

xxhsum(xxhash) - One of the fastest checksum calculation tool on the market developed by Yann Collet(https://github.com/Cyan4973)

pigz(include multi-threads for gzip) (https://github.com/madler/pigz developered by Mark Adler)


xz - An impressive data-compression command-line tool.(you can download static binary from another link)  (https://github.com/tukaani-project/xz)


