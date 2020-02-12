This code implements computation of the tree edit distance using the algorithm proposed by [Zhang and Shasha][1].
 
The tree edit distance is defined as the minimal cost operation sequence of transforming one tree graph into another tree graph by applying one of the following operations: 
- Insertion of an additional node
- Deletion of a node
- Relabeling of a node

The costs of each operation can be provided as a parameter once the distance computation is invoked or be assumed to be unit for each of the operations.

Note that, the trees need to be ordered to ensure the algorithm yields sound results. 

[1]: https://www.researchgate.net/profile/Dennis_Shasha3/publication/220618233_Simple_Fast_Algorithms_for_the_Editing_Distance_Between_Trees_and_Related_Problems/links/59917c2fa6fdcc10d815cebd/Simple-Fast-Algorithms-for-the-Editing-Distance-Between-Trees-and-Related-Problems.pdf