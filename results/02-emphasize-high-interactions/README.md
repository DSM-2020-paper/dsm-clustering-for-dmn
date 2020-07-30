# Emphasize high interactions

Clustering algorithm applied to [originations_dsm.m](/dsm/originations_dsm.m).

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
| 0.53431 | 0.5501 | 5 - 9 |

There's no much difference in results with respect to the [Penalize small clusters](/results/01-penalize-small-clusters) experiment.