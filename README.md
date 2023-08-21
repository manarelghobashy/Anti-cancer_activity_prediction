# Anti-cancer_activity_prediction

The data is in the form of a graph which represents the chemical structure of the compound. Each sample of data contains information about the atoms and the connections between atoms of the molecule. So in this problem, the features are the atoms and connections.
The input file is a structure data file (SDF). It contains information about the chemical composition of a molecule. SDF file store information about the position of an individual atom in the chemical compound and also tells about the connections.


## Steps:
- The first step is to read the sdf file to get information about the atoms and their connectivity in the compound. The atoms are described as nodes and connections are described as edges. The read_sdf method is used to read sdf file and the chemical composition of the compound.
- The nodes are given as characters (like [O, N,...]). Thus it is treated as a sequence of text data and the best way to describe the text data sequence is to tokenize the data and then add the embedding layer. Graph convolutional network is used to calculate the probability of the output class. Different methods differ in implementing message-passing methods.


- Data from: https://www.kaggle.com/competitions/cisc873-dm-w23-a6/data
- 
