---
layout: post
title: Day 24 Insert, Update, Delete & More Deep Learning
description: Today we learned about Insert, Update & Deletes
summary: Today we learned about Inserts, Updates, & Deletes in SQL. All of these functions do exactly what they say. I spent some more time diving into recurrent neural networks after class. 
---

Class today continued the theme of easeful SQL intro. We learned about how to insert new records, update exisiting records, and delete records. We also learned about the START TRANSACTION function which allows us to combine bulk database actions which run together and can be rolled back if there is a failure or committed if they succeed. The concepts here are pretty straightforward so today was mostly a practice in syntax.

SQL just isn't captivating my interest in the way that Java was able to. I hope this will change next week when we integrate SQL with Java. For now, I'm spending a lot of time reading about deep learning. Andrej Karpathy's [twitter page](https://twitter.com/karpathy) has been an especially stimulating source of reading material. He's an AI Engineer at Tesla. The amount he tweets about integration of biology and AI has me on the edge of my seat with a mix of curiousity and fear. This is the field I want to be in.

I spent some time today setting up a development environment to run Andrej's [char-rnn](https://github.com/karpathy/char-rnn): installing ubuntu, then torch (a machine learning framework), then lua (the programming language Andrej's code uses). I also finished the concatenation of my 279 eBooks and now have a 177 MB txt file on which to train the char-rnn. Getting closer to running code! 

This is now deviating quite a bit from Tech Elevator, but just a note about what I have found so fascinating about recurrent neural networks:

A recent Hidden Brain podcast (*[When Things Click: The Power of Judgement-Free Learning](https://www.npr.org/2020/02/03/802422904/when-things-click-the-power-of-judgment-free-learning)*) re-introduced me to operatant conditioning as a way of learning. Shankar talked about experiments where a rat in an electrically charged cage would eventually find the switch to turn it off. He described the process as running around randomly exploring the cage until it figured out what worked. We learn by exploration, trying many different things until we find rewards or punishments. Then we feed our new knowledge of rewards or punishments into our new quests. This allows us to become extremely skilled at tasks we've seen before. 

Recurrent neural networks learn by trying different things and then comparing results against a validation dataset. Similar to the rat seeking the reward of the electricity being turned off, the network is seeking proximity to the validation dataset. Each time it runs through the learning data, it gets better and better. It takes what it learns and applies it to the next attempt. It learns in the same way the rat does, the same way we do. But the computer can fail and adjust at a rapid pace.

Thinking about these neural networks has given me insight about my own learning processes. Specifically, how important it is to fail resiliently. The faster we fail and respond, the faster we learn. In the Hidden Brain episode linked above, Shankar interviews a dog trainer who brought clicker training into his day job--training orthopedic surgeons. He uses the clicker to mark specific physical tasks. The clicker allows students to fail without the emotional strain of disappointing the teacher. It's a simple, nonverbal indication of success. It's an algorithmic approach to teaching which gives students the room to explore and receive immediate validation against the knowledge base of the trainer. 

Software that runs so analogous the processes of human brains captivates and astounds me. Where do we go from here?