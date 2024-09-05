## Main
Here we are comparing the different algorithms deployed.

| S.No | Algorithm | Description | Paper URL |
|------|-----------|-------------|------------|
| 1    | Isolated  | Isolated algorithm make decisions on the next hop for representations solely based on local information available to the individual node. They don't communicate with other nodes to gather a broader network view. This can lead to suboptimal routing, especially in dynamic or congested networks, as nodes may not be aware of more efficient paths |            |
| 2    | Central  | Centralized algorithm rely on a central node that possesses complete knowledge of the network topology. This entity calculates the optimal routing paths for all representations and distributes them to the nodes. |            |
| 3    | Random    | Random algorithm choose the next hop for representations at random. This is a simple approach, but it can lead to very inefficient routing, with representations taking unnecessarily long paths or even getting stuck in loops. |            |
| 4    | Ring      | In a ring network, representations circulate in a predefined direction (clockwise or counter-clockwise). Each node forwards the packet to its neighbor in that direction. This is a simple and robust approach for dedicated ring topologies. |            |
| 5    | Grid      | In grid networks, nodes are arranged in a two-dimensional lattice structure. Routing algorithms for grids often employ techniques like XY routing or dimension-order routing, which exploit the grid structure to efficiently determine the next hop towards the destination |            |
| 6    | Torus     | A torus network is a grid network with "wrap-around" connections at the edges. This allows representations to exit from one edge and re-enter from the opposite edge, creating a continuous path. Routing algorithms for torus, leverage similar principles as grid routing while accounting for the wrap-around connections. |            |
| 7    | Similarity based (top-k) | Similarity-based (top-k) algorithms utilize similarity measures to compare the data packet's destination with the characteristics of neighboring nodes. Nodes with higher similarity to the destination are more likely to be chosen as the next hop. This can be effective in content-based routing scenarios where representations aim to reach nodes with specific content or properties. |            |
| 8    | Swarm     | Nodes in the network communicate and share information about their local routing experiences. This collaborative approach can lead to adaptive and efficient routing, particularly in dynamic networks. This is inspired by the collective behavior of biological swarms. |            |
| 9    | L2C       | L2C algorithms use a model encoder to learn collaboration weights that optimize performance on a local validation set. Nodes dynamically adjust their collaboration strategies based on these learned weights, allowing for more effective peer-to-peer communication. This approach is particularly useful in decentralized networks where data heterogeneity is significant, as it enables nodes to prioritize collaboration with those whose data distributions are more aligned with their own, leading to improved convergence and overall performance. |            |
|10    | Meta-L2C  | This algorithm is a better generalization of L2C that performs meta-learning in order to improve the performance on few-shot collaborator selection problem.|       |
|11    | Def-KT    | Decentralized Federated Learning via Mutual Knowledge Transfer is an algorithm that performs knowledge-distillation to improve the performance in a p2p setting.| [https://arxiv.org/abs/2012.13063](https://arxiv.org/abs/2012.13063)|
|12    | FedFomo   | Personalized Federated Learning with First Order Model Optimization applies an optimization approach to change aggregation weights across nodes to improve the performance of model aggregation.| [https://arxiv.org/abs/2012.08565](https://arxiv.org/abs/2012.08565)|
		
