# Exclude elements and more time

Clustering algorithm applied to [originations_dsm.m](/dsm/originations_dsm.m).

| **Parameter** | **Value** |
| --- | --- |
| `pow_cc`           |     1 |
| `pow_bid`          |    -1 |
| `pow_dep`          |     4 |
| `max_cluster_size` |    31 |
| `rand_accept`      |    62 |
| `rand_bid`         |    62 |
| `times`            |     4 |
| `stable_limit`     |     4 |

We set `times` and `stable_limit` to 4 to let the algorithm run for a longer time before reporting results. We extracted *Applicant data* and *Risk management strategy*. We set `pow_bid` to -1 to penalize small clusters instead of large ones.

| **Mean** | **Median** | **# clusters** |
| --- | --- | --- |
| 0.66507 | 0.66454 | 7 - 10 |

The likeness mean and median are close to the ones of the experiment [Exclude elements with high number of outputs](/results/3-exclude-elements-with-high-number-of-outputs). We get small clusters (size 1 to 3) and clusterings with many clusters.