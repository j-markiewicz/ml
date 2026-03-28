# Machine Learning

## [Exercise 1 - Clustering](./1/047Clustering_Exercises.ipynb)

- [x] Modify the HCM code to work for three groups. This exercise can be divded into four tasks:
  - modify the parameters,
  - modify the calculate_u function,
  - execute the clustering,
  - plot the results.
- [x] For density clustering, plot the feature space with all element marked with different color, depending on the cluster that it's assigned to. You should do the following tasks:
  - fill the get_color method,
  - fill the plot code.
- [x] Build a method that plot baed on dendrograms_history and pydot, a dendrogram for the divisive clustering method. You should base on agglomerative method, but keep in mind that it works top-down instead of bottom-up. This exercise need just one function to be implemented:
  - [show_tree_divisive](./1/tree_diana.png)
    You should loop over the dendrogram_history variable and loop over childs.
- [x] Implement the $s_{2}$ metric
- [x] [Draw the borders between clusters in the output image (for 5.0 grade)](./1/segmented.png)

## [Exercise 2 - Linear Regression](./2/026_Exercises.ipynb)

- [x] Use the cross-validation method to test the linear regression with different $\alpha$ values, at least three.
- [ ] Implement a SGD method that will train the Lasso regression for 10 epochs.
- [ ] Extend the Fisher's classifier to work with two features. Use the class as the $y$.
