# Low-Latency-Low-Loss-and-Scalable-Throughput-L4S-

This repository contains work done under Prof. Shivendra Panwar and Prof. Fraida Fund during my on-site summer research internship at New York University.
<br><br>
In this project, I analysed the performance of various TCP congestion control algorithms like TCP Reno, TCP Cubic, TCP Vegas. I also conducted experiments to analyse the performance when a loss based algorithm (like TCP Reno) and delay based algorithm (like TCP Vegas) coexist in a network. 
Then I replicated the following 4 scenarios and analysed the performance and shortcomings of each scenario which led me to the next scenarios.
![image](https://github.com/Mohak-Singh-Rana/Low-Latency-Low-Loss-and-Scalable-Throughput-L4S-/assets/107363735/9d85c7e0-33d7-41bb-8e46-55e808280bef)
I focused on each of the component of L4S (scalable sender and Enhanced ECN / AccECN), how they work and how they are solving the problems faced by the previous scenarios. I also briefly went over Dual Queue Coupled AQM to understand how L4S traffic coexists with the classic traffic.
