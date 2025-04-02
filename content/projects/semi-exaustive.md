+++
date = '2025-03-26T14:55:29-03:00'
draft = false
title = 'Semi Exhaustive Generation of Safari Rush Hour puzzles'
tags =  ["Projects"]

+++

## The method
The growing need for large amounts of game content has spawned numerous ways of automating the process. Puzzle games are no exception, as they are a prime example of a genre that can be used to generate large amounts of content and test various methods of doing so. This genre can include standalone games or gameplay enhancers that are present in other genres. This spawns a large variety of puzzle types which makes them a great target for generation of interesting content. 

![Exaustive Puzzle Search](/images/semi_exaustive.png "EPS")
Sliding puzzles are one type of puzzle games where the player moves the pieces around the board to reach solutions. Generally, they are games with low variability where generation can become repetitive. Working in favor of exhaustively searching within a space of boards in order to completely solve the game and find the most interesting ones.

In this study, we present the generation of interesting configurations for the sliding puzzle game Safari Rush Hour. The purpose of this research is to validate and build towards procedural generation of every single configuration of the entire search space of Safari Rush Hour using similar approaches. For the generation, the configurations are grouped in clusters according to the pieces they have to reduce the search space into manageable numbers, using only one configuration as representative of the entire group. An estimation of the total configurations and clusters is provided.

