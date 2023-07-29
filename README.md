# NPMCS-GP

## Abstract
Non-overlapping pattern matching focuses on querying data that any two occurrences cannot retrieve the same individual element, which refers to the identical location in the pattern. Regarding its merits of time-saving and rich information, prior researchers have raised approaches in improving the support or number of occurrences under non-overlapping conditions in knowledge mining. However, contrasting with the state-of-the-art works which retrieved the occurrences for each sequence in the database, there are still challenging operations for non-overlapping matching that need to be excavated and elucidated. Inspired by the non-overlapping definition, this study generalized the matching operation cross sequences and proposed an approach called NPMCS-GP, which not only can be applied in meiosis and independent assortment of genes but also the purchase sequences of customers. Based on a second-order Hyper Nettree index structure, we adopted a gapped penalty strategy and pruning operation to fix the non-overlapping pattern matching problem across two sequences under the gap and length constraints. NPMCS-GP first constructed the hyper Nettree index with two target sequences and the given pattern. Contrasting with non-overlapping matching on a single Nettree to seek the rightmost parent and rightmost child node, NPMCS-GP explored the Hyper Nettree. With the gapped penalty strategy, we realized matching cross sequences until an occurrence was obtained, which strictly satisfied the non-overlapping constraint. We also analyzed the completeness and complexity of NPMCS-GP. Extensive experiments have been conducted to prove the correctness and efficiency of the proposed algorithm.

## Dataset
dataset.zip

## 
