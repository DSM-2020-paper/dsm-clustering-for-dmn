# Varied interaction levels

Clustering algorithm applied to [originations_dsm_varied.m](/dsm/originations_dsm_varied.m). We set the interaction level to 0.5 for Input Data and Knowledge Sources, for Decisions we set it to 2.

| **Parameter**          | **Value** |
| --- | --- |
| `pow_cc`           |     1 |
| `pow_bid`          |    -1 |
| `pow_dep`          |     4 |
| `max_cluster_size` |    31 |
| `rand_accept`      |    62 |
| `rand_bid`         |    62 |
| `times`            |     2 |
| `stable_limit`     |     2 |

We set `pow_bid` to -1 to penalize small clusters instead of large ones.

| **Mean** | **Median** | **# clusters** |
| --- | --- | --- |
| 0.60985 | 0.61259 | 8 - 10 |

The likeness mean and median are grater than the one of [Penalize small clusters](/results/1-penalize-small-clusters) experiment (where all interaction levels set to 1). We get too many small clusters, however, the delta between the maximum and the minimum number of clusters is only 2.