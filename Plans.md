This document describes the ongoing activity inside and around the Digital Philosophy project. It's assumed that the reader is familiar enough both with philosophical, psychological and technical aspects of the topic. For in-depth introduction please refer to the [following document](Artificial%20Intelligence.md).

## Functional Account to Consciousness 

In functionalism Consciousness is defined behaviorally via its relationships with other objects, including _itself_. Certain function of consciousness is a subset of those relationships. A function may be defined mathematically, so we can talk about _functional basis_ of Consciousness -- some minimal set of functions all other functions can be reduced to or built from. If such basis is _computable_, such Functionalism is _Computational_. The basis can be Turing-complete, in that case every computable object can be somehow represent everything as a "consciousness"-like function, not just represent everything as a "content" of a consciousness. Here in this work by Functionalism we mean Computational Functionalism. 

Neuroscience follows "top-down" approach to Consciousness where they take large set of complex related behavior and try to explain it as a whole. While it's convenient when we work with human's or animal's higher mental functions, it struggles with reducing consciousness to computable functional basis. 

Philosophy of Mind (PoM), from the other side, follows "bottom-up" approach. The entire set of phenomenology of the conscious is split into two sets: _easy_ and _hard_ phenomena. Easy phenomena (e.g.: thoughts and reasoning) can be explained in a usual way (via, e.g., Mathematics). Hard phenomena is struggled to be explained in a usual way. An example of a hard problem is a problem of _qualia_ -- certain properties of _experience_ like _redness_ which are hard to explain in a functional way. Problems like qualia are useful because they are abstracting away a lot of irrelevant details and make it easy for everyone to discuss the same thing. But such variant of the bottom-up approach may struggle with _scaling_ -- constructing more complex behavior from simple ones.

In this work we are using PoM's approach to Consciousness based on qualia, but with slightly different focus. Quale of _redness_ is described via textual representation of experience "I see red light". Instead of focusing on redness as a quality of experience, we are focusing on _seeing_. This is the hardest part of the problem, because computers don't have an operator _to see_. It all has to be reduced to deterministic elementary interactions, but the problem is that first-person experience apparently has some properties that can't be reduced to known physics without assuming that those properties are _illusions_ (or, better, _approximations_). Examples: _causal loops_ (self-causation) and _free will_.

Qualia, despite sometimes being illusions, nevertheless are used as descriptions of internal and external environments. Free will is the fundamental concept our entire civilization is built on. Qualia are _everywhere_ and their intrinsic irreducibility is the main reason why purely symbolic knowledge models fail to describe subjective experience. Irreducibility of certain mental states plays important role in our entire self-perception: we are both bloody predators (really) and _moral animals_ at the same time. 

Qualitative aspect of self-reporting (set of qualia) is called _Phenomenal Consciousness_ (PConsc). PConsc is hardly reduced to some lower level functions. Form the other side, easily reducible properties are called _Access Consciousness_ (AConsc). In "I see a red light" the formula itself is AConsc, but _redness_ in the formula is PConsc. 

Given these preliminaries, we can now define what we mean _in this project_ by Consciousness:

> Given a self-referential agent acting in an an environment and capable of self-reporting in an explicit or an indirect/implicit form, Consciousness of the agent is the part of its self-report describing its _subjective reality_ and _properties_ of that reality, including the agent itself as a part of its reality.

Functional consciousness is a much less bizarre thing than its substance counterpart. Instead of looking for some special physical substance or a "causal pattern" responsible for "true/real consciousness", we just try to replicate consciousness' _observable effects_ in any substrate sufficiently capable for that.

Generalized Functional Consciousness is scale-independent. We define the following basic generalized functions:
 
1. **Observer** -- self-referential entity that can _causally_ distinguish itself from its environment ("I'm _not_ my environment"). Observer exhibits (reports) _quale_ of _Beingness_ this is "am" in the formula "I am" (where "I" is a Self). Extended experience formula sounds like "I exist and I'm not my environment". Speaking more generally, Observer is a _break in causality_.
2. **Agency** -- Observer that can make actions, independent from it's environment and which is _responsible_ for its own actions. It's formula is: "My actions are _mine_ (caused by myself) and determined by my environment". The latter is also known "downward causation" (note that this term may have multiple meanings).

So, given requirements defined with those two functions, we can try both scaling down consciousness to a simple physical system like [Operational Amplifier](https://en.wikipedia.org/wiki/Operational_amplifier) or a [D-type flip-flop](https://en.wikipedia.org/wiki/Flip-flop_(electronics)), or scaling it up to the level of entire society (collective consciousness of loosely-coupled independent agents).

Note that these two functions define so-called "pure" (or low-level) consciousness where all world-related "content", including many mental specific process, traditionally associated with high-level consciousness in humans, are abstracted away.

## Computational Consciousness 

The summary of previous section is that phenomenal consciousness has some _apparent_ properties that are very hard to map to known physics 1-to-1 in both indeterministic and super-deterministic interpretations of QM. Self-causation isn't possible because causal breaks aren't allowed under modern Physics. And, correspondingly, _free will_ isn't possible either, despite being such important concept. Contrary to the popular in Physics opinion, quantum (or any other form of) indeterminism does not create free will, it creates _random will_.

This project is based on the stance of Illusionism, that "hard" properties of conscious experience are _illusions_ or, better, _approximations_ (of corresponding real things). To make consciousness computable, we need to recreate those illusions in a deterministic environment of _finitely_ computable functions over discrete memory states. The main challenge is that we can't just hardcode those ideas (self-causation, free will and responsibility, etc) at the conceptual level, because in this case they would need to be _encoded_ separately for every such case. We need _emergent_ solution when an agent comes to these conclusions by _rigorous reasoning_, effectively simulating corresponding illusions, adapted to a specific situations.

The solution that is proposed here is grounded in so-called "Higher-order Computational Phenomena" (HOCP). The phenomena itself isn't new but hasn't been largely considered in the context of AI yet. The term HOCP is defined by the project.

The basic idea of HOCP is rather simple, it's using run-time properties of computations as _descriptions_ and data structures. For example, AnyTime/AnySpace algorithms or heuristic algorithms may run arbitrary time and if it runs just too long (over a threshold), it's considered "hard", otherwise -- "easy". These "hard" and "easy" are labels that may be attached to problem instances and used as description.

Another example is logical reasoning that, even if it's decidable, most likely has exponential time complexity. So running logical reasoning over an arbitrary logical problem will most likely result in a timeout. Only a few questions out of full set of possible questions may be feasibly answered this way. But what is _experienced_ by a person when brain can't physically solve some problem exactly? Technically, brain makes a mistake in this case but it doesn't know _how much_ wrong the result is. This mistake may be experienced in any way, but the idea is that _systematic (reproducible) mistakes are experienced in a systematic way_. So, for example, when brain can't resolve all external causal determinants of its internal decision-making, this fact is experienced as _causal breaks_ between the brain and it's environments. In other words, _Observer_ is a _systematic conclusion_ made by a self-referential system over observing its own relationships with its environment ("I'm not caused by my environment"). It's clearly a reasoning mistake, but it's a systematic and persistent mistake, appearing consistently, so it can be used as a _description_.

See the [following section](Artificial%20Intelligence.md#observer-problem) for more in-depth explanation of Observer and Agency functions reduced to HOCPs.
 
Notable example of an HOCP is Schmidhuber's [Artificial Curiosity](https://people.idsia.ch/~juergen/interest.html) (AC) -- mathematical theory of curiosity reduced to the _compression progress_. The idea is that we are building world model by _compressing_ it. Generalized compression is reducible to finding computable models generating observable data. Progress in compression means that "there is possible some _novelty_ here", so it's worth to _pay more attention_ to a specific frame, to find more patterns. So, there is an apparent correspondence between compression progress and _signaling/guiding/heuristic_ function of higher emotions. 

Finally, [Metacognition](https://en.wikipedia.org/wiki/Metacognition) (awareness of one's thought processes and an understanding of the deep patterns behind them) is a entire multy-disciplinary research focusing at self-referential processes in human mind.

%% Self-referential computer. Minimal, FC Rule-based, Transformers. 

No special hardware or computational model is needed for HOCP. HOCP require process/state duality: what is _process_ in one context, is a state (some data structure describing the entire state change history of the process) in another one and vice versa. But if this functionality isn't provided "out-of-the-box", efforts to add it aren't expected to be substantial. Two existing algorithmic environment are currently available for experiementing with HOCP:

1. Forward-Chaining Rule Systems (FCRS), specifically based on the RETE algorithms (Excample: [Drools](https://www.drools.org)). With FCRS computation is represented as a stream of events in _working memory_. Each new event is triggers rule evaluation (pattern matching) that may result in new events, an so on. HOCP in this model are just metrics over working memory (and it's _history_) resulting in new events. Very good for manual exploration of HOCP, but rather hard for ML (genetic programming is welcome, but no specialized hardware exist to accelerate it).
2. Transformers. Self-referentiality is _implicit_ (auto-regression + self-attention) and existing LLM demonstrate very good level of _self-reasoning_. Are trained with ML is a self-superwized way, but hard to interpret. So if something doesn't work as expected, there is no obvious way how to fix it/

## Transformers



## Mindware -- Software 3.0 and Programming 3.0

## Intrapersonal Intelligence

## Development Platform
