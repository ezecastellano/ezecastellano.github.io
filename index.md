# Ezequiel Castellano, Ph.D.

Senior Research Engineer at Woven by Toyota with experience in both industry and academia spanning software engineering, formal methods, scenario-based testing, machine learning safety, and LLM engineering with a track record of academic-industry collaborations and bringing research outcomes into production. 

[Google Scholar](https://scholar.google.com/citations?user=41tcnMQAAAAJ&hl=en) | [LinkedIn](https://www.linkedin.com/in/ezequiel-castellano-phd/)

---

## Publications

### 2021

**Analysis of Road Representations in Search-Based Testing of Autonomous Driving Systems**<br>
**<u>Ezequiel Castellano</u>**, Ahmet Cetinkaya, Paolo Arcaini<br> 
*IEEE 21st International Conference on Software Quality, Reliability and Security (QRS), 2021*<br>
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

<br>

**Frenetic at the SBST 2021 Tool Competition**<br>
**<u>Ezequiel Castellano</u>**, Ahmet Cetinkaya, Cédric Ho Thanh, Stefan Klikovits, Xiaoyi Zhang, Paolo Arcaini<br>
*IEEE/ACM 14th International Workshop on Search-Based Software Testing (SBST), 2021*<br>
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