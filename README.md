# ML_CA03
# Please run my codings in Colab
# 1. Data Source and Contents:
# Read the dataframe and transfer "discrete categories data" to "discrete categories data" in dataframe.
# 2. Data Quality Analysis (DQA)
# I created a new dataframe of train to checking missing values and outliers, and created pie chats to visualized the original dataframe
# Even built the table of statistics and deacription
# 3. Build Decision Tree Classifier Models
# use from sklearn.tree import DecisionTreeClassifier to build the cecision tres classifier models
# 4. Evaluate Decision Tree Performance
# Build models to calculate and sipaly confusion martix(TP, TN, FP, FN, etc) and Accuracy, Precision, Recal, F1 Score
# 5 5. Tune Decision Tree Performance
# Run1 to Run4 are the tunning of arguments
# and plot the accuracy, the accuracy is perfect
# 6. Visualize Your Best Decision Tree using GraphViz
# build decision tree structur and plot the decision tree
# 7. Conclusion
# Q.4 How long was your total run time to train the best model? From box 22, we only spend 0.019s for the total run time to train the best model.
# Q.5 Did you find the BEST TREE? The 'best' tree is a tree with max_depth=8,max_features=0.7,criterion='entropy',min_samples_leaf=30. Actually no. We trained only a single variable separately, which occurred with all other variables at default values, and not for the combined form of the four parameters. If we want to obtain the best model, we need to further tune the parameter crossover.
# Q.6 Write your observations from the visualization of the best tree This is a tree with a depth of 8. There are over 30 data at each leaf node.
# Q.7 Will this Tree “overfit”? From the result on the test set and train set, we find that the effect on the test set and train set are similar, so we are not facing the problem of overfitting problem. It is more like the underfitting problem as the recall is only around 0.56, which means nearly half of the positive cases are not classified correctly.
# 8. Prediction using your “trained” Decision Tree Model
# y_pred is 1, which means the positive class. So the income catgory is over 50k.
