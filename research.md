---
layout: default
---
# Research
The list below shows the major on-going research activities currently being performed in our lab. More details about the project overviews will come soon...

### Autonomous security monitoring and enforcement
In this research, we consider security of system-on-chip designs where the trust of the consisting blocks cannot be establised. The objective is to design HW/SW agents embedded in such designs that can detect and mitigate security attacks autonomously or with minimal human intervention.

### Specification mining for system-on-chip design validation
Comprehensive and well-defined specifications are necessary to perform rigorous and thorough validation of system-on-chip~(SoC) designs. However, in practice such specifications are usually not available, often ambiguous, incomplete, or even contain errors. Moreover, as a SoC design gradually progresses across design stages, the connection between the original specifications and the design implementation may become imprecise and disjoint. The specification problems may lead to potential misunder-standings of the design behavior, introduce unintentional behavior into the design, and hinder effective and efficient validation process. This project addresses that problem by developing automated methods to extract patterns from SoC execution traces using data mining and machine learning techniques. The extracted patterns are served as specification which can be used in SoC validation and debug.
More information about on-going research about this project can be found in our [GitHub repository](https://github.com/sees-usf/Spec-mining-top).

### Safety and Robustness of Machine Learning
Machine learning can be found in growing number of applications due to its recent advances in performance. Many of such applicaitons are becoming increasingly autonomous relying on the decisions made by the embedded machine learning components. At the same time, such applications, self-driving, medical diagnosis, etc, are often safety critical. The robustness is susceptible to adversarial perturbations, which can affect the safety of the overall systems. The objective of this research is to develop verification and testing methods to show safety and robustness of machine learning algorithms under perturbations.

### Testing, verification, and validation of software, hardware, and embedded systems
##### [Scalable methods for probabilistic model checking](https://github.com/sees-usf/ProbMC)
Recently, we received an NSF award to support this project. If you are interested in knowing more about this project, please visit the project page by cliking the project title.

##### [Efficient model checking of parallel and distributed systems](https://github.com/sees-usf/MCCS)
In this project, we try to address the state space explosion problem often encountered during model checking systems of high concurrency. The central idea behind our research is divide-n-conquer, i.e., verification of an entire system is inferred by results from verification of consisting components.

##### [Post-Silicon Debug for System-on-Chip Designs](https://github.com/sees-usf/SoC-Validation)
Post-silicon validation is an activity where a pre-production silicon prototype is used for various types of validation. Compared with pre-silicon verification, post-silicon validation executes silicon at the target speed under real operating conditions, therefore, one second of post-silicon execution may require months or years of pre-silicon simulation cycles. As a result, post-silicon validation allows much deeper state space to be explored, thus being able to reveal bugs escaped from pre-silicon verfification. On the other hand, limited observability is a major challenge to effective post-silicon validation as there are only a very limited number of interface pins available for observing internal behavior of a design for efficient debug. In this research, we have been addressing this problem at a higher abstraction level from a system perspective.

### Hardware/software design of machine learning under latency and energy constraints