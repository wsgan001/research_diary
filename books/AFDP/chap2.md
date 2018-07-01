#### Basic Terms

##### The model of computation

- A trusted curator hold database D, which is comprised of some rows. Each row contains the data of a single individual.
- A query is a function applied to a database.
- Accuracy will necessarily deteriorate with the number of questions asked to ensure privacy or to prevent privacy catastrophes.
- A privacy mechanism takes a database, a universe X, random bits, optionally queries, and produces an output string.

##### Towards defining private data analysis

- The analyst knows no more about any individual in the data set after the analysis is completed.
- The "nothing is learned" approach to defining privacy is reminiscent of semantic security for a cryptosystem: nothing is learned about the plaintext from the ciphertext.
- Why we don't build semantically secure private database mechanism that yield answers to queries while keeping individual rows secret? 

##### Formalizing differential privacy

- Why we need to discuss the input & output space of randomized algorithms?
  - Probability Simplex
  - Randomized Algorithm
  - Distance Between Database
  - Differential Privacy
- What differential privacy promises: by promising a guarantee of $\epsilon$-differential privacy, a data analyst can promise an individual that his expected future utility  will not be harmed by more that an $1+\epsilon$ factor.
- What differential privacy does not promise: differential privacy doesn't guarantee what one believes to be one's secrets will remain secret.
- Qualitative Properties of Differential Privacy
  - Protection against arbitrary risks
  - Automatic neutralization of linkage attacks
  - Quantification of privacy loss
  - Composition
  - Group privacy
  - Closure under post-processing 

##### Final remarks on the definition

- granularity of privacy
- all small $\epsilon$ are alike
-  additional formalisms