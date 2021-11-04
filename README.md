# Breast-Cancer_NN
An entry-level neural networks project designed to classify tumours as benign or malignant. The data comes from the Wisconsin Breast Cancer research dataset.

A heatmap is a great way to show correlation between features. Here we can see a strong correlation between Uniformity of Cell Size and Uniformity of Cell Shape. Another attribute that might be worth mentioning is Bland Chromatin which has a positive correlation of 0.76 with Uniformity of Cell Size. What that means is that the size of Uniformity of Cell Size increases when Uniformity of Cell Shape increases. We could consider removing Uniformity of Cell Size or Uniformity of Cell Shape as their high correlation may prove to be redundant. We could try building our neural network without removing any columns and see how accurately it performs and then see how the network perfoms after deleting Uniformity of Cell Shape.

Benefits of identifying & treating noise in data:

- enables the algorithm to train faster
- reduces the complexity of a model and makes it easier to interpret
- improves the accuracy of a model if the right subset is chosen
- reduces overfitting
- 
![heatmap](https://user-images.githubusercontent.com/79936222/140314392-f3bfb2f2-0b4c-4856-9532-e72426802bac.jpeg)
