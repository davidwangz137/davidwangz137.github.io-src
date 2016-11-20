Title: Mathematical Crossroads
Date: 2016-11-19 9:04
Category: Math

I'm currently at a crossroads with regards to my education. I want to venture further into the field of machine learning which requires skill in continuous mathematics. But my love is for mathematics such as graph theory and discrete optimization. Maybe this is just a temporary infatuation and once I get into the functional analysis and algebraic topology I will forget myself once again.

I've been eyeing Edelsbrunners "Computational Topology" but I feel my algebra and topology is too weak. Then I'll have to tackle differential geometry to understand things like natural gradients. Really the mathematics leans continuous.

But I'm prepared to make the long journey. I mean, I'm going to be a researcher so improving my knowledge and the ability to apply it will only make stronger.

But I've come to appreciate the following polytope:
$$x(\delta(v)) = 1 \quad \forall v \in V$$
$$x(\delta(S)) \geq 1 \quad \forall S \subsetneq V, |S| \geq 3, |S|\>\text{odd}$$
$$x_e \geq 0 \quad \forall e \in E$$

This describes the convex hull of all perfect matchings on $G = (V,E)$. This and its dual (given an objective vector $w$) give great intuition for understanding Edmond's Blossom algorithm for general weighted matching where changing the value of the dual variables correspond to shrinking and unshrinking of nodes. I still have to read through the textbook for all the full details (but then I can be reading other books).
