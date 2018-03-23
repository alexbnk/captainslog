#!bash

TEXT=$@

NOW=$(date +"%m-%d-%Y %T")

INSERT=$NOW" - "$TEXT

if  [ -n "$TEXT" ]
        then
echo "$INSERT" >> /var/log/captain.log

fi

if [ -z "$TEXT" ]
                then
more /var/log/captain.log
fi

~  
