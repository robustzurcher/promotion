# Robust investments under risk and ambiguity

We incorporate techniques from distributionally robust optimization into a dynamic investment model. This allows us to explicitly account for ambiguity in the decision-making process. We outline an economic, mathematical, and computational model to study the seminal bus replacement problem (Rust, 1987) under potential model misspecification. We specify ambiguity sets for the transition dynamics of the model. These are based on empirical estimates, statistically meaningful, and computationally tractable. We analyze alternative policies in a series of computational experiments. We find that, given the structure of the model and the available data on past transitions, a policy simply ignoring model misspecification often outperforms its alternatives that are designed to explicitly account for it.

## Manuscript

* Blesch, M., Eisenhauer, P. (2020). [Robust investments under risk and ambiguity](https://github.com/robustzurcher/promotion/raw/master/Blesch%26Eisenhauer_2020_manuscript.pdf). Submitted.

## Presentation

We provide the most recent version of our slide deck [here](https://github.com/robustzurcher/promotion/raw/master/Blesch%26Eisenhauer_2020_slides.pdf) and a recording is available [online](https://vimeo.com/nuvolos/review/405110545/111a183a04?sort=lastUserActionEventDate&direction=desc) as well.  

## Computational support

We develop two software packages in support of this research. We ensure transparency, reproducibility, and extensibility by documenting both of them online.

* [`ruspy`](https://github.com/OpenSourceEconomics/ruspy) (2019). An open-source package for the simulation and estimation of a prototypical infinite-horizon dynamic discrete choice model based Rust (1987). More details are available in our [online documentation](https://ruspy.readthedocs.io/en/latest/#).

* [`robupy`](https://github.com/OpenSourceEconomics/robupy) (2019). A open-source package for robust optimization. More details are available in our [online documentation](https://robupy.readthedocs.io/en/latest/#).
