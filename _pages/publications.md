---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Preprint

1. G. Marchesini, **S. Liu**, L. Lindemann and D. V. Dimarogonas. [Sampling-Based Planning Under STL Specifications: A Forward Invariance Approach](https://arxiv.org/abs/2506.10739), arXiv:2506.10739, 2025.


## Journal Papers
1. G. Marchesini, **S. Liu**, L. Lindemann and D. V. Dimarogonas. [A Communication Consistent Approach to Signal Temporal Logic Task Decomposition in Multi-Agent Systems](https://arxiv.org/abs/2410.12563). _IEEE Transactions on Automatic Control_, to appear, 2025.
2. T. Zaccherini, **S. Liu**, and D. V. Dimarogonas, [Multi-Agent Estimation and Control Based on a Novel k-hop Distributed Prescribed Performance Observer](https://ieeexplore.ieee.org/document/11018605). _IEEE Control Systems Letters_, to appear, 2025. 
3. **S. Liu**, A. Saoud, and D. V. Dimarogonas. [Controller synthesis of collaborative signal temporal logic tasks for multi-agent systems via assume-guarantee contracts](https://ieeexplore.ieee.org/document/10918825). _IEEE Transactions on Automatic Control_, to appear, 2025.
4. B. Zhong, **S. Liu**,  M. Caccamo, and  M. Zamani. [Secure-by-construction synthesis for control systems](https://ieeexplore.ieee.org/document/10849614). _IEEE Transactions on Automatic Control_, vol. 70, no. 6, pp. 4170--4177, 2025.
5. **S. Liu**, X. Yin, D. V. Dimarogonas, and M. Zamani. [On approximate opacity of stochastic control systems](https://ieeexplore.ieee.org/document/10795160). _IEEE Transactions on Automatic Control_, vol. 70, no. 6, pp. 3846-3861, 2025.
6. J. Hou\*, **S. Liu**\*, X. Yin, and M. Zamani. [Abstraction-based verification of approximate pre-opacity for control systems](https://ieeexplore.ieee.org/document/9993745?source=authoralert). _IEEE Control Systems Letters_, vol. 7, pp. 1087--1092, 2022. doi: 10.1109/LCSYS.2022.3230770. (\*contributed equally)
7. **S. Liu**, A. Trivedi, X. Yin, and M. Zamani. [Secure-by-construction synthesis of cyber-physical systems](https://www.sciencedirect.com/science/article/pii/S1367578822000104). _Annual Reviews in Control_, vol. 53, pp. 30--50, 2022. doi: 10.1016/j.arcontrol.2022.03.004.
8. **S. Liu**, N. Noroozi, and M. Zamani. [Symbolic models for infinite networks of control systems: A compositional approach](https://www.sciencedirect.com/science/article/pii/S1751570X2100087X?dgcid=author). _Nonlinear Analysis: Hybrid Systems_, vol. 43, December 2021. doi: 10.1016/j.nahs.2021.101097.
9. S. Tasdighi Kalat, **S. Liu**, and M. Zamani. [Modular verification of opacity for interconnected control systems via barrier certificates](https://ieeexplore.ieee.org/document/9447831). _IEEE Control Systems Letters_, vol. 6, pp. 890--895, 2022. doi: 10.1109/LCSYS.2021.3087103.
10. **S. Liu**, A. Swikir, and M. Zamani. [Verification of approximate-state opacity for switched systems: A compositional approach](https://www.sciencedirect.com/science/article/pii/S1751570X21000741?dgcid=author). _Nonlinear Analysis: Hybrid Systems_, vol. 42, November 2021. doi: 10.1016/j.nahs.2021.101084.
11. **S. Liu**, M. Zamani. [Compositional synthesis of opacity-preserving finite abstractions for interconnected systems](https://www.sciencedirect.com/science/article/pii/S000510982100265X?dgcid=author). _Automatica_, vol. 131, September 2021. doi: 10.1016/j.automatica.2021.109745. 
12. **S. Liu** and M. Zamani. [Verification of approximate opacity via barrier certificates](https://ieeexplore.ieee.org/document/9257384). _IEEE Control Systems Letters (presented at ACC 2021)_, vol. 5, no. 4, pp. 1369--1374, Oct. 2021. doi: 10.1109/LCSYS.2020.3037840.
13. X. Yin, M. Zamani, and **S. Liu**. [On approximate opacity of cyber-physical systems](https://ieeexplore.ieee.org/document/9104922). _IEEE Transactions on Automatic Control_, vol. 66, no. 4, pp. 1630--1645, April 2021. doi: 10.1109/TAC.2020.2998733.
14. Z. Liang, **S. Liu**, et al. [Lateral entry guidance with no-fly zone constraint](https://www.sciencedirect.com/science/article/abs/pii/S1270963816309464). _Aerospace science and technology_, 60: 39--47. 2017. doi: 10.1016/j.ast.2016.10.025.
15. **S. Liu**, Z. Liang, Z. Ren, Q. Li. Review of reentry guidance methods for hypersonic gliding vehicles. _Chinese Space Science and Technology_, 36(6), 1. 2016.



## Conference Papers

1. T. Zaccherini, **S. Liu**, and D. V. Dimarogonas. Communication-aware multi-agent systems control based on k-hop distributed observers. _European Control Conference (ECC)_, to appear, June 2025.
2. **S. Liu**, F. Chen, and D. V. Dimarogonas. Transient control of linear multi-agent systems with leader-follower configuration. _American Control Conference (ACC)_, to appear, July 2025.
3. G. Marchesini, **S. Liu**, L. Lindemann, and D. V. Dimarogonas. Decentralized control of multi-agent systems under acyclic spatio-temporal task dependencies. _the 63rd IEEE Conference on Decision and Control (CDC)_, to appear, December 2024.
4. G. Marchesini, **S. Liu**, L. Lindemann, and D. V. Dimarogonas. Communication-constrained STL task decomposition through convex optimization. _American Control Conference (ACC)_, to appear, July 2024.
5. B. Zhong, **S. Liu**, M. Caccamo, and M. Zamani. Towards trustworthy AI: Sandboxing AI-based unverified controllers for safe and secure cyber-physical systems. _the 62nd IEEE Conference on Decision and Control (CDC)_, pp. 1833--1840, December 2023. 
6. J. Hou, **S. Liu**, X. Yin, and M. Zamani. Abstraction-based synthesis of controllers for approximate opacity, _the 62nd IEEE Conference on Decision and Control (CDC)_, pp. 7930--7936, December 2023.
7. B. Zhong, **S. Liu**, M. Caccamo, and M. Zamani. [Secure-by-Construction Controller Synthesis via Control Barrier Functions](https://www.sciencedirect.com/science/article/pii/S2405896323019833). _22nd IFAC World Congress_, 56(2), 239--245, July 2023.
8. **S. Liu**, A. Saoud, P. Jagtap, D. V. Dimarogonas, and M. Zamani. [Compositional synthesis of signal temporal logic tasks via assume-guarantee contracts](https://ieeexplore.ieee.org/abstract/document/9992715). _61st IEEE Conference on Decision and Control (CDC)_, pp. 2184--2189, December 2022.
9. S. Tasdighi Kalat, **S. Liu**, and M. Zamani. [Verification of approximate infinite-step opacity using barrier certificates](https://ieeexplore.ieee.org/document/9838153). _European Control Conference (ECC)_, pp. 175--180, July 2022.
10. **S. Liu**, A. Swikir, and M. Zamani. [Compositional verification of initial-state opacity for switched systems](https://ieeexplore.ieee.org/document/9304322). _59th IEEE Conference on Decision and Control (CDC)_, pp. 2146--2151, December 2020.
11. **S. Liu**, X. Yin, and M. Zamani. [On a notion of approximate opacity for discrete-time stochastic control systems](https://ieeexplore.ieee.org/document/9147235). _American Control Conference (ACC)_, pp. 5413--5418, July 2020.  
12. **S. Liu** and M. Zamani. [Compositional synthesis of almost maximally permissible safety controllers](https://ieeexplore.ieee.org/document/8815361). _American Control Conference (ACC)_, pp. 1678--1683, July 2019.
13. **S. Liu**, Z. Liang, et al. [Predictor-corrector guidance for entry with terminal altitude constraint](https://ieeexplore.ieee.org/document/7554222). _IEEE Chinese Control Conference (CCC)_, pp. 5557--5562, July 2016. 


## Dissertations
* **S. Liu**, [Secure-by-Construction Synthesis of Cyber-Physical Systems](https://mediatum.ub.tum.de/?id=1651390), Ph.D. Dissertation, _Technical University of Munich (TUM)_, Germany, April 2022.


