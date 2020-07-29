# Varied interaction levels and emphasize high interactions

Clustering algorithm applied to [originations_dsm_varied.m](/dsm/originations_dsm_varied.m). We set the interaction level to 0.5 for Input Data and Knowledge Sources, for Decisions we set it to 2.

| **Parameter**          | **Value** |
| --- | --- |
| `pow_cc`           |     1 |
| `pow_bid`          |    -1 |
| `pow_dep`          |     8 |
| `max_cluster_size` |    31 |
| `rand_accept`      |    62 |
| `rand_bid`         |    62 |
| `times`            |     2 |
| `stable_limit`     |     2 |

We set `pow_bid` to -1 to penalize small clusters instead of large ones. We increase `pow_dep` to 8 to evaluate its effect on results.

| **Mean** | **Median** | **# clusters** |
| --- | --- | --- |
| 0.61692 | 0.6124 | 7 - 11 |

With respect to the [Varied interaction levels](/results/7-varied-interaction-levels) experiment we have.

- Similar likeness mean and median.
- Higher delta between the maximum and the minimum number of clusters (i.e., 4).

We get too many small clusters.