# Peer-to-Peer-Massage-Sharing
Compile as -

gcc receiver.c -o receiver
gcc sender.c -o sender

Run as -

./receiver 3344
./sender 3344 "Massage by sender"

here the receiver listning on port 3344, and it will receive massage from sender by 1st command.

accordingly sender will send massage on port 3344 by 2nd command.

----
Department Socket Programming
