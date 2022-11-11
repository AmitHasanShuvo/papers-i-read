
# Commit2vec Learning distributed representations of code changes





In this work, Rocío Cabrera Lozoya el at introduced a technique to represent source code changes capable of representing full commits, which can be composed of changes in multiples methods and in multiple files. 


In more detail, they proposed a model for representing code changes, called Commit2Vec, along the lines of Code2Vec, uses paths from the AST to build a representation of code changes. It feeds the added and deleted AST paths to a fully-connected layer to encode code changes for classifying security-related commits.


They also evaluated the model on industry relevant use cases where limited number of samples were available. 

They came to the conclusion that training on a high relevant pretext task will be more advantageous than training on a lengthy task with larger dataset.
















