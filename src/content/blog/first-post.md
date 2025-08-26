---
title: "Birb"
description: "Delve into the rabbit hole of boidion interactions between objects."
pubDate: "Aug 25, 2025"
heroImage: "/blog-placeholder-3.jpg"
---

I've always been fascinated by birbs. Their fluid movements, whilst elegant, also unsoundly effecient. Take for example the migrating geese. Although all they really do is come here to poop around and leave after they're done, they utilize a "V" path flying to reduce the amount of work having to be done by the birbs behind the frontmost one, similar to how nascars "draft" of eachother by sticking to the tail of the the cars in front of them to reduce fuel usage and reduce the stress on their engines.

I'm still struggling to decide what to have the color of the boid to represent. I could use speed, but that would be better represented with the boids length. I could also represent it with how many birbs there are i 

My math is correct for their interactions, but it is highly unoptimal. I can feel my cpu melting under the stress of less then 1000 boids, and it really was just quickly put together. Some optimizers that come to mind immediatly include remembering if I had already calculated their interaction, so I don't do it twice, changing how i check their interactions form a for loops iterating through every birb to maybe a hashmap? It's been a while since I took Data Structures and Algorithms, so some brushing up would be required however.

It would also be neat to create different species that have different tolerances for each other such as "friendly," which they would exhibit boid behavior towards; "neutral," in which they wouldn't attract, but they wouldn't mind them either; and "avoidance," these birbs aren't fearful of the other birb group as if they were a predator, but they don't mix well either.

My next steps would involve adding a predator for my birbs to avoid, and if time allows, perhaps using this as an excuse for learning about 3d rendering. My endgoal for this function is to make a sort of "island" for the birbs to interact with, by avoiding obstacles and predators, and grouping near water and their nests. 