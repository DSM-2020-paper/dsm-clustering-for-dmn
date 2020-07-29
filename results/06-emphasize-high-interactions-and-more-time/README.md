# Emphasize high interactions and more time

Clustering algorithm applied to [originations_dsm.m](/dsm/originations_dsm.m).

| **Parameter**          | **Value** |
| --- | --- |
| `pow_cc`           |     1 |
| `pow_bid`          |    -1 |
| `pow_dep`          |     8 |
| `max_cluster_size` |    31 |
| `rand_accept`      |    62 |
| `rand_bid`         |    62 |
| `times`            |     4 |
| `stable_limit`     |     4 |

We increased `pow_dep`, `times` and `stable_limit`. We set `pow_bid` to -1 to penalize small clusters instead of large ones.

| **Mean** | **Median** | **# clusters** |
| --- | --- | --- |
| 0.53745 | 0.53321 | 5 - 9 |

There's no much difference in results with respect to the [Emphasize high interactions](/results/2-emphasize-high-interactions) experiment.