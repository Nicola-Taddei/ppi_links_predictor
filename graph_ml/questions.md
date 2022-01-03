## Here are some questions about the dataset and the code I have to aswer to in order to proceed

* Are there edges between the same ids? --> Yes
  - How frequent?
* Does each id correspond to a kind of protein or deos it represent a specific protein instance (in a tissue, for example)?
* What does multiple edges between the same nodes represent (are they something more that noise?)?
* When we are testing whether an edge between two proteins does exist deos we know the location of each of the two proteins in some ppi graph? (Maibe we can leverage that knowledge)
* How much is the graph clustered? (Clustering coefficient)
* What is the degree distribution?
* How is degree distribution linked to clustering?
* Are links undirected or directed from a logical point of view? (possibly undirected)
  - The possible lack of direction corresponds to double links between the same pair of nodes or do we have to infer it from a single link?
* What is the feature domain? (R or {0, 1} or something else?)