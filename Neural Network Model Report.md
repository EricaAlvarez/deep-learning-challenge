# Neural Networl Model Report

# What variable(s) are the target(s) for your model?
The variable target is the "IS_SUCCESSFUL" column from the dataframe.

# What variable(s) are the features for your model?
After dropping the 'IS_SUCCESSFUL' column from the original dataframe, The feature variables were every two column from the dataframe.

# What variable(s) should be removed from the input data because they are neither targets nor features?
The variable removed were "EIN" and "NAME".

# How many neurons, layers, and activation functions did you select for your neural network model, and why?
In the first attempt, at hidden_nodes_layer1 I used 7, at hidden_nodes_layer2 I used 14, at hidden_nodes_layer3 I used 21, just as a first attempt.

# Were you able to achieve the target model performance?
No, in this ocation I did't get to the request point of 75% accuracy.

# What steps did you take in your attempts to increase model performance?
I tried adding more layers, removing columns, adding hidden nodes, and changing activation functions to improve model accuracy.

# Summary:
The deep learning model achieved an accuracy rate under 75% on classification. To improve prediction accuracy, it would be beneficial to use a model that has a stronger correlation between input and output. This can be achieved by performing additional data cleanup at the beginning and experimenting with different activation functions. Iterating until higher accuracy is achieved could also be an option.