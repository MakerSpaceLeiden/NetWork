# NanoBSD for FreeBSD 11.1


Put these files in /usr/src/tools/tools/nanobsd/

mkdir /data/nano or change config

pkg install screen

and run:

screen sh nanobsd.sh -c msl.conf 

or later 

screen sh nanobsd.sh -b -c msl.conf

dd if=/data/nano/_.disk.full of=/dev/da<x> bs=64k  

See more details here

http://makerspaceleiden.nl/wiki/index.php/NetworkSetup_AP



