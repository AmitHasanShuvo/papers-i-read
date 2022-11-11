
# CC2Vec Distributed Representations of Code Changes



Patches, which are used to update source code, are created mainly by developers to introduce new features, correct bugs, or maintain functionality.

In this paper, the authors proposed a deep learning architecture named CC2Vec that can effectively embed a code change into a vector space where similar changes are close to each other. CC2Vec optimizes the vector representation of a code change in a patch to predict appropriate words, extracted from the first line of the log message. The log message, used to describe the semantics of the code changes, is written in natural language by the developers. Additionally, they investigated the value of integrating the code change vectors generated by CC2Vec and feature vectors used by state-of-the-art approaches on three tasks (log message generations, bug fixing path identification, and just-in-time prediction).








