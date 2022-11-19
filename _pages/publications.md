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

## Journal Papers

1. **S. Liu**, A. Trivedi, X. Yin, and M. Zamani. [Secure-by-Construction Synthesis of Cyber-Physical Systems](https://www.sciencedirect.com/science/article/pii/S1367578822000104). _Annual Reviews in Control_, vol. 53, pp. 30--50, 2022.
2. **S. Liu**, N. Noroozi, and M. Zamani. [Symbolic models for infinite networks of control systems: A compositional approach](https://www.sciencedirect.com/science/article/pii/S1751570X2100087X?dgcid=author). _Nonlinear Analysis: Hybrid Systems_, vol. 43, December 2021. doi: 10.1016/j.nahs.2021.101097.
3. S. Tasdighi Kalat, **S. Liu**, and M. Zamani. [Modular verification of opacity for interconnected control systems via barrier certificates](https://ieeexplore.ieee.org/document/9447831). _IEEE Control Systems Letters_, vol. 6, pp. 890-895, 2022. doi: 10.1109/LCSYS.2021.3087103.
4. **S. Liu**, A. Swikir, and M. Zamani. [Verification of approximate-state opacity for switched systems: A compositional approach](https://www.sciencedirect.com/science/article/pii/S1751570X21000741?dgcid=author). _Nonlinear Analysis: Hybrid Systems_, vol. 42, November 2021. doi: 10.1016/j.nahs.2021.101084.
5. **S. Liu**, M. Zamani. [Compositional synthesis of opacity-preserving finite abstractions for interconnected systems](https://www.sciencedirect.com/science/article/pii/S000510982100265X?dgcid=author). _Automatica_, vol. 131, September 2021. doi: 10.1016/j.automatica.2021.109745. 
6. **S. Liu** and M. Zamani. [Verification of approximate opacity via barrier certificates](https://ieeexplore.ieee.org/document/9257384). _IEEE Control Systems Letters (presented at ACC 2021)_, vol. 5, no. 4, pp. 1369-1374, Oct. 2021. doi: 10.1109/LCSYS.2020.3037840.
7. X. Yin, M. Zamani, and **S. Liu**. [On approximate opacity of cyber-physical systems](https://ieeexplore.ieee.org/document/9104922). _IEEE Transactions on Automatic Control_, vol. 66, no. 4, pp. 1630-1645, April 2021. doi: 10.1109/TAC.2020.2998733.
8. Z. Liang, **S. Liu**, et al. [Lateral entry guidance with no-fly zone constraint](https://www.sciencedirect.com/science/article/abs/pii/S1270963816309464). _Aerospace science and technology_, 60: 39-47. 2017. doi: 10.1016/j.ast.2016.10.025.
9. **S. Liu**, Z. Liang, Z. Ren, Q. Li. Review of reentry guidance methods for hypersonic gliding vehicles. _Chinese Space Science and Technology_, 36(6), 1. 2016.



## Conference Papers

1. **S. Liu**, A. Saoud, P. Jagtap, D. V. Dimarogonas, and M. Zamani. Compositional synthesis of signal temporal logic tasks via assume-guarantee contracts, _61th IEEE Conference on Decision and Control (CDC)_, to appear, December 2022.
2. S. Tasdighi Kalat, **S. Liu**, and M. Zamani. Verification of approximate infinite-step opacity using barrier certificates. _European Control Conference (ECC)_, pp. 175-180, July 2022.
3. **S. Liu**, A. Swikir, and M. Zamani. Compositional verification of initial-state opacity for switched systems. _59th IEEE Conference on Decision and Control (CDC)_, pp. 2146-2151, December 2020.
4. **S. Liu**, X. Yin, and M. Zamani. On a notion of approximate opacity for discrete-time stochastic control systems. _American Control Conference (ACC)_, pp. 5413-5418, July 2020.  
5. **S. Liu** and M. Zamani. Compositional synthesis of almost maximally permissible safety controllers. _American Control Conference (ACC)_, pp. 1678-1683, July 2019.
6. **S. Liu**, Z. Liang, et al. Predictor-corrector guidance for entry with terminal altitude constraint. _IEEE Chinese Control Conference (CCC)_, pp. 5557-5562, July 2016.
