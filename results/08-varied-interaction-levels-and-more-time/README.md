# Varied interaction levels and more time

Clustering algorithm applied to [originations_dsm_varied.m](/dsm/originations_dsm_varied.m). We set the interaction level to 0.5 for Input Data and Knowledge Sources, for Decisions we set it to 2.

| **Parameter**          | **Value** |
| --- | --- |
| `pow_cc`           |     1 |
| `pow_bid`          |    -1 |
| `pow_dep`          |     4 |
| `max_cluster_size` |    31 |
| `rand_accept`      |    62 |
| `rand_bid`         |    62 |
| `times`            |     4 |
| `stable_limit`     |     4 |

We set `times` and `stable_limit` to 4 to let the algorithm run for a longer time before reporting results. We set `pow_bid` to -1 to penalize small clusters instead of large ones.

| **Mean** | **Median** | **# clusters** |
| --- | --- | --- |
| 0.58831 | 0.61042 | 6 - 8 |

With respect to the [Varied interaction levels](/results/07-varied-interaction-levels) experiment we have.

- Similar likeness mean and median.
- Same delta between the maximum and the minimum number of clusters (i.e., 2).
- Smaller minimum and maximum number of clusters.

We get clusters of size 1 and 2.