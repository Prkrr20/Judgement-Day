# Judgement-Day


### Entry 1 - 11/3/2020

This is the story of a Neural Network. But this Neural Network. was created by Parker and myself, Cayde. Parker was a Freshman in highschool, and Cayde was a sophomore. The idea started out very simple: create something that could recognize text. We tried using a basic method from VSauce's "The Stilwell Brain" and tried using that.

then we started to say, "What if we could do more..."

Eventually, we did just that. We wanted to see what two highschool students could do with 2 shitty Lenovo laptops and WAY too much time on their hands.

Then, at God-Knows-What hour of the morning, I recived a text.

I remember rolling over and seeing the all-caps text:
"WHAT IF WE DITCHED THE ALGORITHM AND MADE THE ENTIRE THING A NEURAL NETWORK"

I got up and, not knowing anything about programming (exept for how to make a "dick printer" with a while true loop, because ya know, highschool sophomores are REALLY mature), started to run ideas past Parker.

The next day we were off, trying to figure out how to make the POS work.

looking back, we could have done this so much easier.

But as im sitting here writing this in my 6th bell chemistry class, I realized that we have made a working neurtal neural network from scratch.


### Entry 2 - 11/4/2020

We've finally moved on to v4. Though no matter what we try, we cant get the damn thing to work.

Its time to take a step back and try again. We're gonna fail a lot more so we better get used to it.

1st twitch stream went well. NN is Finally working well enough that its at least not getting stupider


### Entry 3 - 11/5/2020

We've started to advertize PJD more through twitter. We got the Github repository working properly and Parker
started working with Stackoverflow.

We started working with many different test inputs/outputs. The main ones we've tried are

In | Out
-----|---
1, 1 | 1
1, 0 | 1
0, 1 | 1
0, 0 | 0

and

In | Out
-----|---
1, 1 | 1
1, 0 | 0
0, 1 | 0
0, 0 | 1

We were listening to some russian rap, and Parker started laughing. I asked why and he said "WHY THE FUCK IS HE SPEAKING MINECRAFT ENCHANTMENT TABLE???" I'm still laughing.

Tomorrow we hope to start merging neural networks.


### Entry 4 - 11/6/2020

Today we take the next step. taking 2 (or more) neural network and merging them to create one that can give 2 (or more) outputs. here is our data set

In | Out
-----|---
0, 0, 0 | 1, 0, 0
0, 0, 1 | 1, 0, 0
0, 0, 2 | 1, 0, 0
0, 1, 0 | 0, 1, 0
0, 1, 1 | 0, 1, 0
0, 1, 2 | 0, 1, 0
0, 2, 0 | 0, 0, 1
0, 2, 1 | 0, 0, 1
0, 2, 2 | 0, 0, 1
1, 0, 0 | 1, 0, 0
1, 0, 1 | 1, 0, 0
1, 0, 2 | 1, 0, 0
1, 1, 0 | 0, 1, 0
1, 1, 1 | 0, 1, 0
1, 1, 2 | 0, 1, 0
1, 2, 0 | 0, 0, 1
1, 2, 1 | 0, 0, 1
1, 2, 2 | 0, 0, 1
2, 0, 0 | 1, 0, 0
2, 0, 1 | 1, 0, 0
2, 0, 2 | 1, 0, 0
2, 1, 0 | 0, 1, 0
2, 1, 1 | 0, 1, 0
2, 1, 2 | 0, 1, 0
2, 2, 0 | 0, 0, 1
2, 2, 1 | 0, 0, 1
2, 2, 2 | 0, 0, 1

We'll only be giving the neural network about 1/3 of the data and seeing if it can come up with the rest.

First draft of this and it went horribly wrong. But thats to be expected. We'll try again.

We hope to implement a hidden layer. We are not too sure of how this shit will work, we just hope it does.

