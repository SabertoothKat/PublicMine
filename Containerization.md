## Containerization, a *love* story
#### A short overview of how we got here.

Ever since the dawn of [8-bit](https://en.wikipedia.org/wiki/8-bit) computing, we humans have dreamed of how to increase the bits while decreasing the price. 
Under price, I mean physical space, sound pollution, electricity costs, and at least Bob the Admin's wages. All of this can be summarized under what we call *cost*. 
And boy can Bob's lunch sometimes be costly! 

So, long story short, it all started back in the day when computers, in order to be portable, needed a [ship and a crane](https://www.computerhope.com/issues/ch000984.htm) No, seriously!

This was the first dream of computational power, a crude analogy Icarus flying over to pay the Sun a visit, all neatly dressed in his waxed up wings. 
Then, Bob (IBM in this case), wanted to change the way we think about the server room. 

To increase the density, you need the technology to decrease the cost. The server room's size won't increase indefinitely! 
This is where the bookshelf-a-like technology of 'blades' came into play. The major players (Dell, HP, IBM) thought it would be cooler to compare these to knives in a holding rack (hence the blade analogy), but to me, they'll always look like [books in a shelf](https://www.broadberry.co.uk/system_files/images/system_type_trans/8.png).

[**You be the judge.**]((https://s3files.core77.com/blog/images/2014/02/OnOurTable-Box-Knife-Block.jpg)

What I'll judge next is that this wasn't enough. Not by a long-shot. What came next was [virtualization](https://en.wikipedia.org/wiki/Virtualization). 

Virtually, this meant cramming more services onto each one of those, ugh, "blades". You could pudding your way out of hardware limitations, by literally (or rather, virtually) abstracting the hardware layer into dedicated resources.


This... helped. 

And for a long time, that is. 

But, nature has a way of its own, as does Google, who released an open-source variant of their Borg system. Yes, Star Trek all the way!

What's a "borg" you might ask? 

Well, you're in for a wild ride, but let me summarize that for you. 

Computers were rooms. 
The rooms became smaller and smaller. 
Smaller and smaller meant individual servers. 
Individual servers became (sigh) "blades".
"Blades" started hosting more and more applications. 
More and more applications meant we need a way to divide what we have more efficiently. 

Fanfare, enter in 'containerization'.

Every application needs an exactly prescribed amount of 'stuff' to run, think of it as your air and water. Containerization offers just this, a container full of *only the "bear" necessities* for it to run. 

Each library, prerequisite, piece of code, script, RAM/CPU amount, IP address segment, everything can be crammed into a single container. 
So, now, not only could you segregate the hardware into exactly cut slices of the 'blade' (see why blade doesn't work here?) for each application you have. 

Neat, right? Yes!

So, like a story from each 'book in the shelf' (a-ha!), each application now is its own container. 

On paper it's perfect! 
But container on paper also can mean 'a garbage disposal object'. 

Stay tuned for more on that subject!


