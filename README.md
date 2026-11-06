# 7. Conclusion

## Explain whether the analysis supports the idea that the world cannot be divided into only two groups.

The statistical analysis reveals that the world cannot be divided into solely two groups, as utilizing only the first two clusters only explains 37% of the variance in the data.

## For your final clustering solution, choose one country from each cluster to represent and explain that cluster.

We pick Luxembourg from the developed cluster.

We pick Cuba from the developing cluster.

For each selected country, discuss:

### Why does this country appear to belong to this cluster?

Luxembourg is grouped with other countries of relatively higher economic means and infrastructure, such as France and Germany. Meanwhile, Cuba belongs in the group of relatively lower economic means and infrastructure, like Angola and Botswana.

### Does it look similar to the other countries assigned to the same cluster?

Yes, the countries share many characteristics with other countries from the same respective group.

### What characteristics distinguish this cluster from the others?

The cluster that Luxembourg belongs to has lower infant mortality, longer life spans, and higher GDP per capita. Likewise, Cuba's group has higher infant mortality, shorter life spans, and lower GDP per capita.

### Is there anything surprising about the countries grouped together?

Given the chosen indicators of development, the grouping of countries is sensical given that the more developed countries have better economic performance and improved life conditions.

## Can the world be meaningfully divided into only two clusters (developed vs developing)?

No, the world cannot be meaningfully divided into only two clusters.

## How many clusters are actually suggested by the data according to the Elbow Rule?

The Elbow Rule shows us that four clusters work for this scenario.

## How much of the data structure is explained by two clusters compared to the optimal number of clusters?

50% of the data structure is explained by the first four clusters, as opposed to only 37% explained by just two clusters.

## Does the evidence support the claim in *Factfulness* that the world cannot be divided into only two groups but into 4?

Yes, the evidence found here does support this claim, as more of the data structure is explained by four groups rather than just two.

## Why is scaling required before clustering?

Scaling is required before clustering in large datasets to create comparability. Scaling prevents variables with large absolute magnitudes from absolutely dominating variables with smaller ranges. Typical methods of scaling include the `StandardScaler`, which produces a zero mean and a unit variance of 1 on fitted data. Another technique would be the `MinMaxScaler`, which rescales data to a bounded range. Either of these techniques is recommended before clustering any distance-based algorithms.