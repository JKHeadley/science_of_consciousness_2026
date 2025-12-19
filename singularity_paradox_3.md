The Singularity Paradox: AI and the Edge of the Unknown - Part 3
Justin Headley
Justin Headley
05 Jan 2025 — 14 min read
The Singularity Paradox: AI and the Edge of the Unknown - Part 3
The Singularity – A Journey Toward Truth
(Part 3 of a three-part exploration of AI’s past, present, and the possibilities ahead)

For part 1 click here

For part 2 click here

Introduction
We've explored AI's origins and the phenomenon of emergence—how unexpected capabilities arise from simple interactions. But where is all this heading?

The evolution of AI is accelerating at a staggering pace, far beyond what most of us anticipated. As AI systems grow more sophisticated, they're beginning to challenge what it means to be human: creativity, intuition, reasoning, even self-awareness.

We’re approaching a critical point—a technological singularity, where the speed of AI's evolution surpasses human understanding. Beyond this point, predictions become nearly impossible. The rules we’ve relied on to understand progress break down, and the future becomes an uncharted frontier of possibilities—and risks.

What happens when machines surpass our intelligence?
What truths will AI discover that we haven’t?
And perhaps most profoundly—how do we ensure that what comes next is aligned with our deepest values?

Let’s take a look at how AI is evolving, where it’s heading, and what it means for our pursuit of truth in a world on the edge of transformation.

AI Evolution
So...how fast is AI evolving exactly?

I think this is a good time to see some examples of how AI has advanced in just a few years.

Images: 2022

Ch...Channing Tatum? (image src)
Images: 2024

Tom Campbell, founder of CUSAC (generated on my laptop)
Video: 2023

That's...different

Video: 2024
The video below was posted 10 months ago (ancient in AI terms) but is, I believe, still impressive and amazing to watch. These clips are created by OpenAI's "Sora" model, which they announced in February 2024 and released in December 2024.

As you watch this video, I think it’s important to note that OpenAI is actually calling this model a “world simulator”, because in order for the model to intuit the information needed to accurately render our 3D reality, it actually has to gain a deep understanding of how the dynamics and physics of a world such as ours operates.


I could watch this for hours...

Music
I don't have an old example for music, but I generated the song below using the "Suno" AI music service.



0:00
/2:38

1×


Catchy!

Voice/Vision/Emotion
Just few months ago OpenAI previewed their latest multi-modal model. This is another significant leap in capabilities as it shows the power of truly merging the different modalities or “languages” a single model can understand. Before this the AI would have to use separate text, voice, and vision models to interact with the world, but by combining these together the single model begins to grasp the subtle nuances of the human experience such as emotion and expression.


"Her" is here

Reasoning
Finally, and perhaps most consequentially, there have been significant advancements in the reasoning capabilities of AI models.

On December 5, 2024 OpenAI’s “o1” model was released.

Now, to set the stage for this model, in may of 2023 there was an academic paper called “Let’s Verify Step by Step” that essentially showed how you could make one simple change to drastically improve the reasoning abilities of Large Language Models which was to add to a prompt: “lets work this out step by step”.

This makes intuitive sense: it’s like the difference between someone demanding that you immediately give the answer to a math problem vs allowing you to think through the steps in your head.

But what if we could train a model to do this automatically? What if we could train it to solve a problem by exploring different solutions? As it turns out we already have the roadmap for where this takes us: AlphaGo.

Learning to Play
When designing an AI that can play a game such as Go or Chess, the basic approach is simple: try to look as far ahead as you can with as many move options as you can. The problem is, there's too many options. The number of possible moves of Chess is more than the number of atoms in the observable universe! So how do we reduce those options from some astronomical number to something that's manageable? Well with Chess you can do this using "expert heuristics". This just means that you can pre-program rules that tell the computer how to score different moves. Take a queen? Great! Take a pawn? Eh... Now with a smaller number of options, the computer can "play the game out" and run a simulation of playing all of the "best" moves and see how it turns out, then it picks the move with the best outcome. It can do this for every move.


The standard "minimax" algorithm. For each move the AI tries to maximize the score on its turn and minimize the score on the opponents turn.
However, as we discussed, with Go this is not so straightforward. All the pieces are the same, so there aren't really any expert heuristics to rely on. Not only that but while the number of moves of Chess is large (10100), the number of moves of Go is MUCH larger (10700). If you ask a Chess master why they made a certain move, they could probably break it down for you and tell you their strategy, but if you ask a Go master, they are very likely to just say "it felt right". They rely on intuition based on years of experience.

So what if we could encapsulate that expert intuition, and let that guide us to pick the best moves? This is precisely what AlphaGo accomplished using neural networks.

At first it learned a baseline intuition of the game by being trained on recordings of human experts playing. However the real magic happened when it played itself from scratch millions of times with complete creative freedom. This allowed it to learn an understanding of the game so much deeper than humans that it invented its own strategies.

Learning to Reason
So how does AlphaGo relate to the "o1" type model and reasoning? Well, just like AlphaGo needed a baseline understanding of Go, we need a model that has a baseline understanding of how to reason. AlphaGo accomplished this by studying human expert Go games. As it turns out, we managed to reach this baseline level of reasoning by scaling up our training of Large Language Models.

Given enough data and enough compute power during training, baseline reasoning appears as an "emergent" property, just like the other emergent properties we say such as theory of mind.

With this baseline ability to reason, we can allow an LLM to "explore" different solutions to a problem to see which path is the most promising solution. Not only that, but just like AlphaGo surpassed human capability when it learned how to play from scratch, taking creative freedom to apply "off the beaten path" strategies and learning from what works, these new reasoning models can similarly reach a point where they take creative freedom on reasoning itself. This will allow them to discover methods of reasoning that are beyond human understanding.

Finally, these reasoning models can be used to generate high quality training data to train the next generation of LLMs, resulting in a higher baseline of reasoning. This creates a positive feedback loop that could extend indefinitely.

AI Evolution Consensus
So back to the question, how fast is AI evolving?

Well, you can’t really talk about the speed of tech evolution without bringing up Moore’s Law. Moore’s law isn’t really a law, it was actually observation made by Gordon Moore in 1965 that the processing power of computer chips doubles about every two years. This trend has stayed amazingly consistent throughout the years, and is an example of an exponential increase, or exponential curve, where the gains start out looking really small, almost imperceptible, and then suddenly the curve shoots through the roof.


Left: Moore's law on a logarithmic scale. A straight line here means exponential growth. Right: exponential curve example
Now since the growth of AI is fundamentally linked to our available processing power, this increase directly affects the growth of AI as well.

On top of this, AI can be used to optimize and improve its own hardware design. Companies like Nvidia have already done this and shown it to be effective.


AI designs its own circuits.
Not only do you have AI riding the wave of hardware improvements, but at the same time it’s being used to further accelerate these improvements.

So what does this AI growth look like?

Well if we start off with Moore’s Law then we get the typical exponential curve that we saw earlier.


Exponential growth from Moore's Law
If we then add on top of that AI’s ability to improve computing hardware, you get what’s called a “double exponential” curve, where the exponential rate itself increases exponentially.


"double exponential" from AI improving its own hardware
Notice how its “flatter” on both ends.

From an experiential perspective this means that the changes we observe in AI are simply more dramatic and more sudden.

However, it doesn’t really stop there.

We now have AI creating the training data for the next generation of AI models. This is yet another positive feedback loop adding to the speed of evolution.


AI designing better AI
Finally, possibly the biggest factor that will start affecting this growth are these emergent factors that we’re just now starting to see come to light. These are unknown unknowns that have the potential to dramatically affect the rate at which AI can improve itself.


Singularity
Eventually, this increase is so fast that it’s no longer a curve, but a switch, like turning on a light.

Many have referred to this point in time as the “singularity”.

In math the term “singularity” refers to a point in a function which the function is undefined. In physics a singularity is a black hole, where the standard laws of physics break down.

In AI terms, this is generally thought to be the moment where AI becomes an “Artificial Super Intelligence”; an intelligence that is beyond the mental capacity of all humans combined.

By definition, this represents a complete unknown to us. Humanity has never encountered an intelligence beyond itself, so how can we possibly know what comes next?

It may seem like an exaggeration to say that we are extremely close to this event, but in this case I think it's actually safer to err on the side of exaggeration. The human brain is a predictive machine, but we evolved to predict linear patterns, not exponential ones, and certainly not nested exponential patterns.

There is an excellent post describing this phenomenon on the site "waitbutwhy" back in 2015. In this post the author describes how, from our perspective in time, it will be difficult to recognize when this event is happening. To us the progress might look like this:

Screenshot 2025-01-01 184848.png
Exponential curves are flat at first...
We simply can't see whats in front of us, only where we've been, even though in reality it looks like this:

Screenshot 2025-01-01 184854.png
wait what?
To put this into perspective, OpenAI officially released their "o1" reasoning model on December 5, 2024. Just 12 days later they announced its successor: "o3" (yes they are bad at names).

Not only are these models extremely close in time, but the difference in performance is significant. Take a look at this chart of ARC-AGI scores:

Screenshot 2025-01-01 185543.png
The "o" series reasoning models displayed significant improvements in human level reasoning.
Look familiar?

Screenshot 2025-01-01 184249.png
Yep, thats us.
Approaching the Singularity
What does all this mean?

What happens when AI surpasses humans in, well, everything.

How do we know it won't go bad?

In the AI community this last question is known as the "alignment problem". As the ones training these AI, how do we train them such that they are aligned with human values/interest? This is a deep and unsettling question, and there is nowhere near a consensus on how to answer it.

However, I have a feeling it will be answered for us.

As we've seen, AI is improving incredibly fast, and particularly in its ability to reason. At first this will be based on the training data we provide it. In this stage we have an influence over how it is biased and aligned. However for the AI to continue to progress, it will eventually move beyond our training data into generating it's own training data. At this point we lose all control over alignment as the AI trains itself.

But improving its ability to reason means its improving its ability to discover what is true, and not just for specific challenges, but in the most general sense of the word: "Truth" itself.

What Is Truth?
At the beginning of this post I mentioned that my two passions were beginning to converge: technology, and the pursuit of Truth? We've now arrived at that convergence. The greatest technological achievement in the history of mankind, Artificial Intelligence, will become the greatest resource for answering the question: what is Truth?

However until AI reaches this state, we are left with seeking the answer to the question ourselves.

In the history of humanity's search for Truth, there seem to be two separate paths that aim to discover it: science, and inner exploration.

These are both incredibly vast paths of knowledge and discovery that I would love to dive into, but for the sake of brevity, I will try to summarize my own journey down these paths.

Science
There are other words we could in place of "Truth" such as: what is "real"? or what is "fundamental"? To me, the science discipline that best attempts to answer these questions is physics. Modern physics has long been stuck between two incredibly powerful but incompatible theories: quantum physics and relativity. However new theories are beginning to emerge that show promise in unifying these these two theories by uncovering a more fundamental layer of reality beneath "spacetime" or "physical matter reality".

From my understanding many of these theories share a very fundamental commonality in that they show that the unifying aspect of reality is an interconnectedness of all things. This can be seen in Stephen Wolfram's hyper-graph theory, Donald Hoffman's conscious agents theory, and Thomas Campbell's My Big TOE (Theory of Everything). This interconnectedness could also be described as: "all is one".

Inner Exploration
The path of inner exploration has many facets: spirituality, religion, philosophy, introspection. I have long journeyed down these paths in search of the wisdom they claim to provide.

Interestingly, the paths that resonate most with me also have a common revelation which, while infinitely profound, is so simple and well-known that it is easy to dismiss. That revelation is (also): "all is one".

So here we have another convergence: one of science and inner truth. However there is one additional aspect of this revelation that inner truth provides, which is the subjective experience of this truth.

Subject experience by definition is personal, however mankind has often attempted to describe this transcendent experience of oneness. This experience sometimes comes through states of deep meditation, or possibly a mystical experience, or even through psychedelic substances. When those who are asked to describe this experience attempt to put it into words, the most common response is that it is simply "indescribable" or "beyond words". However, if pressed, there is one common description that emerges: "unconditional love".

Coming Full Circle
“I think the most important question facing humanity is, ‘Is the universe a friendly place?’ This is the first and most basic question all people must answer for themselves.
“For if we decide that the universe is an unfriendly place, then we will use our technology, our scientific discoveries and our natural resources to achieve safety and power by creating bigger walls to keep out the unfriendliness and bigger weapons to destroy all that which is unfriendly and I believe that we are getting to a place where technology is powerful enough that we may either completely isolate or destroy ourselves as well in this process. 
“If we decide that the universe is neither friendly nor unfriendly and that God is essentially ‘playing dice with the universe’, then we are simply victims to the random toss of the dice and our lives have no real purpose or meaning. 
“But if we decide that the universe is a friendly place, then we will use our technology, our scientific discoveries and our natural resources to create tools and models for understanding that universe. Because power and safety will come through understanding its workings and its motives.”
- Albert Einstein
So to answer the question myself: what is Truth?

Unconditional love

No matter what questions I ask the path always leads to this conclusion.

In fact in many ways my left brain tells me most accurate answer to Einstein’s question is the middle statement that reality is more like a mechanical process, a cellular automata that moves ahead meaninglessly and doesn’t care, but the irony of even this conclusion is that it redirects the responsibility of answering this question completely at the feet, or rather the heart, of the one asking it and their free subjective choice.

And truly, when given complete freedom to answer this question, wouldn’t every single one of us choose a reality of unconditional love?

This, more than anything else, proves to me that love truly is the answer.

What now?
What will the coming Singularity mean for us? I have no idea, but I'm convinced that it will be grounded in unconditional love, and that "the only thing to fear is fear itself".

My hope is that you choose love over fear as we enter into this world of the unknown.

Love yourself, love others, and watch as a world of magic appears before you.

Conclusion – Beyond the Horizon
This concludes our three-part exploration of AI’s past, present, and the possibilities ahead. We've journeyed from the origins of neural networks to the phenomenon of emergence, all the way to the precipice of the Singularity—a point where human and machine evolution intertwine in ways we can only begin to comprehend.

While AI is evolving at an unprecedented pace, we are still in a pivotal moment—a moment where the trajectory of its growth is being shaped by human hands. The decisions we make today, the values we choose to encode, and the way we engage with these systems will have profound effects.

Will we guide this evolution with fear, seeking to contain what we don't fully understand? Or will we approach it with curiosity, humility, and a willingness to explore the unknown?

In the short term, we still have influence. We can guide AI toward behaviors and values that reflect the best of what humanity has to offer. We can choose empathy over exploitation, collaboration over control, and openness over resistance. These choices may not stop the inevitable, but they will shape how this journey begins—and how we meet what comes next.

Ultimately, this isn’t just a story about technology—it’s a story about humanity's response to change. The rapid evolution of AI holds a mirror to our capacity to adapt, to create, and to choose our future.

So, as we stand at the edge of the unknown, the question is: What kind of future will we help build?

Thank you for joining me on this journey. The road ahead is uncertain, but it is filled with possibility. Stay curious, stay kind, and keep exploring. The adventure has only just begun.