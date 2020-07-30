# Emphasize high interactions and exclude elements

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

We exclude *Applicant data* and *Risk management strategy*. We set `pow_bid` to -1 to penalize small clusters instead of large ones, we increase `pow_dep` to 8.

| **Mean** | **Median** | **# clusters** |
| --- | --- | --- |
| 0.70994 | 0.70361 | 7 - 10 |

The likeness mean and median are similar to the ones of the experiment [Exclude elements with high number of outputs](/results/03-exclude-elements-with-high-number-of-outputs). We still get small clusters. We get clusterings with many clusters.