# deep-learning-projects

**Problem Overview:**

The XOR problem is a classic in neural network research. It involves predicting the output of an XOR gate, where the output is 1 only when one input is 1 and the other is 0. This problem can't be solved with a single-layer network due to its non-linearity, highlighting the need for multi-layered networks.

**Truth Table :**

<img width="185" alt="image" src="https://github.com/kulfi-12/deep-learning-projects/assets/128511001/b23c317d-ffbe-4d26-883a-45c633b7f465">



**Correct Classification**: First type of results are two different cases where the regressor finds correlation between data points on the diagonals of the domain.

![JnqurN1svdw3BEIYYiK3xERoX6BRm_N37QXY6d9Bo8MRqs4IGf63RsVAIh6W-z1UwNcPAODScLp6sz_AaAh7myol64Pym9TL5n6Eh297_k1K0Vlg73rwYMnJ3LQg](https://github.com/kulfi-12/deep-learning-projects/assets/128511001/609ec7f0-7fd1-42b5-ac2a-ceba44cfa4fb)
![OcGFJrZcL2RJwZIXGxwsJkkqha6D_DE53vIjaB0dNKCP46lCf-GgjmFxzCYX0xt2VfT35W-ylEjb-mlljzW9rtG3bBtQg2_u-oF_3UAk-p55AFb6DNxZBLPHwSzT](https://github.com/kulfi-12/deep-learning-projects/assets/128511001/d6bfcc40-0f6d-48e1-841f-5ff7d064ac91)

****Challenges and Anomalies****

➢ **Not Converging:** Random weight initialization can produce values which lead to NN not
converging within max iteration threshold, thus producing this "stuck" result.


![9inCw3dpCyq2Ue3-fAXCdRm9R5MQX2-F-qLFH3FbxmmNc-T6qenjxrcEi6yi4aVEM0wzq5a077zotDcuNnztHuyVXUcmt0dsia5KV5a40EwkSk3-vgFsLtXq9e5U](https://github.com/kulfi-12/deep-learning-projects/assets/128511001/45bcce99-353d-4299-832c-c95b206ac19b)

➢ **Anomalies:** Increasing the number of hidden layers and neurons in each layer, can push the network to converge faster but also causes NN to produce peculiar results.


![HRAr89dAducQPZxoMRyZTd26-A5uIrzEZOA1WZgWhP4LxK_QfN4D_RZpwWzpaXtTEKgmMFsVDYAkPPsU7iRYWdGNLRjjRbbehaz3FwSAEP_-8Xhbyz1NDfHakh3T](https://github.com/kulfi-12/deep-learning-projects/assets/128511001/c581028a-71d4-4f2e-b0ce-1adddd056a90)

Decoding the XOR Magic: Unveiling the Mechanics of Convergence

This is the gif that shows how the convergence happens in XOR classification

https://github.com/kulfi-12/deep-learning-projects/assets/128511001/fe087073-e370-4aa4-ae5f-5fec66161a32
