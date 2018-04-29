---
layout: post
title:  "Learning, starting to understand, and appreciate Git"
date:   2018-04-29 21:35:43 +0100
categories: blog
published: false
---
Some very quick, unedited thoughts on things I've found out this evening. Apologies in advance for how rough and ready it is, I'm mostly writing this down to help solidify what I've worked out this evening.

I've been fiddling with my website this evening and figuring stuff out about Git (perhaps just version control?) that I was somewhat aware of but not entirely clear on the application of. I've been wanting to try different themes on my site but had been having some trouble getting them to work. The reason for the problems seems to be that I can't just use the config I have and transplant that into a new Jekyll theme - at least I don't think so, I don't know enough to be sure!

What do I do then? Well... you clone your desired theme, plug your stuff into it and start configuring? Kinda, initially I made the mistake of trying to push my commits back to the original repository! Thankfully other people already knew idiots like me exist and don't give access to just anybody.

So I need to copy the stuff into my repository... but I don't want to replace my site just yet though! This is where branches come into it - I create a new branch - copy my stuff in and then commit this. The beauty of this is that I can quickly switch back and forward between the 'live' and 'in development' branches and work on one or the other. 

It makes me want to pay for an account or have work pay for an account so I can create some private repositories!