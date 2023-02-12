# Mining Code Review Data to Understand Waiting Times Between Acceptance and Merging: An Empirical Analysis

Tags: PR

### Abstract:

This study investigates the code review process to quantify delays and investigate opportunities to potentially increase code velocity. They identified two types of time delays:

1. the wait time from the proposal of code changes until first response
2. the wait time between acceptance and merging.

Their results indicates that reducing the time between acceptance and merging has the potential to speed up Phabricator code reviews by 29–63%.

### Dataset:

1. Dataset that they used for this paper:

[Mining Code Review Data to Understand Waiting Times Between Acceptance and Merging: An Empirical Analysis](https://figshare.com/s/892a48c4fc86bc158e05)

1. For gerrit dataset, the authors have used another dataset and for phabricator thay have mined the dataset from scratch.
    1. https://github.com/kin-y/miningReviewRepo
    2. Phabry (paper and github repo cited in the paper)
2. Collected data about 569,914 code reviews from Gerrit and Phabricator to **quantify the phases of code review process and activities within** and examine the non-productive time for potential solutions.
    1. (A study on Gerrit code reviews categorizes a code review into pre-review time, review time, pre-integration time, and integration time )Lehtonen, Samuel. *Metrics for Gerrit code reviews*
    . MS thesis. 2015. 

### Process

For the project 

- only considered merged PRs
- ignored rejected code reviews or code changes without any activity
- selected code reviews where timestamps follow logical progression
- handled self accepted PRs
- Manual inspection of bots
        
- After applying all filtering: For Gerrit projects, we started with 329,392 code reviews (conducted from 2013 to 2015). After applying all the filters, the resulting dataset contains 164,726 code reviews. For Phabricator, the initial set contains 240,522 code reviews (conducted from 2012 to 2021) and final set 185,317 code reviews.

### Inspection of dataset and taxonomy:

For phabricator:

Link: 

[⚙ D498 Optimize double storing by memset; memcpy](https://reviews.llvm.org/D498)

- has clear indication of who’s the reviwer.

For gerrit:

link: 

[](https://gerrit.libreoffice.org/c/core/+/7199)

- clear description in changelog
