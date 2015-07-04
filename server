echo "--------------"
echo "Launching"
echo "Renegademiners"
echo "Please Wait"
echo "--------------"
sleep 3
#!/bin/sh
BINDIR=$(dirname "$(readlink -fn "$0")")
cd "$BINDIR"
while : ; do
echo "Starting ... Updating server !"
cd /home/MASTER/Exemple/plugins
scp plugin.jar /home/Exemple/plugins/
sleep 2
java -Xms128M -Xmx128M -jar spigot.jar nogui
echo "Restart after 5 seconds"
sleep 1
echo "Restart after 4 seconds"
sleep 1
echo "Restart after 3 seconds , or press Ctrl+c"
sleep 1
echo "Restart after 2 seconds"
sleep 1
echo "Restart after 1 seconds"
sleep 1
done
