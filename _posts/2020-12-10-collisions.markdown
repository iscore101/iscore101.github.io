---
layout: post
title:  "Collision Replay: What Does Bumping Into Things Tell You About Scene Geometry?"
date:   2020-10-10 3:24:59 +00:00
image: /images/collision.jpg
categories: research
author: "Alex Raistrick"
paper: /pdfs/collision.pdf
venue: preprint
---

We explore learning to predict scene floorplans and distance functions from egocentric images, using only random walk collisions as supervision. Each collision is projected into nearby frames to provide supervision at a distance, and a pixel-condition implicit function learns to predict the distribution of possible random walks from a given visible starting location. It does this despite noisy, sparse, randomly sampled supervision.