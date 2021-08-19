# Robust investments under risk and ambiguity

Economists often estimate a subset of their model parameters outside the model and let the decision-makers inside the model treat these point estimates as-if they are correct. This practice ignores model ambiguity, opens the door for misspecification of the decision problem, and leads to post-decision disappointment. We develop a framework to explore, evaluate, and optimize decision rules that explicitly account for the uncertainty in the first step estimation using statistical decision theory. We show how to operationalize our analysis by studying a stochastic dynamic investment model where the decision-makers take ambiguity about the model’s transition
dynamics directly into account.


## Manuscript

* Blesch, M., Eisenhauer, P. (2020). [Robust investments under risk and ambiguity](https://arxiv.org/abs/2104.12573). Working paper.

## Presentation

We provide a slide deck from an earlier stage of the paper [here](https://github.com/robustzurcher/promotion/raw/master/Blesch%26Eisenhauer_2020_slides.pdf) and the corresponding recorded talk is available [online](https://vimeo.com/nuvolos/review/405110545/111a183a04?sort=lastUserActionEventDate&direction=desc) as well.

## Software

We develop two software packages in support of this research. We ensure transparency, reproducibility, and extensibility by providing both of them online.

* [`ruspy`](https://github.com/OpenSourceEconomics/ruspy) (2020). An open-source package for the simulation and estimation of a prototypical infinite-horizon dynamic discrete choice model based on Rust (1987). More details are available in our [online documentation](https://ruspy.readthedocs.io/en/latest/#).

* [`robupy`](https://github.com/OpenSourceEconomics/robupy) (2020). An open-source package for robust optimization. More details are available in our [online documentation](https://robupy.readthedocs.io/en/latest/#).
