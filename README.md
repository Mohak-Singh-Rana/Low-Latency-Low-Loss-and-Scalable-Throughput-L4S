# Low Latency, Low Loss and Scalable Throughput (L4S)

**Summer Research Internship at New York University under Prof. Shivendra Panwar and Prof. Fraida Fund**

This repository contains the results of the experiments conducted during my on-site summer research internship at New York University. The project focused on analyzing the performance of various TCP congestion control algorithms and exploring the Low-Latency Low-Loss Scalable Throughput (L4S) framework.

## Project Objectives
- **Analyze TCP Congestion Control Algorithms:** Evaluate the performance of TCP Reno, TCP Cubic, and TCP Vegas, including their behavior in network scenarios.
- **Investigate Coexistence of Algorithms:** Study the performance when loss-based algorithms (like TCP Reno) and delay-based algorithms (like TCP Vegas) coexist in a network.
- **Evaluate L4S Components:** Examine how L4S components, including scalable sender and Enhanced ECN/AccECN, address problems faced in previous network scenarios.
- **Study Dual Queue Coupled AQM:** Understand how L4S traffic coexists with classic traffic using Dual Queue Coupled Active Queue Management (AQM).

## Key Activities
- **TCP Congestion Control Experiments:**
  - Conducted experiments demonstrating AIMD (Additive Increase Multiplicative Decrease), slow start, and the classic sawtooth pattern of congestion window.

- **Performance Analysis:**
  - Analyzed TCP Reno, Cubic, and Vegas individually and in scenarios where they share the same bottleneck router with FIFO queue.
  - Experimented with progressive network scenarios from classic TCP flow to Active Queue Management (AQM) flow (varying ECN threshold) and finally to L4S flow.
  - I replicated the following 4 scenarios and analysed the performance and shortcomings of each scenario which led me to the next scenarios:
  ![image](https://github.com/Mohak-Singh-Rana/Low-Latency-Low-Loss-and-Scalable-Throughput-L4S-/assets/107363735/9d85c7e0-33d7-41bb-8e46-55e808280bef)

- **L4S Flow Analysis:**
  - Demonstrated the scalable sawtooth behavior of L4S and the operation of Enhanced Explicit Congestion Notification (ECN).
  - Examined impacts on latency, bandwidth, and other parameters in networks coexisting of L4S traffic and classic traffic.

