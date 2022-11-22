Devin Lin
113503586
Programming Homework 3

The servers that I used to test my program with are:
* Local Host: 127.0.0.1
* stonybrook.edu: 172.30.32.25
* cs.stonybrook.edu: 23.185.0.2
* Buenos Aires, Argentina: 131.255.7.26
* Frankfurt, Germany: 195.201.213.247
* Shen Zhen, China: 47.119.149.69
* Brisbane, Australia: 223.252.19.130
Most of the servers I got from https://www.dotcom-monitor.com/blog/technical-tools/network-location-ip-addresses/

Instructions to run program
1. Navigate to the correct directory where the pinger.py file is located.
2. Run the program by executing the command "python3 pinger.py **[server address]**", the command might use python instead or python3 depending on how your device is configured, replace **[server address]** with the server that you are trying to reach. I listed above a few servers that worked for me including overseas servers. Also on Mac I had some permission problems but was able to fix it by running "sudo python3 pinger.py **[server address]**", this may not be necessary if you aren't on mac
3. Allow the program to connect to the server and print out the replies it get back, after about 3-5 replies you can feel free to terminate the program, use ctrl c
4. After terminating the program the program should print out statistics, this includes the minimum, maximum, and average round trip time

**Part D:**
There is a noticable difference in the RTT of trying to ping localhost, stony brook's website, and the 4 overseas servers. This can be explained through their distance from me. The further the server from me the longer the RTT is. For example the minimum RTT for localhost is 0.082 ms, meanwhile the minimum RTT for pinging stonybrook.edu is 5.773 ms and the minimum RTT for pinging Shen Zhen, China is 252.919 ms. Since localhost is where I'm sitting it's the closest with stonybrook.edu located nearby since I'm on campus and the server in Shen Zhen China being around the world, it takes the longest about of time to send and receive a request. 