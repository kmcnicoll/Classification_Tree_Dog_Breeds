# Classification_Tree_Dog_Breeds

Using Data from https://www.hillspet.com to see if American Kennel Club dog breed classification standards could be predicted from dog traits.
The data
Hills Pet, https://www.hillspet.com dog suppy company that has information and care data on every breed. It's purpose is to provide information to potential customers so that the prospects buy their dog food.

# The goal
The aim of this project is to use analyse the dog traits and see if average breed traits such as height, wieghts, tendancy to bar, energy level, ect, can be used to accuratly predict the AKC classifiction of the breed.

# Statistical tests used
In order to find the most effective model 9 different tests were done.

![test matrix](Screen Shot 2019-12-12 at 4.17.07 PM.png)


As you can see KNN preformed the best. 
It was determined after a grid search that the best K value for nearest neightbors should be 7. Model lead to the following confusion matrix

![confusion matrix for KNN](Screen Shot 2019-12-12 at 4.17.06 PM.png)

# Limitations
While interesting it must be understood that this project faced major limitations. For instance the total population orignated ad 132 rows and 9 classes which in and of itself prevents usable modeling. In addition that data on the breeds were all physical and no personality traits.

# Conclusion
While the test faced major limitations, a highly accurate prediction for Toy breed was attainible. This is most likely due to its small size. If more data can be attained and specific samples of dogs, it would be interesting to see if there are actually noticlble destinctions, from a data standpoint, on the differences between what is considered to be a Hound, Herding, or Terrier dog.
