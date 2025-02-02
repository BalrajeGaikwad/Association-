# Association-
Association 
Association Rule Mining

Association is a rule-based machine learning technique used to discover relationships or patterns between items in large datasets. It is widely used in market basket analysis, recommendation systems, and fraud detection.

Key Concepts

1. Support: The proportion of transactions that contain an itemset.



\text{Support}(X) = \frac{\text{Count of transactions containing X}}{\text{Total transactions}}

\text{Confidence}(A \Rightarrow B) = \frac{\text{Support}(A \cup B)}{\text{Support}(A)}

\text{Lift}(A \Rightarrow B) = \frac{\text{Confidence}(A \Rightarrow B)}{\text{Support}(B)}

If Lift = 1, A and B are independent.

If Lift < 1, A and B are negatively correlated.


Association Rule Mining Algorithms

1. Apriori Algorithm

Iteratively finds frequent itemsets based on a minimum support threshold.

Used in market basket analysis (e.g., "Milk & Bread → Butter").



2. Eclat (Equivalence Class Clustering and Bottom-Up Lattice Traversal)

Uses depth-first search for finding frequent itemsets.

Works well on small and dense datasets.



3. FP-Growth (Frequent Pattern Growth)

Uses a compact tree structure (FP-tree) to find frequent itemsets efficiently.

Faster than Apriori for large datasets.




Applications of Association Rules

Retail & E-commerce (market basket analysis, cross-selling)

Recommendation Systems (e.g., Amazon's "Customers who bought this also bought")

Healthcare (disease co-occurrence patterns)

Fraud Detection (identifying unusual transaction patterns)




