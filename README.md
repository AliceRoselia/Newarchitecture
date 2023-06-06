# Newarchitecture
The architecture I want to implement inspired by multiple sources. 
The connection was similar to wavenet, so it could have been "inspired by" it. However, it is natural for those using binary attention to come up with such a connection to pair things together.
This model is based on simple assumptions.
1. Low complexity of RNN is good.
2. Parallel computation of Transformer is good.
3. Attention is good.
4. Satisfying the prior constraints, Occam's razor applies.

RNNs have O(n) sequential computation step and O(n) compute time. Transformers have O(1) sequential computation steps and O(n^2) compute time. This one is a compromise offering O(logn) serial computation steps and O(nlogn) compute time.
