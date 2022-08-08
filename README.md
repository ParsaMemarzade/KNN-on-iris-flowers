
# KNN on iris flowers

It's implement of KNN algorithm on iris flowers data.




## Part by Part

### Load Data
irises	(n, s) = (120, 4) ➡️ 120 flowers with lenth of the sepals, width of the sepals, petal length and petal width for each one.

types	(n,) = (120,) ➡️ types of 120 flowers

new_irises (m,s) = (30, 4) ➡️ new flowers with lenth of the sepals, width of the sepals, petal length and petal width for each one.

### Calculate distances
All three function do the same things.
distances between new_irises and each of the irises.
in the array of (m,n).

### Find k-nearest neighbors
find k=10 nearest flowers to new_irises[i] in irises.
k_nearest[i][j] = number of flower (j) in irises that is near to flower (i) in new_irises.

### Find type of k-nearest neighbors
find types of k_nearest flowers and  Put the data into the k_nearest_types

### Find type of flowers
here we make a predicted_types array with (m,) that includes the most frequent types for each flowers.

