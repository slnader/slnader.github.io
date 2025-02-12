---
layout: default
---

## Public Datasets

- Glove-V
[\<link\>](https://huggingface.co/datasets/reglab/glove-v){:target="_blank"}
[\<supplementary materials\>](https://aclanthology.org/2024.emnlp-main.510/){:target="_blank"}
> The Glove-V repository contains pre-computed GloVe embeddings and GloVe-V variances for the
Corpus of Historical American English (COHA) (1900-1999) (300-dim).

- NC-CAFO
[\<link\>](https://reglab.stanford.edu/data/cafo-training-dataset/){:target="_blank"}
[\<supplementary materials\>](https://static-content.springer.com/esm/art%3A10.1038%2Fs41893-019-0246-x/MediaObjects/41893_2019_246_MOESM1_ESM.pdf){:target="_blank"}
> The NC-CAFO dataset includes hand-validated images
of poultry and swine CAFOs and control images throughout the state of North
Carolina from the US Department of Agriculture (USDA)
National Agricultural Imagery Program (NAIP).

- fcc-comments
[\<link\>](https://huggingface.co/datasets/slnader/fcc-comments){:target="_blank"}
[\<supplementary materials\>](https://onlinelibrary.wiley.com/action/downloadSupplement?doi=10.1002%2Fpoi3.327&file=poi3327-sup-0001-online-appendix.pdf){:target="_blank"}
> fcc-comments is an annotated version of the comment corpus from the
Federal Communications Commission's (FCC) 2017 "Restoring Internet Freedom" proceeding.
The comment data were processed to be in a consistent format (machine-readable pdf or plain text), and annotated with three types of information: whether the comment was cited in the agency's final order, the type of commenter (individual, interest group, business group), and whether the comment was associated with an in-person meeting.

## Code Repositories and Software
- Glove-V starter code
[\<link\>](https://github.com/reglab/glove-v){:target="_blank"}
[\<supplementary materials\>](https://aclanthology.org/2024.emnlp-main.510/){:target="_blank"}
> Code to download pre-computed GloVe embeddings and GloVe-V variances from our HuggingFace repository, 
to interact with these data products and propagate uncertainty to downstream tasks.


- Probabilistic relevance ranking algorithm used in "Do fake online comments
pose a threat to regulatory policymaking? Evidence from Internet regulation
in the United States." [\<source\>](https://github.com/slnader/fcc-comments/tree/main/search_utils){:target="_blank"}
[\<supplementary materials\>](https://onlinelibrary.wiley.com/action/downloadSupplement?doi=10.1002%2Fpoi3.327&file=poi3327-sup-0001-online-appendix.pdf){:target="_blank"}
>Python implementation of BM25 relevance ranking algorithm with weighting option
designed to work with corpuses that have a large amount of duplication.

- Replication code for "Do fake online comments pose a threat to regulatory
policymaking? Evidence from Internet regulation in the United States."
[\<source\>](https://github.com/slnader/fcc-comments){:target="_blank"}
[\<paper\>](https://doi.org/10.1002/poi3.327){:target="_blank"}
>The code and data in this repository will replicate the comment scoring and
analysis conducted in "Do fake online comments pose a threat to regulatory
policymaking? Evidence from Internet regulation in the United States."

- Replication code for "Deep Learning to Map Concentrated Animal Feeding Operations"
[\<source\>](https://github.com/slnader/cafo_public){:target="_blank"}
[\<paper\>](https://www.nature.com/articles/s41893-019-0246-x){:target="_blank"}
>The code and data in this repository will replicate the tables and figures
in the main body of "Deep Learning to Map Concentrated Animal Feeding Operations."
Includes manually tagged and modeled CAFO point locations.

- The Educational Opportunity Monitoring Project
[\<source\>](https://github.com/slnader/achievement_gaps){:target="_blank"}
[\<live site\>](https://cepa.stanford.edu/educational-opportunity-monitoring-project/achievement-gaps/race/)
>Interactive graphics depicting trends in racial and ethnic achievement gaps
for all 50 states, and how the gaps relate to socioeconomic inequalities between
groups.


- Income Segregation in the United States' Largest Metropolitan Areas
[\<source\>](https://github.com/slnader/income_maps){:target="_blank"}
[\<live site\>](https://inequality.stanford.edu/income-segregation-maps){:target="_blank"}
>Interactive maps of the patterns and trends in residential income segregation
over the past forty years in the two dozen most populated metropolitan areas
of the United States.
