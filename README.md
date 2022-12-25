# TCP - CongestionControl -c
third assignment in "Computers Networking" course at Ariel University. 
Project partner - lior vinaman: https://github.com/liorvi35
## Description
In this Ex we wrote two program files: Sender.c and Receiver.c. The Sender will send a file (which is at least 1MB) and the Receiver will receive it and measure the time it took for his program to receive the file. The file will be sent in two parts (first half and second half – Each half should be 50% of the file). Each half will be sent using reno and cubic CC algorithms respectively. The Sender can send the file multiple times, to create a data set of the efficiency of each of the CC algorithms and the efficiency of the pipeline itself. To see how the TCP protocol handles the packet loss with each CC algorithm, we use the packet lost tool that linux have via the iproute package. In this Ex we will use the packet lost tool in the following levels: 0% lost, 10% lost, 15% lost and 20% lost.

