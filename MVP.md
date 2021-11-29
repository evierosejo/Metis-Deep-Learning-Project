# Detecting Bee's Health Status through Neural Network  

The goal of this project is to develop a tool for beekeepers to detect their hives health condition. I built an image-based neural network to classify a bee belonging to a hive of the following:
  1. hive being robbed
  2. healthy
  3. few varrao, hive beetles
  4. ant problems
  5. missing queen
  6. Varroa, small hive beetles 


### Sequential Model Summary 
![Screen Shot 2021-11-29 at 5 53 52 PM](https://user-images.githubusercontent.com/84474016/143955459-fa953113-61c5-4231-b6bf-0ec32eb19d6c.png)

I fit the data with 4 epochs and had the following results:

|             | Accuracy |
| ----------- | ----------- |
| train       | 0.87         |
| val       | 0.81        |
| y_test, y_pred   | 0.82        |

Next, I plan on further optimizing the network via the hyperparameters to increase the accuracy of the model. 
