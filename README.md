## Performer MPC

### Abstract
Despite decades of research, existing navigation systems still face real-world challenges when deployed in the wild, e.g., in cluttered home environments or in human-occupied public spaces. To address this, we present a new class of implicit control policies combining the benefits of imitation learning with the robust handling of system constraints from Model Predictive Control (MPC). Our approach, called Performer-MPC, uses a learned cost function parameterized by vision context embeddings provided by Performers---a low-rank implicit-attention Transformer. We jointly train the cost function and construct the controller relying on it, effectively solving end-to-end the corresponding bi-level optimization problem. We show that the resulting policy improves standard MPC performance by leveraging a few expert demonstrations of the desired navigation behavior in different challenging real-world scenarios. Compared with a standard MPC policy, Performer-MPC achieves >40% better goal reached in cluttered environments and >65% better on social metrics when navigating around humans. 

### Paper Link

### Supplementary Video

[<img src="https://img.youtube.com/vi/uu8-c5H50e8/maxresdefault.jpg" width="90%">](https://youtu.be/uu8-c5H50e8 "Supplementary Video")

### Scenarios
[<img src="https://img.youtube.com/vi/mWDiplwBF2c/maxresdefault.jpg" width="45%">](https://youtu.be/mWDiplwBF2c "Scenario 1")  [<img src="https://img.youtube.com/vi/lOGytuLteTg/maxresdefault.jpg" width="45%">](https://youtu.be/lOGytuLteTg "Scenario 2")


[<img src="https://img.youtube.com/vi/GTQz_tsbeP0/maxresdefault.jpg" width="45%">](https://youtu.be/GTQz_tsbeP0 "Scenario 3")  [<img src="https://img.youtube.com/vi/4O6WNSXfk7k/maxresdefault.jpg" width="45%">](https://youtu.be/4O6WNSXfk7k "Scenario 4")
