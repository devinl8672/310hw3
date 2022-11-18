# 310hw3

The servers that I used to test my program with are:
* Beijing: 47.94.129.116
* Tel Aviv: 185.229.226.83
* Brisbane: 223.252.19.130
* Amsterdam: 95.142.107.181
* stonybrook.edu: 172.30.32.25
* cs.stonybrook.edu: 23.185.0.2

Instructions to run program
1. Navigate to the correct directionary where the pinger.py file is located.
2. Run the program by executing the command "sudo python3 pinger.py <server address>", the command might use python instead or python3 depending on how your device is configured, replace <server address> with the server that you are trying to reach. I listed above a few servers that worked for me including overseas servers.
3. All the program to the connect to the server and print out the replies it get back, after about 4-5 replies you can feel free to terminate the program, use ctrl c
4. After terminating the program the program should print out statistics, this includes the minimum, maximum, and average round trip time

There is a noticable difference in the RTT of trying to ping localhost, stony brook's website, and the 4 overseas servers. This can be explained through their distance from me. The further the server from me the longer the RTT is. For example the average RTT for localhost is 0.1 ms, meanwhile the average RTT
