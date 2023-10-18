# Secure-Event-Triggered-Distributed-Kalman-Filters
## Secure Event-Triggered Distributed Kalman Filters for State Estimation Over Wireless Sensor Networks

### [Link to paper](https://ieeexplore.ieee.org/abstract/document/9851668)

#### Authors: Aquib Mustafa, [Majid Mazouchi](https://majid-mazouchi.github.io/), Hamidreza Modares
### Abstract
In this article, we analyze the adverse effects of cyber–physical attacks as well as mitigate their impacts on the event-triggered distributed Kalman filter (DKF). We first show that although event-triggered mechanisms are highly desirable, the attacker can leverage the event-triggered mechanism to cause nontriggering misbehavior, which significantly harms the network connectivity and its collective observability. We also show that an attacker can mislead the event-triggered mechanism to achieve continuous-triggering misbehavior, which not only drains the communication resources but also harms the network’s performance. An information-theoretic approach is presented next to detect attacks on both sensors and communication channels. In contrast to the existing results, the restrictive Gaussian assumption on the attack signal’s probability distribution is not required. To mitigate attacks, a meta-Bayesian approach is presented that incorporates the outcome of the attack detection mechanism to perform second-order inference. The proposed second-order inference forms confidence and trust values about the truthfulness or legitimacy of sensors’ own estimates and those of their neighbors, respectively. Each sensor communicates its confidence to its neighbors. Sensors then incorporate the confidence they receive from their neighbors and the trust they formed about their neighbors into their posterior update laws to successfully discard corrupted information. Finally, the simulation result validates the effectiveness of the presented resilient event-triggered DKF.

### Overview figure
![Overview](https://github.com/majid-mazouchi/majid-mazouchi.github.io/blob/main/assets/img/SecEvKalPrj.png)

### Algorithm 1 Detecting Attacks on Sensors
![algorithm](https://github.com/majid-mazouchi/majid-mazouchi.github.io/blob/main/assets/img/Alg1SecEventDKF.png)

