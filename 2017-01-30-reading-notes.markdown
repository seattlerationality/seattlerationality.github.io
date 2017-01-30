---
layout: page
---

[Artificial Intelligence as a Positive and Negative Factor in Global Risk](https://intelligence.org/files/AIPosNegFactor.pdf)
-------------------------------------------------------------------------

### Introduction

Artificial intelligence is dangerous because people are too quick to conclude that they understand it: look at AI's history of promising the moon and then, predictably, failing to deliver.

If the world is destroyed, it'll probably be by accident ('cause basically nobody would *decide* to) -- therefore, the frequent misunderstanding of AI is worrisome.

AI is not settled science: it is very much on the frontier. There's no history to consult to determine tiny annual probabilities of catastrophe, as for asteroid strikes.



### Anthropomorphic Bias

People evolved to model people, and we therefore take personness for granted: we anthropomorphize everything, especially optimization processes (see: Agent Smith, evolution, bug-eyed aliens abducting attractive women).

> Fun example (Barrett and Keil, 1996): study subjects strongly professed their belief in God's non-anthropomorphicness, e.g. omnipresence and omniscience. When asked to retell stories about God in their own words, their answers anthropomorphized God anyway, talking about him doing things in series rather than in parallel. (When asked very similar questions, but with God replaced by a superintelligent computer, they **still** anthropomorphized it.)

If you want to avoid anthropomorphic bias, try studying evolutionary biology, preferably with math. It's *super easy* to come to *super wrong* conclusions by thoughtlessly putting yourself "in evolution's shoes."

The space of possible minds is **inconceivably vast** compared to the subspace of humanoid minds. Anthropomorphizing inhuman optimization processes is terribly, terribly fallible.


### Prediction and Design

It's easy to mistakenly draw conclusions about an artificial intelligence, just because it's called an "intelligence."

But evolution produced intelligent humans by making tiny random tweaks and basing future work off of what's worked best so far -- a lot like AI research. If AI comes about just because researchers stacked a bunch of random algorithms on top of each other, with no real understanding of how the system works, do we really think it's going to be friendly?

Not knowing how to build friendly AI isn't deadly on its own: it's only deadly if you *think you can.*


### Underestimating the Power of Intelligence

Because people spend so much time thinking about *people,* when you say "intelligent," they think "Einstein" (smart *for a human*) not "humans" (so far beyond other species' intelligence that we put footprints on the moon).

It's likely that a future with superhuman minds is *fundamentally different,* not like "the present with floating cities and flying cars."

AI could be an existential risk if people don't understand it. But it could also solve other existential risks. It's complicated.


### Capability and Motive

A lot of discussion of AI goes: "A sufficiently powerful AI could (and would) X. Therefore we should/n't build it." Let's call this "the Giant Cheesecake Fallacy" (for the case where X is "build a cheesecake larger than any human could"): you're conflating "could" and "would," capability and motive.

Let's introduce the term "optimization process": a system which hits small targets in large search spaces to produce coherent real-world effects. It's a useful abstraction: if you understand an optimization process's target, you can *kinda* predict what the outcome, even without understanding how it accomplishes the goal.

> Example: if friend drives you to the airport in an unfamiliar city, by understanding your friend's *target* (get you to the airport), you can predict that you'll arrive at the airport, even though you don't know how you'll get there.

**Please,** don't try thinking of reasons why a generic optimization process would be friendly. Wishful thinking does not select for true beliefs.


### Friendly AI

It would be nice if we knew how to build a nice AI.

(Such an AI might even be able to safely modify itself without changing its "goals," because it could formally prove the correctness of its self-improvements. This paper won't focus on that, but it's not impossible.)


### Technical Failure and Philosophical Failure

There are two ways Friendly AI might fail:

* "Technical failure," where the AI doesn't work the way you think;
* "Philosophical failure," where you tried to build the wrong thing.

The border between these kinds of failure is fuzzy.

#### An Example of Philosophical Failure
The first communists -- many honest and intelligent -- didn't have Soviet Russia's example to warn them of the dangers of trying to implement communism.

We **mustn't** attribute huge catastrophes to evil or unusual stupidity: else, when we perceive that we're not evil or unusually stupid, we'll conclude, "But that would never happen to *us.*"

The first communist revolutionaries were basically aiming for the same thing as everyone else: they wanted people to be happy. They were wrong about how to get there, though.

That's the danger of combining an empirical belief (that trying to implement communism would make people work fewer hours and have greater wealth) with a value judgement (that that outcome is desirable). Given a different empirical belief, the communists would have pursued a different course.

Telling a superhuman AI *how to achieve your goal* is dangerous, because you're trusting that your empirical belief about how to achieve the goal is correct. If you tell the AI, "Implement [political system]," and it turns out [political system] *sucks,* it won't re-evaluate.

#### An Example of Technical Failure

A famous parable in AI:

> The army wanted to use neural networks to automatically detect camouflaged tanks. They trained a neural net on 100 photos: 50 with tanks, and 50 without. Then they tested it on new photos, and the net performed perfectly, so they reported success to the Pentagon!
>
> The Pentagon handed it back: in their tests, it had done very poorly. Turns out, the researchers had taken their tank-pictures on cloudy days, and their tankless pictures on sunny days, and that was what the neural net had learned to distinguish.

The lesson here is that code that does something desirable in one context can do something *really bad* in another. For example, an AI that was trained to respond positively to smiling faces in one context (where humans control the world), transplanted into another context (where it controls the world), might tile the galaxy with tiny smiling faces.

There's a temptation to think that the AI will notice if "that's not what we meant": nonsense.


### Rates of Intelligence Increase

One critical point: AI could get *way* smarter *very* quickly, since it can rewrite its own code from scratch (unlike humans, who can't rewrite their brains, or evolution, which basically never messes with sexual recombination).

There's a big difference between a lump of uranium where each fission triggers $0.9994$ more fissions, and one where each fission triggers $1.0006$ fissions. Quality of recursive self-improvement may show a similar change in behavior. (Consider <em>Homo sapiens</em>, which got smarter slowly, slowly, over millions of years, and then suddenly in the last few tens of thousands of years we conquered the planet.)

It's also to keep in mind that the intelligence difference between "village idiot" and "Einstein" is *very small* in the grand scheme of things. Even if an AI's intelligence increases only "linearly" (in some sense), it might go from infra-idiot to ultra-Einstein terrifyingly quickly.

What would follow from the assumption that superhuman AI might happen overnight?

* We can't put off thinking about Friendly AI just because we don't yet have AI.
* We can't assume that an AI's programmers will be able to modify it against its will.
* If the AI wants to modify itself to be unFriendly, Friendliness has failed. It may be able to overcome any precaution you take to prevent it from self-modifying.


### Hardware

Large computers are probably not the enabling factor for AI. People talk about hardware a lot because it's easy to make PowerPoints about; but really, better hardware just lowers the level of researcher understanding required for AI. (Consider natural selection, which has *no* understanding but built us by throwing *phenomenal* computational resources at the problem.)

This is kinda worrying: the catastrophic outcome is if we succeed at AI but fail at Friendly AI, and Moore's Law makes it easy to do exactly that.

Suppose molecular nanotech was developed; this would gift us unfathomable computational power, which would make it relatively easy to run an extremely intelligent unFriendly AI.

Governments restricting access to supercomputers isn't likely to help: Friendly AI isn't about brute-forcing the problem.


### Threats and Promises

The conjunction fallacy makes it hard to say specifically how an AI would help or harm humanity, and the future has frequently broken the bounds of past civilizations' imaginations. But nevertheless, let's try to solidify this.

There are three unreliable metaphors to help imagine superhuman AI:

* $g$-factor metaphors: AIs are to us as we are to idiots. They'll patent new technologies, lead political power blocs, and publish amazing papers.

    This is flawed: it assumes that AIs will go from "amoeba-level" to "supergenius-level" and then... stop!?


* History metaphors: AIs are to us as we are to past civilizations. They'll invent nanotech and interstellar travel.

    Suppose you locked a sped-up human civilization in a box that could affect the outside world only (relatively) glacially slow tentacles. It would focus on the fastest possible way to build faster manipulators. What's the shortest path it might take to do that? It's unknowable, but maybe something like "solve the protein folding problem, email DNA sequences to some outside labs to synthesize proteins, and get the results mixed together to build a wet nanosystem controllable by acoustic vibrations." This would give it fast manipulators in a couple (outside-subjective) weeks, and this is an *upper limit* on how long it would take.


    And once an AI has fast manipulators, it could rewrite the world unopposed: an unFriendly AI wouldn't need a robot army, it could turn the earth into grey goo (or whatever its optimization target is) before you finish thinking "I should do something." A Friendly AI wouldn't do something cliche like curing cancer, it would cure *disease*.


* Species metaphors. AIs are to us as we are to dogs. They'll have magic, they'll have things that are **literally incomprehensible** to humans. We can't even speculate what this looks like.


### Local and Majoritarian Strategies

Risk-mitigation strategies might require unanimous cooperation (obviously unworkable), majority cooperation (which require enormous effort and much time and some luck), or local cooperation (usually the easiest).

So... local strategy or majoritarian strategy?

* Majoritarian: reasonable in a world where the first AI can't do catastrophic damage, and a bunch of Friendly AIs can protect humanity against a few unFriendly AIs.
* Local: reasonable in a world where the first AI can't do catastrophic damage, and a single Friendly AI (plus humanity) can fend off tons of unFriendly AIs.

(left off at the bottom of page 29)

### AI vs. Human Intelligence Enhancement

### Interactions of AI with Other Technologies

### Making Progress on Friendly AI

### Conclusion
