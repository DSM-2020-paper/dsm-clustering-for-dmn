# Run for a longer time

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

We set `times` and `stable_limit` to 4 to let the algorithm run for a longer time before reporting results. We set `pow_bid` to -1 to penalize small clusters instead of large ones.

| **Mean** | **Median** | **# clusters** |
| --- | --- | --- |
| 0.53119 | 0.5511 | 4 - 7 |

The likeness mean and median are similar to the ones of [Penalize small clusters](/results/1-penalize-small-clusters) and [Emphasize high interactions](/results/2-emphasize-high-interactions) experiment. The number of clusters varies only from 4 to 7, sometimes we get small clusters (size 1 to 3).

Despite the inconsistency of the results with respect to cluster likeness, the results we get with the above parameters could be useful most of the times. The maximum number of clusters is not that high and DRDs for small clusters could be merged with other DRDs.