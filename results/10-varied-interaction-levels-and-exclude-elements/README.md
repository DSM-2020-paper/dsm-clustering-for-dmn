# Varied interaction levels and exclude elements

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

We exclude *Applicant data* and *Risk management strategy*.

| **Mean** | **Median** | **# clusters** |
| --- | --- | --- |
| 0.66831 | 0.6682 | 8 - 12 |

With respect to the [Varied interaction levels](/results/07-varied-interaction-levels) experiment we have.

- Higher likeness mean and median.
- Higher delta between the maximum and the minimum number of clusters (i.e., 4).

We get too many small clusters.