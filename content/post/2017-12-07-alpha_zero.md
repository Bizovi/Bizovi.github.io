---
title: On Google's Alpha Zero beating the best chess engine
author: Bizovi Mihai
date: '2017-12-07'
slug: alpha_zero
categories: ["ml"]
tags: ["deep-learning", "chess"]
---

> Chess has taught me how to better deal with `Dynamic Complexity`^[A complex situation with interconnected parts, and the techniques are closely related to visualizations and systematic reasoning, exploration], even though I did not realize this at the time. What I saw in these games by Alpha Zero was a Deep Reinforcement Learning algorithm that captured the essence of chess. It's not the fact that Stockfish got crushed, it's the fashion which brought so much fascination and excitement. [Thinking] What if I could put those rusty chess skills to good use again? 

Why are chess players so excited about this seemingly inevitable event? It was a matter of time since the success of Alpha Go, for it to be adapted to other domains and applications. Also, it's not surprising that a learning algorithm is capable of overcoming a brute-force tree-pruning game-theoretic approach, it's just that no one managed to train a neural network architecture good enough to compete with players, let alone strongest engines. 



> People praise the Zugzwang game, but that is something a human would able to do (probably not against Stockfish). I'm more impressed by the following sacrifice, for a long-term initiative and no clear targets:
<iframe allowfullscreen src="https://chess24.com/en/embed-custom-tournament/condensed/alphazero-vs-stockfish/1/1/10" width="580" height="430" frameborder="0" style="margin:0; padding:0;"></iframe>
                

To answer this question, we have to go back to the DeepBlue vs Kasparov match and the following decades of improved chess engines, which transformed the way players prepare. The best algorithms right now are rated around 3300 ELO and represent the classical approach to AI, before Judea Pearl^[His largest contribution being in introducing uncertainty and probabilistic reasoning as an essential feature of Intelligent Systems]. 


From almost a decade of using chess engines, it was clear that quantity (in terms of computation) beat quality (the human ability to recognize patterns, intuition and creativity). The engine is very skeptical, captures material and defends tirelessly, but despite this unnatural way of playing, it was rarely disproven. Google's Deep Mind team gave an incredible gift to the chess community: that we don't have to do this anymore. The engines are by no means sources of truth and there are ideas much deeper. For me personally, it's the triumph of the Dynamic Complexity over Sequential Thinking and the simulation over determinism. 


> Deep Mind emphasized over and over again activity over material, combining subtle tactics with a grand strategic scheme. The most striking were the long-term, positional sacrifices, resourcefulness in exchanging king's defenders and organizing multiple waves of attack combined with regrouping and conversion, capitalization of positional advantage. 

My interpretation is that the Neural Architecture and the Reinforcement Learning capture highly nonlinear and dynamic, long-term interactions, which give the illusion of an AI/human way of playing. It's still machine learning, but that's one hell of a progress! Now imagine the machine is left to explore theoretical positions in openings, endgames. If the chess players will get to use this tool in the future, a lot of chess theory and historical analysis will have to be rewritten. 

> In the end, what a time to be alive for a former chess player practicing machine learning!
