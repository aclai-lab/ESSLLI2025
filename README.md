
# Vector space embeddings of modal logic formulas

This code generates an embedding for modal logic formulas (rows) and Kripke models (columns) by iteratively constructing a satisfaction matrix.

Starting with a small set of formulas and models, it evaluates their truth values in each existing models, and expands the matrix step by step.

Optimization ensures that each row and column remains unique, with the objective of obtaining a sufficiently diverse set of Kripke models that serve as dimensions in the resulting vector space representation.