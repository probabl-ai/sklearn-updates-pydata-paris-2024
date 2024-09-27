# "An update on the latest scikit-learn features" - PyData Paris 2024

This repository contains the supporting material for the talks entitled:

"An update on the latest scikit-learn features"

It was presented at PyData Paris 2024 on September 26, 2024. The slides are
available [here](https://docs.google.com/presentation/d/18XZcuokdTafTay8HKZzO0KkZnfuL3WkIhrbwjCJsvJc/edit?usp=sharing).

You will find a collection of code associated to the demo on the slides.

### Optmising operational decision

You can refer to the
[following example](https://scikit-learn.org/stable/auto_examples/model_selection/plot_cost_sensitive_learning.html#sphx-glr-auto-examples-model-selection-plot-cost-sensitive-learning-py) 
to see a use case using the new `TunedThresholdClassifierCV` to optimize
the decision of a classifier based on a business metric.

### Array-API: GPU dispatch

The [following notebook](https://colab.research.google.com/drive/1TeF6fZQvvKFRJDagXN6Bbn0199sRiQ6j?usp=sharing)
show a demo leveraging the Array-API that dispatches some computation on a GPU.

### Metadata Routing API

[This
notebook](https://github.com/StefanieSenger/Talks/blob/main/2024_Metadata-Routing-API/metatdata_routing_API.ipynb)
contains the code shown in the talk on the metadata routing API and some notes for the context.


### References

#### Metadata routing

- [User Guide on Metadata Routing](https://scikit-learn.org/stable/metadata_routing.html#metadata-routing)
- [Developer Guide on Metadata Routing](https://scikit-learn.org/stable/auto_examples/miscellaneous/plot_metadata_routing.html#metadata-routing)
- [Adrin Jalali's talk on the internal logic of metadata routing at EuroPython Conference 2023](https://www.youtube.com/watch?v=1rf6HI-pYq8)

#### Use cases using `sample_weight`

- [:probabl. Whiteboard Series by Vincent Warmerdam: Improving models via subsets](https://www.youtube.com/watch?v=REIg5NH2SNc)
- [Blogpost by Florian Wilhelm on Inverse Probability of Treatment Weighting](https://florianwilhelm.info/2017/04/causal_inference_propensity_score)
