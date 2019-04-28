# Codepath Honeypot (Project 9)
Honeypot Project for Codepath


# Type of Honeypot
Dionaea over HTTP: a low interaction, server side honeypot that tries to trap malware samples.


# Issues encountered
In general, there weren't any issues for creating this honeypot. I would say that the only thing to slow me down was waiting for attackers/IP Scanners to actually try to access my honeypot.

# Summary of Data Collected
Number of Attacks in the past 24hrs: 224 attacks

# Top 5 Attacker IPs
1.  150.109.33.119 (146 attacks) -- Singapore, Income at Raffles, Tencent Building, Kejizhongyi Avenue (known Internet      
    Scanner)<br>
2.  39.108.133.190 (9 attacks) -- China, Aliyun Computing Co., Hangzhou Alibaba Advertising Co.,Ltd. <br>
3.  5.188.210.101 (7 attacks) -- Russian Federation, Petersburg Internet Network ltd. (self-signed) <br>
4.  185.254.122.33 (4 attacks) -- Lithuania, Arturas Zavaliauskas (observed scanning the internet) <br>
5.  178.128.122.110 (2 attacks) -- Netherlands, Digital Ocean (cloud) <br>
(all above information about IPs was taken from [Shodan](Shodan.io))

# Top Attacked Ports
1. 80 (186 times)
2. 3389 (31 times)
3. 10000 (5 times)
4. 3000 (2 times)

# Unresolved Questions Raised by Data Collected
1. Why are well-known companies, like Alibaba Advertising, scanning random IPs? <br>
2. Which of these 224 attacks actually contain malware? Or are they all just internet scanners? I wish that there was more
   information at my disposal.
