#### Releasing Linear Queries with Correlated Error

##### Offline mechanism: SmallDB

- (from chap2) database $x$ is thought as being collection of records from a universe X, also to represent by their histograms: $x\in\mathbb{N}^{|X|}$, in which entry $x_i$ represents the number of elements in the database x of type $i\in X$

- Lemma 4.3(Sampling Bounds) For any $x\in\mathbb{N}^{|X|}$, and for any collection of linear queries Q, there exists a database y of size $||y||_1=\frac{\log|Q|}{\alpha^2}$, s.t. $\max_{f\in\mathcal{Q}}|f(x)-f(y)|\le\alpha$
  - Question: How to find the y? (constructively)

##### Online mechanism: private multiplicative weights

***

References

- A. Blum et al., A learning Theory Approach to Non-Interactive Database Privacy
- M. Hardt et al,. A Multiplicative Weights Mechanism for Privacy-Preserving Data Analysis