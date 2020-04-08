# Robust investment under risk and ambiguity

We incorporate techniques from distributionally robust optimization into a dynamic investment model. This allows us to explicitly account for ambiguity in the decision-making process. We outline an economic, mathematical, and computational model to study the seminal bus replacement problem (Rust, 1987) under potential model misspecification. We specify ambiguity sets for the transition dynamics of the model. These are based on empirical estimates, statistically meaningful, and computationally tractable. We analyze alternative policies in a series of computational experiments. We find that, given the structure of the model and the available data on past transitions, a policy simply ignoring model misspecification often outperforms its alternatives that are designed to explicitly account for it.

## Manuscript

* Blesch, M., Eisenhauer, P. (2020). [Robust investment under risk and ambiguity](https://github.com/robustzurcher/promotion/raw/master/Eisenhauer%26Blesch.2020.pdf). Submitted.

## Computational support

We develop two software packages in support of this research. We ensure transparency, reproducibility, and extensibility by documenting both of them online.

* `ruspy`, open-source package for estimating and simulating infinite horizon single-agent discrete choice model in the setting
of Rust (1987). More details are available in our [online documentation](https://ruspy.readthedocs.io/en/latest/#).

* `robpy`, open-source package for finding worst-case probabilities in the context of robust decision making. More details are available in our [online documentation](https://robupy.readthedocs.io/en/latest/#).
