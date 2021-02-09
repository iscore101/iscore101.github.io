---
layout: post
title:  "Collision Replay: What Does Bumping Into Things Tell You About Scene Geometry?"
date:   2020-10-10 3:24:59 +00:00
image: /images/collision.jpg
categories: research
author: "Alex Raistrick"
authors: "Alex Raistrick, Nilesh Kulkarni and David Fouhey"
venue: preprint
---

We explore learning to predict scene floorplans and distance functions from egocentric images, using only random walk collisions as supervision. Each collision is projected into nearby frames to provide supervision at a distance, thus converting a weak signal about the agent's immediate surroundings into a useful signal at a distance. We train a pixel-condition implicit function to predict the distribution of possible random walks from a given visible starting location. It does this despite noisy, sparse, randomly sampled supervision. The method is successful in both predicting scene distance functions / floorplans, and discriminating between categories of indoor structures such as 'Hallway', 'Corner', 'Open Space'.
