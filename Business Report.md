

# **Customer Segmentation for Targeted Mall Promotions**


---

## k = 3 Summary

| Cluster | Count | Income Mean | Income Std | Spending Mean | Spending Std |
|---|---|---|---|---|---|
| 0 | 38 | 87.0 | 16.3 | 18.6 | 10.9 |
| 1 | 39 | 86.5 | 16.3 | 82.1 | 9.4 |
| 2 | 123 | 44.2 | 16.0 | 49.8 | 19.7 |

# **Buisness Inference (when k= 3):**


## *   High Income, Low Spenders: 
Cluster 0 has rich 38 homogeneous members with mean income 87k with mean standard deviation 16.27 with mean spending score 18.63 and mean standard deviation 10.92

## *   High Income, High Spenders: 
Cluster 1 has rich 39 homogeneous customers with mean income 86.54k with mean standard deviation 16.31 with mean high spending score 82.13 with with less standard deviation 9.36

## *   Mid Income, Moderate Spenders:
Cluster 2 has mid-income homogeneous customers with mean income 44.15k with mean standard deviation with mean spending score 49.83 but with widely dispersed spending pattern of mean standard deviation 19.69

## **Business must retain their best High Income, High spender homogeneous customers.**



---

## k = 4 Summary

| Cluster | Count | Income Mean | Income Std | Spending Mean | Spending Std |
|---|---|---|---|---|---|
| 0 | 101 | 48.2 | 14.5 | 43.4 | 14.7 |
| 1 | 39 | 86.5 | 16.3 | 82.1 | 9.4 |
| 2 | 22 | 25.7 | 7.6 | 79.4 | 10.5 |
| 3 | 38 | 87.0 | 16.3 | 18.6 | 10.9 |

# **Buisness Inference (when k= 4):**
## * **Homogeneity:** 
Yes, the standard deviations shrank within cluster when K=4. When K=3, the highest spending score deviation was 19.7 for cluster 2, Now when k=4, the high spending score deviation is reduced to 14.7 for cluster 0. So the customers are becoming homogeneous within clusters
## * **Size Balance:**
Yes, Cluster 2 became very small with only 22 customers , when k=4. But they spend a lot with mean spending score 79.4. So it worth campaigning these small customer segments too.
## **Business can focus on campaigning homogenous Cluster 1 and 2 as they high spending score 82.13 and 79.63 with mean standrad deviations 9.4 and 10.5 respectively.**

---
## k = 6 Summary

| Cluster | Count | Income Mean | Income Std | Spending Mean | Spending Std |
|---|---|---|---|---|---|
| 0 | 77 | 56.1 | 8.6 | 49.9 | 6.5 |
| 1 | 39 | 86.5 | 16.3 | 82.1 | 9.4 |
| 2 | 22 | 25.7 | 7.6 | 79.4 | 10.5 |
| 3 | 35 | 88.2 | 16.4 | 17.1 | 9.95 |
| 4 | 12 | 24.6 | 6.7 | 9.6 | 5.3 |
| 5 | 15 | 31.5 | 9.5 | 35.9 | 5.97 |

# **Buisness Inference (when k= 6):**
## * **Homogeneity:**
Yes, the standard deviations shrank within cluster when K=6. Cluster 0, cluster 4, cluster 5 have preferrably low spending score deviations 6.5, 5.3, 5.97. The other clusters mean spending score deviation also fall between 9.4 to 10.5. So business can provide offer to cohesive, homogeneous customer segments.
## * **Size Balance:**
Yes, the size of cluster 4 and 5 shrank so much with size 12 and 15 and with mean spedning score 9.5 and 35.9 respectively. Since every additional segment costs, business can skip campaigning these smaller clusters.

---
## **Business Recommendations:**

## 1.   Yes, We can divide our loyalty membes into a handfule of distict customer segments, based on how much they earn and how they actually spend, so that each segment gets a promotion designed for it.
## 2.   We can have 4 customer segments (Cluster 0 with size 77, Cluster 1 with size 39, Cluster 2 with size 22, Cluster 3 with Size 35) and exclude smallaer clusters 4 and 5, as every additional segment costs campaigning cost.(Refer  k-means statistical anlaysis summary when k=6). 

---
## **Business must focus on campaigning Cluster 0, 1, 2 and 3 and skip campaigning cluster 4 and 5 to save cost as they have few customers 12 and 15 respectively.**
