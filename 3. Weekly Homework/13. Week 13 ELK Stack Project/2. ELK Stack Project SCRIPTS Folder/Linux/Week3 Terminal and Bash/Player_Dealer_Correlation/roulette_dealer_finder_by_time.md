#!/bin/bash

#Design the shell script to accept the following two arguments: 1) one for the date (4 digets) 2) one for the time.

#awk '{print $1, $2, $5, $6}' $1_Dealer_schedule | grep '$2'

#cat $1_Dealer_schedule | awk '{print $1, $2, $5, $6}' | grep "$2"

cat $1_Dealer_schedule | awk '{print $1, $2, $5, $6}' | grep "$2"



