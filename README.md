 

#!/bin/bash
mkdir -p /tmp/Julia
touch /tmp/Julia/logo.txt
date >> /tmp/Julia/logo.txt
echo "it works!" >> /tmp/Julia/logo.txt
cp /tmp/Julia/logo.txt /opt


   0 nano script.sh
   1 ls
   2 chmod 700 script.sh
   3 ls -la
   4 ./script.sh
   5 mv script.sh /bin
   6 history
   7 history > /tmp/history.txt
