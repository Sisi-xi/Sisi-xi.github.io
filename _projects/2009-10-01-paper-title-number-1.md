---
title: "Comment Grading for Recommendation System"
collection: projects
permalink: /projects/comment-grading
excerpt: 'This is a group project for Google ML Camp 2020.'
date: 2020-1-17
---
This project focuses on user comments with high quality but few reviews due to release time. We implement NLP methods on prediction of the new-coming comments. Therefore, we are able to select the comments that are likely to be useful, and give them more exposure to other users.

Checkout our project on [github](https://github.com/sunyaofeng8/Turiss).

In this project, we finished:

-   A network that can predict the helpfulness of a new comment based on information like text, user, product ID.
-   A mathematical model(recommendation system) that can place a new comment at a predicted place instead of the bottom(baseline model). This function will largely decrease the cost to rerank a helpful comment and increase the probability that a potentially helpful new comment can be seen by more users.

I am responsible for: 

-   statistical work on dataset
-   build the multimodal part of the network
-   help design the recommendation system
-   do simulation and analysis experiments

[Here](https://github.com/sunyaofeng8/Turiss/blob/master/Turiss_pre.pdf) is our presentation pdf, including illustrations showing our network architecture, recommendation system design, and experiment results. 