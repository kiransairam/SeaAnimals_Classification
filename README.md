# SeaAnimals Image Classification

Aquatic environments have been the birthplace of most life forms, with the oceans providing approximately 90% of the world's living space in terms of volume. The first known vertebrates were fish, exclusively found in water. Some fish evolved into amphibians, capable of surviving both on land and in water for parts of the day. Among amphibians, certain subgroups, including sea turtles, seals, manatees, and whales, further evolved into reptiles and mammals. Plant life, such as kelp and other algae, support some underwater habitats. The ocean's food chain relies on phytoplankton, crucial primary producers.

Aquatic environments are home to a diverse array of organisms, including microscopic phytoplankton, which serve as the base of the ocean food chain. Phytoplankton are important primary producers, using energy from the sun to produce organic matter through photosynthesis. They are an essential food source for a wide range of organisms, from zooplankton to large predators like sharks and whales. And We are in this project to detect the 23 different types of sea animals,using the Neural Network models.

We actually have a large dataset with 12000+ images in which we divided into the train 8000 test 2000 and validation dataset 2000 and good number of images for each variable, so we did not perform the “Data Argumentation” in our dataset.so i directly performed the models on our dataset. Below is the list of Models I did on my project.

1. BaselineModel
2. BaselinewithMultilayerandDropoutlayer
3. DepthwiseseparableandResidualBlock
4. TransferLearningUsingthefeatureextension(DenseNet169)
5.  TransferLearningUsingthe“ResNet101”

Fine Tuning helped our model to improve a lot, it got the accuracy of 93% and validation loss 88%, this is the best output results we got.

● The overall accuracy of the model on the test set is 0.636, which means that it correctly predicts the class label for 63.6% of the instances in the test set.

● Looking at the individual class metrics, it appears that the model performs well on some classes, such as Sea Urchins, Otter, and Turtle_Tortoise, with high precision, recall, and F1-score. On the other hand, the model performs poorly on some classes, such as Eel, Octopus, and Sharks, with low precision, recall, and F1-score.

● The macro average, which is the unweighted mean of precision, recall, and F1-score across all classes, is 0.617 for precision, 0.605 for recall, and 0.608 for F1-score. The weighted average takes into account the support for each class, and is therefore more representative of the overall performance of the model. The weighted average precision, recall, and F1-score are 0.634, 0.636, and 0.632, respectively.
  


