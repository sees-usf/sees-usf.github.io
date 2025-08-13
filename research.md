---
layout: default
---
# Research
Below is a list of our lab’s major ongoing research activities. Please check back regularly for updates.

### GenAI for hardware design
In this research, we explore the use of generative AI, particularly large language models (LLMs), to assist in various aspects of hardware design—such as generating RTL code, testbenches, and assertions from natural language descriptions. Our ultimate goal is to enable fully autonomous hardware design, where <em>systems</em> that meet diverse requirements—including functionality, performance, power/energy efficiency, and security—can be automatically synthesized from natural language specifications.  
Some preliminary results can be found in our [GitHub repository](https://github.com/bnadimi/GenAI-for-hardware-design).

### Hardware/software co-design of AI applications under latency and energy constraints
The aim is to optimize efficiency of GenAI, specifically large language models (LLMs), in terms of latency and energy through hardware-software co-design and innovations across the entire system stack from model architectures and algorithms (training/inference) to hardware implementation. 

Highly motivated students with strong independent problem-solving skills are invited to join us and make contributions to this research directioin. Solid background in computer arechitecture and large language model (LLM) architectures, and extensive experiences of hardware design are required. 

### Specification mining for system-on-chip design validation
Comprehensive and well-defined specifications are necessary to perform rigorous and thorough validation of system-on-chip~(SoC) designs. However, in practice such specifications are usually not available, often ambiguous, incomplete, or even contain errors. Moreover, as a SoC design gradually progresses across design stages, the connection between the original specifications and the design implementation may become imprecise and disjoint. The specification problems may lead to potential misunder-standings of the design behavior, introduce unintentional behavior into the design, and hinder effective and efficient validation process. This project addresses that problem by developing automated methods to extract patterns from SoC execution traces using data mining and machine learning techniques. The extracted patterns are served as specification which can be used in SoC validation and debug.
More information about on-going research about this project can be found in our [GitHub repository](https://github.com/sees-usf/Spec-mining-top).

### Safety and Robustness of Machine Learning
Machine learning can be found in growing number of applications due to its recent advances in performance. Many of such applicaitons are becoming increasingly autonomous relying on the decisions made by the embedded machine learning components. At the same time, such applications, self-driving, medical diagnosis, etc, are often safety critical. The robustness is susceptible to adversarial perturbations, which can affect the safety of the overall systems. The objective of this research is to develop verification and testing methods to show safety and robustness of machine learning algorithms under perturbations.

### Testing, verification, and validation of software, hardware, and embedded systems
##### Scalable methods for probabilistic model checking
This project focuses on extending the capabilities of probabilistic model checking to handle complex safety-critical systems, particularly those with biological components. These systems often present two significant obstacles: **very large or infinite state spaces** that exceed memory limits, and the **extreme rarity of critical error states**, making their analysis computationally prohibitive. To address the challenge of extensive state spaces, we developed a **[property-guided state-space truncation method](https://github.com/fluentverification/bmc_counterexample)**. This technique intelligently reduces the model size by focusing on states most relevant to the properties being verified, making it amenable to model checking. For the issue of rare event analysis, we first conducted a **[comparative study of importance sampling methods](https://github.com/fluentverification/weghted_SSA)** to enhance the efficiency of Monte Carlo simulations. Building upon this, we introduced a novel **[reinforcement learning framework to automate parameter selection for weighted Stochastic Simulation Algorithms (wSSA)](https://github.com/moahmadi26/rlwssa)**, thereby improving the performance and automation of rare event probability estimation. These contributions aim to make the stochastic analysis of such challenging systems more scalable and robust.
Key publications from this project include:
* Ahmadi, M.,  Buecherl, L., Myers, C.J., Zhang, Z., Winstead, C. and Zheng, H., 2024, August. Rare-Event Guided Analysis of Infinite-State Chemical Reaction Networks. In *International Conference on Quantitative Evaluation of Systems and Formal Modeling and Analysis of Timed Systems* (pp. 196-212). Cham: Springer Nature Switzerland.
* Ahmadi, M., Thomas, P.J., Buecherl, L., Winstead, C., Myers, C.J. and Zheng, H., 2022. A comparison of weighted stochastic simulation methods for the analysis of genetic circuits. *ACS Synthetic Biology*, 12(1), pp.287-304.

##### [Efficient model checking of parallel and distributed systems](https://github.com/sees-usf/MCCS)
In this project, we try to address the state space explosion problem often encountered during model checking systems of high concurrency. The central idea behind our research is divide-n-conquer, i.e., verification of an entire system is inferred by results from verification of consisting components.

##### [Post-Silicon Debug for System-on-Chip Designs](https://github.com/sees-usf/SoC-Validation)
Post-silicon validation is an activity where a pre-production silicon prototype is used for various types of validation. Compared with pre-silicon verification, post-silicon validation executes silicon at the target speed under real operating conditions, therefore, one second of post-silicon execution may require months or years of pre-silicon simulation cycles. As a result, post-silicon validation allows much deeper state space to be explored, thus being able to reveal bugs escaped from pre-silicon verfification. On the other hand, limited observability is a major challenge to effective post-silicon validation as there are only a very limited number of interface pins available for observing internal behavior of a design for efficient debug. In this research, we have been addressing this problem at a higher abstraction level from a system perspective.


