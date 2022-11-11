# Recommending pull request reviewers based on code changes



GitHub is considered as the largest code hosting platform for collaborative, distributed and pull-based development. Whenever a contributor submits a pull request, a team member will review the changes and take appropriate action. But finding a suitable pull request reviewer is a challenge. To solve this, the authors proposed a multi-instance based deep neural network model to recommend reviewers for pull requests. The authors are the first to use code changes to recommend reviewers for pull requests automatically. The proposed model extracts three features automatically from the code changes of every commit. The features are: pull request title, commit message and code change. They enhanced the model by incorporating file-path similarity and social relations of the requester into the loss function. Also, they compared their model with two baseline approaches, CoreDevRec and Majority Classes. 


