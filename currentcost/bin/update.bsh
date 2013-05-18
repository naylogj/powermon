#!/bin/bash
# script to regenerate all of the graphs

# Change the variables to reflect your install
UDATADIR=~/currentcost

cd $UDATADIR/bin


for i in `ls | grep graph`
do
	echo "Running "$i
	cd $UDATADIR/bin
	. ./$i
	echo "Return Code "$?
done
