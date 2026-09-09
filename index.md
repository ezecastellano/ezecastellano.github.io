# Ezequiel Castellano, Ph.D.

Senior Research Engineer at Woven by Toyota with experience in both industry and academia spanning software engineering, formal methods, scenario-based testing, machine learning safety, and LLM engineering with a track record of academic-industry collaborations and bringing research outcomes into production. 

[Google Scholar](https://scholar.google.com/citations?user=41tcnMQAAAAJ&hl=en) | [LinkedIn](https://www.linkedin.com/in/ezequiel-castellano-phd/)

---

## Publications

### 2023

**Incremental search-based allocation of autonomous robots for goods delivery**<br>
Paolo Arcaini, **<u>Ezequiel Castellano</u>**, Fuyuki Ishikawa, Hirokazu Kawamoto, Kaoru Sawai, Eiichi Muramoto<br> 
*IEEE Congress on Evolutionary Computation (CEC)*<br>
[[PDF](/assets/pdfs/CEC2023_IncrementalSearch.pdf)] [[Publisher Link](https://doi.org/10.1109/CEC53210.2023.10254103)]
<details markdown="1"><summary>Abstract & BibTeX</summary>

**Abstract:** Autonomous robots can solve different issues of delivery services, by guaranteeing less traffic congestion, less pollution, and lower operational costs. Designing such type of delivery system based on autonomous robots requires the collaboration of different stakeholders, having different concerns: the store utilising the delivery service that is interested in costs and customer satisfaction, the municipality where the service is operated that is interested in the safety of the service, and the robotic company providing the service that is interested in all previous concerns. Our industrial partner from the robotic domain is designing this type of service in a smart town, and using a simulator for assessing different configurations providing different levels of performance. Since manually designing the configurations is time consuming for engineers, in this paper, we propose a search-based approach (All) that is able to explore the space of service configurations and find the optimal ones that show the tradeoff existing among the different concerns, so that stakeholders can make an informed decision. Since assessing one configuration requires to simulate the service multiple times over different types of customer requests, the approach suffers from scalability issues. Therefore, we propose two improvements of the approach that reduce the number of required simulations (IncrSim), and the duration of the simulation (IncrTime). Ex-periments on different settings show that IncrSim and IncrTime can find results as good as those of All in less time, and better than versions of All executed for the same budget.

```bibtex
@INPROCEEDINGS{10254103,
  author={Arcaini, Paolo and Castellano, Ezequiel and Ishikawa, Fuyuki and Kawamoto, Hirokazu and Sawai, Kaoru and Muramoto, Eiichi},
  booktitle={2023 IEEE Congress on Evolutionary Computation (CEC)}, 
  title={Incremental Search-Based Allocation of Autonomous Robots for Goods Delivery}, 
  year={2023},
  volume={},
  number={},
  pages={1-10},
  keywords={Costs;Service robots;Heuristic algorithms;Scalability;Space exploration;Safety;Stakeholders;autonomous robots;goods delivery;search-based allocation;approximate fitness},
  doi={10.1109/CEC53210.2023.10254103}}
```

</details>

### 2022

**FreneticV at the SBST 2022 Tool Competition**<br>
**<u>Ezequiel Castellano</u>**, Stefan Klikovits, Ahmet Cetinkaya, Paolo Arcaini<br> 
*IEEE/ACM 15th International Workshop on Search-Based Software Testing (SBST)*<br>
[[PDF](https://dl.acm.org/doi/pdf/10.1145/3526072.3527532)] [[Publisher Link](https://doi.org/10.1145/3526072.3527532)]

<details markdown="1"><summary>Abstract & BibTeX</summary>

**Abstract:** FreneticV is a search-based testing tool based on an evolutionary approach that generates roads where an automated driving agent possibly fails the lane-keeping task. It uses a curvature-based road representation and, compared to its predecessor Frenetic, considers the validity of the generated roads. In particular, it tries to avoid generating roads with overly sharp turns, detects self-intersecting roads, and can rotate and relocate roads to fit them in a given map.

```bibtex
@INPROCEEDINGS{9810738,
  author={Castellano, Ezequiel and Klikovits, Stefan and Cetinkaya, Ahmet and Arcaini, Paolo},
  booktitle={2022 IEEE/ACM 15th International Workshop on Search-Based Software Testing (SBST)}, 
  title={FreneticV at the SBST 2022 Tool Competition}, 
  year={2022},
  volume={},
  number={},
  pages={47-48},
  keywords={Software testing;Roads;Conferences;Task analysis;search-based testing;autonomous driving;Frenet frame;FreneticV},
  doi={10.1145/3526072.3527532}}
}
```

</details>

**Explaining the behaviour of game agents using differential comparison**<br>
**<u>Ezequiel Castellano</u>**, Xiao-Yi Zhang, Paolo Arcaini, Toru Takisaka, Fuyuki Ishikawa, Nozomu Ikehata, Kosuke Iwakura<br> 
*Proceedings of the 37th IEEE/ACM International Conference on Automated Software Engineering*<br>
[[PDF](https://dl.acm.org/doi/pdf/10.1145/3551349.3560503)] [[Publisher Link](https://doi.org/10.1145/3551349.3560503)]

<details markdown="1"><summary>Abstract & BibTeX</summary>

**Abstract:** The difficulty in exploring the game balance has been increasing, especially in Game-as-a-Service (GaaS) with updates in every few weeks, and due to the complexity in game design and business models. In the limited time available for testing, using automated game agents enables much more test plays than using human test players does, and it has been accelerated by the recent progress of deep reinforcement learning. However, understanding specific behaviours of each agent is hard due to their “black-box” nature. In this paper, we propose a method for explaining the behaviour of game agents using differential comparison between agents. This comparison approach is motivated by our experience with existing explanation techniques that often extracted uninteresting, common aspects of the behaviour. In addition, there are large potentials for the application of the comparison: between agents with different learning algorithms, between human agents and automated agents, and between test agents and users. We applied our technique to a prototype of a commercial GaaS and confirmed our technique can extract specific differences between agents.

```bibtex
@inproceedings{10.1145/3551349.3560503,
author = {Castellano, Ezequiel and Zhang, Xiao-Yi and Arcaini, Paolo and Takisaka, Toru and Ishikawa, Fuyuki and Ikehata, Nozomu and Iwakura, Kosuke},
title = {Explaining the Behaviour of Game Agents Using Differential Comparison},
year = {2023},
isbn = {9781450394758},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3551349.3560503},
doi = {10.1145/3551349.3560503},
booktitle = {Proceedings of the 37th IEEE/ACM International Conference on Automated Software Engineering},
articleno = {210},
numpages = {8},
keywords = {explainability, games, reinforcement learning, testing},
location = {Rochester, MI, USA},
series = {ASE '22}
}
```

</details>

**Dynamic Shielding for Reinforcement Learning in Black-Box Environments**<br>
Masaki Waga, **<u>Ezequiel Castellano</u>**, Sasinee Pruekprasert, Stefan Klikovits, Toru Takisaka, Ichiro Hasuo<br> 
*International Symposium on Automated Technology for Verification and Analysis*<br>
[[PDF](https://arxiv.org/pdf/2207.13446)] [[Publisher Link](https://link.springer.com/chapter/10.1007/978-3-031-19992-9_2)]

<details markdown="1"><summary>Abstract & BibTeX</summary>

**Abstract:** It is challenging to use reinforcement learning (RL) in cyber-physical systems due to the lack of safety guarantees during learning. Although there have been various proposals to reduce undesired behaviors during learning, most of these techniques require prior system knowledge, and their applicability is limited. This paper aims to reduce undesired behaviors during learning without requiring any prior system knowledge. We propose dynamic shielding: an extension of a model-based safe RL technique called shielding using automata learning. The dynamic shielding technique constructs an approximate system model in parallel with RL using a variant of the RPNI algorithm and suppresses undesired explorations due to the shield constructed from the learned model. Through this combination, potentially unsafe actions can be foreseen before the agent experiences them. Experiments show that our dynamic shield significantly decreases the number of undesired events during training.

```bibtex
@InProceedings{10.1007/978-3-031-19992-9_2,
author="Waga, Masaki
and Castellano, Ezequiel
and Pruekprasert, Sasinee
and Klikovits, Stefan
and Takisaka, Toru
and Hasuo, Ichiro",
editor="Bouajjani, Ahmed
and Hol{\'i}k, Luk{\'a}{\v{s}}
and Wu, Zhilin",
title="Dynamic Shielding for Reinforcement Learning in Black-Box Environments",
booktitle="Automated Technology for Verification and Analysis",
year="2022",
publisher="Springer International Publishing",
address="Cham",
pages="25--41",
isbn="978-3-031-19992-9"
}
```

</details>


### 2021

**Analysis of Road Representations in Search-Based Testing of Autonomous Driving Systems**<br>
**<u>Ezequiel Castellano</u>**, Ahmet Cetinkaya, Paolo Arcaini<br> 
*IEEE 21st International Conference on Software Quality, Reliability and Security (QRS)*<br>
[[PDF](/assets/pdfs/QRS2021_RoadSearch.pdf)] [[Publisher Link](https://doi.org/10.1109/QRS54544.2021.00028)] [[Code](https://github.com/ERATOMMSD/roadsearch)]

<details markdown="1"><summary>Abstract & BibTeX</summary>

**Abstract:** Validating Autonomous Driving Systems (ADSs) is essential to ensure that the ADS meets the necessary requirements to be widely accepted. Simulation-based testing is one of the main validation approaches, in which the ADS is run in a simulated environment over different scenarios. In this context, search-based testing (SBT) is used to generate scenarios that possibly expose particular failures of the ADS under test. Most SBT approaches search for behaviors of other traffic participants, but usually fix the road map of the scenario in advance. Recently, the SBT community started investigating the search for road structures, which is particularly useful when testing specific components of the ADS, such as the lane-keeping component. However, roads can be represented in multiple ways and the impact of using a particular representation on the effectiveness of SBT is unclear. To fill this gap, this paper investigates the usage of six road representations for SBT of ADSs. As a representative SBT approach, we test the lane-keeping component of an ADS in the BeamNG.tech simulator, aiming to generate roads in which the autonomous vehicle drives off the lane. We study the effectiveness of each road representation in terms of triggered failures and also diversity of the generated roads.

```bibtex
@INPROCEEDINGS{9724804,
  author={Castellano, Ezequiel and Cetinkaya, Ahmet and Arcaini, Paolo},
  booktitle={2021 IEEE 21st International Conference on Software Quality, Reliability and Security (QRS)}, 
  title={Analysis of Road Representations in Search-Based Testing of Autonomous Driving Systems}, 
  year={2021},
  volume={},
  number={},
  pages={167-178},
  keywords={Roads;Conferences;Software quality;Software reliability;Security;Autonomous vehicles;Testing;Autonomous Driving Systems;Search-Based Testing;Simulation-Based Testing;Road Representation},
  doi={10.1109/QRS54544.2021.00028}
}
```

</details>

**Frenetic at the SBST 2021 Tool Competition**<br>
**<u>Ezequiel Castellano</u>**, Ahmet Cetinkaya, Cédric Ho Thanh, Stefan Klikovits, Xiaoyi Zhang, Paolo Arcaini<br>
*IEEE/ACM 14th International Workshop on Search-Based Software Testing (SBST)*<br>
[[PDF](/assets/pdfs/SBST2021_Frenetic.pdf)] [[Publisher Link](https://doi.org/10.1109/SBST52555.2021.00016)] [[Code](https://github.com/ERATOMMSD/frenetic-sbst21)]

<details markdown="1"><summary>Abstract & BibTeX</summary>

**Abstract:** Frenetic is a genetic approach that leverages a curvature-based road representation. Given an autonomous driving agent, the goal of Frenetic is to generate roads where the agent fails to stay within its lane. In other words, Frenetic tries to minimize the “out of bound distance”, which is the distance between the car and either edge of the lane if the car is within the lane, and proceeds to negative values once the car drives off. This work resembles classic aspects of genetic algorithms such as mutations and crossover, but introduces some nuances aiming at improving diversity of the generated roads.

```bibtex
@INPROCEEDINGS{9476234,
  author={Castellano, Ezequiel and Cetinkaya, Ahmet and Thanh, Cédric Ho and Klikovits, Stefan and Zhang, Xiaoyi and Arcaini, Paolo},
  booktitle={2021 IEEE/ACM 14th International Workshop on Search-Based Software Testing (SBST)}, 
  title={Frenetic at the SBST 2021 Tool Competition}, 
  year={2021},
  volume={},
  number={},
  pages={36-37},
  keywords={Software testing;Roads;Conferences;Tools;Drives;Genetics;Automobiles},
  doi={10.1109/SBST52555.2021.00016}
}
```

</details>

### 2020 
**[Doctoral Thesis] Minimising makespan of discrete controllers: A qualitative approach**<br>
**<u>Ezequiel Castellano</u>**<br>
*The Graduate University for Advanced Studies, SOKENDAI*<br>
[[PDF](https://ir.soken.ac.jp/record/6108/files/A2160%E6%9C%AC%E6%96%87.pdf)] [[Publisher Link](https://ir.soken.ac.jp/records/6108)] [[Code](https://github.com/ezecastellano/minimising-makespan)]

<details markdown="1"><summary>Abstract & BibTeX</summary>

**Abstract:** Qualitative controller synthesis techniques produce controllers that guarantee to achieve a given goal in the presence of an adversarial environment. However, qualitative synthesis only produces one controller out of many possible solutions and typically does not provide support for expressing preferences over other alternatives.
Synthesis and planning techniques that allow expressing preferences exist, such as those regarding performance or reliability. Such quality attributes are modelled by introducing a quantitative aspect to the system specification, which imposes a preference order on the controllers that satisfy the qualitative part of the specification. However, from a practical perspective, these approaches require modelling quality attributes quantitatively, whereas in many cases, such detailed representation is not available, possible, or desired.
The main objective of this thesis is to present a formal approach to reason about preferences qualitatively, restricting attention to makespan of discrete event-based controllers for safety and reachability goals. Time is reasoned upon symbolically, which relieves the user from providing concrete quantitative measures. In particular, we study the scenario in which durations of individual activities are not known up-front.
First, we show how controllers can be symbolically and fairly compared by fixing the contingencies. Then, we present an algorithm to produce controllers that are makespan-minimising. The algorithm was implemented in the MTSA tool, as well as evaluated in case studies.

```bibtex
@phdthesis{oai:ir.soken.ac.jp:00006108,
 author = {Ezequiel, Gustavo Castellano and Ezequiel, Gustavo Castellano},
 month = {Jun},
 note = {application/pdf, 総研大甲第2160号},
 school = {総合研究大学院大学},
 title = {Minimising Makespan of Discrete Controllers: A Qualitative Approach(離散制御器のメイクスパン最小化手法: 定性的アプローチ)},
 year = {2020},
 yomi = {エッセキエル, グスタヴォ　カステヤーノ}
}
```
</details>

### 2019

**Minimising makespan of discrete controllers: A qualitative approach**<br>
**<u>Ezequiel Castellano</u>**, Victor Braberman, Nicolás D’Ippolito, Sebastián Uchitel, Kenji Tei<br>
*IEEE 58th Conference on Decision and Control (CDC)*<br>
[[PDF](/assets/pdfs/CDC2019_MinimisingMakespan.pdf)] [[Publisher Link](https://doi.org/10.1109/CDC40024.2019.9029766)]

<details markdown="1"><summary>Abstract & BibTeX</summary>

**Abstract:** Qualitative controller synthesis techniques produce controllers that guarantee to achieve a given goal in the presence of an adversarial environment. However, qualitative synthesis only produces one controller out of many possible solutions and typically does not provide support for expressing preferences over other alternatives. In this paper, we thus present a formal approach to reason about preferences qualitatively, restricting attention to makespan of discrete event-based controllers for reachability goals. Time is reasoned upon symbolically, which relieves the user from providing concrete quantitative measures. In particular, we study the scenario in which durations of individual activities are not known up-front. We first show how controllers can be symbolically and fairly compared by fixing the contingencies. Then, we present an algorithm to produce controllers that are makespan-minimising.

```bibtex
@INPROCEEDINGS{9029766,
  author={Castellano, Ezequiel and Braberman, Victor and D’Ippolito, Nicolás and Uchitel, Sebastián and Tei, Kenji},
  booktitle={2019 IEEE 58th Conference on Decision and Control (CDC)}, 
  title={Minimising Makespan of Discrete Controllers: A Qualitative Approach}, 
  year={2019},
  volume={},
  number={},
  pages={1068-1075},
  keywords={Safety;Standards;Law;Production;Planning;Computational modeling},
  doi={10.1109/CDC40024.2019.9029766}}
```

</details>

**A Runtime Monitoring Framework to Enforce Invariants on Reinforcement Learning Agents Exploring Complex Environments**<br>
Piergiuseppe Mallozzi, **<u>Ezequiel Castellano</u>**, Patrizio Pelliccione, Gerardo Schneider, Kenji Tei<br>
*IEEE/ACM 2nd International Workshop on Robotics Software Engineering (RoSE)*<br>
[[PDF](https://rose-workshops.github.io/files/rose2019/papers/rose2019_2.pdf)] [[Publisher Link](https://doi.org/10.1109/RoSE.2019.00011)]

<details markdown="1"><summary>Abstract & BibTeX</summary>

**Abstract:** Without prior knowledge of the environment, a software agent can learn to achieve a goal using machine learning. Model-free Reinforcement Learning (RL) can be used to make the agent explore the environment and learn to achieve its goal by trial and error. Discovering effective policies to achieve the goal in a complex environment is a major challenge for RL. Furthermore, in safety-critical applications, such as robotics, an unsafe action may cause catastrophic consequences in the agent or in the environment. In this paper, we present an approach that uses runtime monitoring to prevent the reinforcement learning agent to perform "wrong" actions and to exploit prior knowledge to smartly explore the environment. Each monitor is de?ned by a property that we want to enforce to the agent and a context. The monitors are orchestrated by a meta-monitor that activates and deactivates them dynamically according to the context in which the agent is learning. We have evaluated our approach by training the agent in randomly generated learning environments. Our results show that our approach blocks the agent from performing dangerous and safety-critical actions in all the generated environments. Besides, our approach helps the agent to achieve its goal faster by providing feedback and shaping its reward during learning.

```bibtex
@INPROCEEDINGS{8823721,
  author={Mallozzi, Piergiuseppe and Castellano, Ezequiel and Pelliccione, Patrizio and Schneider, Gerardo and Tei, Kenji},
  booktitle={2019 IEEE/ACM 2nd International Workshop on Robotics Software Engineering (RoSE)}, 
  title={A Runtime Monitoring Framework to Enforce Invariants on Reinforcement Learning Agents Exploring Complex Environments}, 
  year={2019},
  volume={},
  number={},
  pages={5-12},
  keywords={Monitoring;Runtime;Safety;Reinforcement learning;Probabilistic logic;Software agents;runtime monitoring;reinforcement learning;reward shaping;LTL invariants},
  doi={10.1109/RoSE.2019.00011}}
```

</details>