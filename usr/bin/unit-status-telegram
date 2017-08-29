#!/bin/bash

UNIT=$1

UNITSTATUS=$(systemctl status $UNIT)
ALERT=$(echo -e "\u26A0")

telegram "$ALERT Unit failed $UNIT $ALERT
Status:
$UNITSTATUS"
