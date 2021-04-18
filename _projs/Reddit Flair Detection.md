---
layout: work
title: "Reddit Flair Detector"
description : "Model which predicts the flair of a reddit post from its contents"
caption: This model aims to detect the flair of a Reddit post from '/india' subreddit. The model classifies the flair of a post given its URL into Coronavirus, Nonpolitical, Political and others. The model can also be hosted as a web service.
tags: ["Deep Learning", "PyTorch"]


comments: true
github: https://github.com/Ishan-Kumar2/Reddit-Flair-Detector
---

This model aims to detect the flair of a Reddit post from '/india' subreddit. The model classifies the flair of a post given its content, into Coronavirus, Nonpolitical, Political and others. The model can also be hosted as a web service (done using Flask). The data was scrapped using Reddit's API PRAW
Accuracy was compared taking the input data as Only Title or Title and Content. Various Embeddings and Model architectures were also compared.
