# Computational Functional Consciousness (with Memoria Framework) #

**Note that this page is a scratchpad, it's always work in progress. If you need to reference it, please contact me and I will create a Git tag for you.** 

This is a currently a scratchpad where I'm (Victor Smirnov) condensing my thoughts and arguments of the topic of computational consciousness. Originally it was inspired by [this work](https://arxiv.org/abs/0812.4360) by Juergen Schmidhuber, and the initial idea was to put better psychological and technical foundation here. But to do it we need a Theory of Experience, because "beauty", "interest" is an _experience_, not a _behavior_. Here we go -- The Hard Problem of Consciousness.

This page was written over a pretty large time, it was started at 2017, but _my_ ideas outlined here go back to 2010 and earlier. What I want to specifically emphasize here is that **core ideas aren't mine**, one may find them here and there separately, scattered in the literature. What I'm doing is compiling ideas from multiple disciplines (Psychology, Neuroscience, Philosophy of Mind, Computer Science and Algorithmic Information Theory) into a single _framework_ backed by Memoria as a technical platform.

But there is a _foundational_ idea (that isn't mine either) that is absolutely necessary to understand this work properly: to work with phenomenal consciousness we need a pretty good level of _Intrapersonal Intelligence_ (IntraI) growing on the grounds of _process introspection_ -- ability of our mind to "see" its own hidden _processes_. This ability isn't inborn and has to be [developed at lifetime](https://medium.com/@victorsmirnov/brief-notes-on-ai-and-process-introspection-615af6104d6b). Lack IntraI isn't noticeable but results in _intraspective blindness_: not only mental processes is unaccessible, the person isn't aware about it. At best, mind is experienced as a pure holistic structure-less entity, at worst -- as a non-physical _miracle_.

This work is focused on a functional account to consciousness and two basic functions: Observer and Agency. Important applied questions like computational foundations of _feelings_ and _intuition_ (pretty hard topics for computational modeling) are currently left aside (for the future). 

The main contribution of this work (besides multi-disciplinary compilation) is the concept of _higher-order computational phenomena_ in self-referential systems, when space-time properties of a computation over some object may become a part of _description_ of this object. See [the main ideas](#higher-order) section.

This work is not yet sufficiently self-consistent, sections may contradict each other slightly.

## Introduction

This work is largely influenced by or mostly consistent with the following theories: 

1. Graziano's Attention Schema Theory (AST), explaining how self-referentiality contributes to phenomenal reports.
2. Damasio's Somatic Markers Theory (SMT) explaining basics of emotional intelligence: guiding function of emotions in decision making.
3. Jean-Louis Dessalles' [Simplicity Theory](https://perso.telecom-paristech.fr/jld/papiers/simplicity.html) explaining subjective attractiveness in a fundamental way.
4. Tononi's Integrated Information Theory (IIT), linking conscious states with descriptional complexity.
5. Daniel Dennett's Cartesian Theater and Multiple Drafts. Consciousness is not an illusion in a strict sense. But traditional first-person view on it is heavily biased, that leads to various paradoxes. 
6. Ray Solomonoff's theory of Universal Induction (UI). This theory explains theoretical and practical limits of problem solving. 
7. Jurgen Schmidhuber's [Artificial Curiosity (AC)](https://arxiv.org/abs/0812.4360) and his theory of intrinsic reward, explaining highest emotions in a mathematically universal way.
8. Schmidhuber's Goedel Machine, explaining limits of recursive self-improvements. 

AST gives clever insights into how certain important subjective phenomena emerges in a self-referential structures like "attention schemes" but it leaves some important questions unexplored. In this work I introduce a semi-formal self-referential machine, self-referential algorithms and self-referential data structures constituting _self-models_. There is nothing special about them from mathematical perspective, but they have certain properties by turning computational phenomena into descriptions. For example, how gradual incompleteness of self-referentiality leads to the lack of "process introspection" and, by that, leads to "inexplicable" elements in phenomenal reports, like qualia which can be viewed as a subjective report of the system's inability to recurse deeper into perception of an object. 

Damassio introduces guiding function of emotions in its SMT that manifests by affecting decision making in an unconscious way. Schmidhuber proposes universal scheme for certain higher emotions, but emotions are not feelings. Conceptual jump from emotions to feelings requires subjectivity, and I'll try to show how feelings are self-models of emotions. _(Note that this specific topic (emotions/feelings) is not currently in this work.)_

Self-models can be learned directly from data via induction. Solomonoff's UI is complete but not computable. Computable induction can't be complete, but can be approximated with various techniques. If self-models are expressive enough to emulate universal computer, they can be used to host inductive learning, resulting in a functionally complete metacognition. It turns out that phenomenal consciousness is not just a side-effect of intelligence, it's a substrate-independent AI by itself, capable for problem solving.

Hard problem of consciousness then can be reformulated the following way: **can all phenomenal reports be composable and decomposable in a computable way**. To prove this, it is necessary to provide minimalistic but universal self-model that can evolve with algorithmic induction into any human phenomenal report *in the limit*. So, no subjective phenomena will be left unexplained in the limit.

Memoria provides decent environment for self-modeling. It has framework for advanced data structures like self-indexes, that can turn self-models into advanced databases, and allows deploying such structures at scale in distributed and decentralized manner. Memoria has vertically integrated AIO subsystem from raw block devices to networking and C++-based heterogeneous computations unifing CPUs, GPUs and ASICs. It's primary goal to make approximations of Universal Induction practical, which is necessary to evolve self-models. (But see [this section](#case-3-consciousness-of-llms-implicit-srm))


## The Sketch of Main Ideas ##

1. There are theoretical schemes for AGI, but they are not finitely computable. Any finitely computable AGI will not be complete or, in other words, truly generic. These schemes can be approximated, if we are agree to sacrifice some generality to achieve desirable performance in certain domains. Note that by AGI it's currently mean "Human-Level-generic AI" that is neither historically correct, nor allows us to define what is AGI precisely.

2. Human brain is not an AGI in that narrow sense, though it can be true AGI in the limit, providing infinite time and memory. Being an approximation of AGI, it can solve some problem classes efficiently (fast), being slow on all other classes.

3. One of possible AGI approximation strategies is trading memory for speed. AGI is based on search in Turing-complete programs space that is too large to be tractable for anything except toy domains. 

4. To speedup this process we can apply restrictions to the program space, so the search will be performed only within small subset of the space. The method is no more complete but can be flexibly tuned for very wide variety of problem classes just by changing the system of restrictions. 

5. In most cases the system of such restrictions is poorly compressible, so the only way to specify it, is by direct description via data structures. In other words, an AGI approximation, built on this principle, will have huge database. The bigger the database, the more generic intelligence such a system will have. There are theoretical results that practical AGI will be complex in any means, and present complexity of advanced ANNs is reflecting this principle. 

6. This database will be much more complex than those ones currently in use. It will be based on very advanced coding schemes and data structures. Memoria is all about that. See this [advanced data structure](https://memoria-framework.dev/docs/data-zoo/associative-memory-2/) as an example.

7. It's not that easy to determine classes of problems brain-AGI can solve efficiently: human-like AGI approximation problem.

8. Hard problem of AI reformulated: does phenomenal consciousness have any problem-solving abilities by itself? _Yes, it does_. 

9. Sentiments and emotional Intelligence: emotions, feelings and guiding function of emotions.

10. From emotion to feeling. Self-referential machines have a "dualistic" property of representing computations as data and vise versa. They can build self-model allowing them to act on the stored log of their own previous states in the way increasing global and local utility functions. Entire universal Turing machine can be implemented this way, performing self-referential operations on self-referential data structures. See [Observer and Agency](#observer-problem).

11. Particularly, this type of machines can catch certain fundamental computational phenomena <a name="higher-order"></a>(here: _higher-order computational phenomena_) and use them as descriptions. For example, inherent incompleteness of self-referentiality (infeasibility to build a complete self-model) results in simplified self-models systematically lacking some causality links. Everything systematic (even if this systematicy is stochastic) can be turned into description. 

12. For example, if we can somehow arrange this lack of causal structure in self-descriptions in a multi-scale way, we can turn corresponding records in memory logs into multiscale data structures, analogous to [compressed multidimensional quad tree](https://memoria-framework.dev/docs/data-zoo/associative-memory-2/), instantly enabling many sophisticated algorithms on top of such data structures. 

13. A set of such structures with "dualistic" properties emerging in self-referential computations can be viewed as a formal language, describing "phenomenal reports" in memory logs of self-referential machine. This formal language can be Turing-complete, so, in principle we can build another self-referential machine inside a self-referential machine. 

14. Finally, a Normalized Information Distance (NID) scheme can be build on top of this formal language, measuring similarities and differences between everything in a pretty generic way. NID-based encoding enables differential encoding when new data is represented as old data + some delta of _novelty_. NID can be efficiently approximated with Normalized Compression Distance (NCD). Simpler schemes are also possible.

15. NCD aligns naturally with mutiscale data structures from (12) and efficiently generalizes them to any domain where there is a more-or-less efficient compression scheme, that is Multiscale NCD-decomposition. NCD works fine with lossy compression.

16. Particularly, self-referential decomposition of an object can efficiently implement its Mutiscale NCD decomposition relative to the entire history of the self-referential machine. In such decomposition some information, that is completely new to the machine, will appear as a very rude approximation or "vagueness" in phenomenal reports. Nevertheless, it contains some bits of actual data that contribute to the difference between vague elements of phenomenal report guiding decision-making.

17. If we define needs and emotions somehow for the self-referential machine, then motivations and feelings are self-models of needs and emotions correspondingly. Both needs and emotions are kind of internal stimulus, so motivations and feelings are sub-type of senses. 

18. All senses have "motivational" component that is a manifestation of guiding function of emotions to decision making reflected in phenomenal reports. It looks similar to an attractor in non-linear dynamics, or to gravity in physics. So, "something" happens behind the scene, at the level that is not accessible, and at the accessible level we have _results_ of this hidden process.

19. If needful portrait encodes the set of an agent's goals, and emotional portrait encodes some stimulus relatively to the needful portrait, then _sentiment_ is a self-model of emotional portrait of the stimulus.

20. Until this moment it was not implied that self-referential machine has any special properties enabling it to learn like a human just because it resembles our core cognitive abilities. Nothing special is about such machine relative to learning. It's implied that self-models are learned separately from self-referentiality with some kind of approximated program induction mentioned above: (1) - (7). 

21. But if a self-referential machine is expressive enough, it can host such inductive learning partially or entirely, resembling not just cognition as thinking but also cognition as obtaining new knowledge in a unified way. By separating cognition to self-referentiality and induction over it we are making entire problem much simpler to tackle.

22. The idea of self-referential machine's solution to problem of qualia in AI is that there is no such thing as "red color", the minimal element of memory log of such machine is "I see the red color", that is not a static structure encoded in memory, but also a dynamic computation (in another context). In other words, some form of an _Observer_ is always implied, and it is finally the machine itself. Note that this is a form of pan-proto-experientalism but in the "software" when higher-level experience is composed from lower-level ones in a computable way. Note also that this "experience" is also _physical_, because both the machine and information processing on it are physical.

23. From a functional perspective, qualia are soft bounds in building the self-model of a stimulus. Developing a self-model is computationally very hard task, but this complexity is not evenly distributed. Some elements of phenomenal report emerges faster than others. Some elements will remain underdeveloped forever and, because of their stable hardness, may become descriptions themselves, like qualia.

24. Note that if we accept that "rational" problem solving ability can be unsound and incomplete, then we can reduce rational intelligence to emotional one and implement it on the same computational substrate. Then such rationality will be heavily biased in many ways, and reduces to specific type of phenomenal report like "I'm reasoning logically here". Note that sound and complete inference not feasible for everything except very narrow sets of problems.

25. The last question is "why" self-referentiality. Any online learning system must maintain consistency of its knowledge base, so it must somehow reason about itself. Any sufficiently large computer has non-perfect hardware that becomes more error-prone with size and has some kind of "homeostasis" to maintain over time. Self-referentiality emerges naturally in such environments. Moreover, all modern IT systems not just stores part of their computational states into logs, but can even act on this stored state, thus having some rudimentary self-model. Artificial consciousness is inevitable for sufficiently large and generic AI. 

26. Note that while self-hosted induction in a self-referential machine does not explain consciousness in a strict philosophical sense, it transforms the problem from philosophical to functional domain, by explaining phenomenal reports in a functional way. If brain is indeed a self-referential machine, then it can improve its own process introspection in a monotonic way. If all subjective phenomena believed explainable in the limit this way by a person, then she can see herself as a machine phenomenally. Or, in another words, conceptual gap between self-aware person and machine disappears. That is what we need for upcoming age of AI.

27. It's the lack of process introspection what make us so unique in our own eye at the first place. Know you machine!

28. Form another side, phenomenal consciousness is not finitely explainable indeed, as some philosophers insist. I mean that while we can have complete functional model of consciousness in a form of certain self-referential machine, this machine will never have complete self-model, so some internal phenomena may only believed explainable in the limit, but never (in a finite lifetime) actually be explained.

29. There is one interesting property of self-referential computations. Phenomenal reports are not directly accessible from outside. It's can be possible to read memory of a self-referential machine directly, but in order to reconstruct back memory logs into phenomenal reports, we have to run the machine. So the only generic way to access phenomenal reports is to ask the machine about its current experience.

30. So far, form technical perspective, we have two complex problem. First is basic self-referential machine, tuned to process and generate human-compatible phenomenal reports. This is a key requirement that is needed for a machine to understand human and vise versa. 

31. Second, is a feasible induction approximation to learn this machine from data, because it will be not manually programmable, except for toy problems. Self-referential machine must be expressible enough to host this induction approximation schemes. 

32. As it has been already said, universal induction can be approximated by trading time for memory, by restricting program search space. This system of restrictions will be poorly compressible, so the only way to represent it is direct description in a form of a database. If for some subset of tasks such system is compressible, then it reduces to a finite system of heuristics. 

33. Memoria has long-term goals in hosting applications targeted these two problems. It's an integrated data engineering framework providing (A) vertically integrated Asynchronous IO engine, starting from raw block storage to networking and visualization, (B) C++-based heterogeneous computing, merging CPU cores, GPUs and ASICs in a single data flow framework, and (C) confluently-persistent decentralized data structures, both basic ones like arrays, maps, sets, vectors, tables, trees, graphs, and advanced ones like mutiary wavelet trees. 

34. Memoria seamlessly integrates IO- and Compute-intensive tasks by making data as close as possible to computational resources. 

35. But unlike other AI-related platforms, Memoria does not specialize only on A[G]I, allowing to solve wide range of practical tasks currently common to BigData.

36. [Memoria](https://memoria-framework.dev/)'s design follows bottom-up evolutionary path to AGI. Instead of building "AGI-in-a-box", Memoria's approach consists in decomposing such complex thing as human-level metacognition into well-manageable building blocks that can be used together or independently, to bring new qualities into existing applications.

## Types of AI 

There are many types of AI, and traditionally what we call Artificial Intelligence is a **Good Old-Fashioned AI** or **GOFAI**, or catching human ways of reasoning during *problem solving* in special notations, which for those times were logic languages and frames theory. The ultimate AI of this kind is an emotion-less "pure mind" or Expert System augmenting human reasoning through question-answering.

GOFAI has two main conceptual limitations: there was wide disagreement how to model higher mental functions and uncertainty. And if latter problem has finally been solved with probability theory, the question if computers can exactly model consciousness is still one of the most controversial in AI.

Historically there were several main types of AI:

1. **Strong AI**. In sort, this is AI with true consciousness, having the same nature with humans consciousness. Or, more certainly, that human consciousness can in principle be modeled on a digital computer. If Strong AI hypothesis is true, we can upload our consciousness into a computer and survive death this way. Term "strong" may be misleading because it does not describe or define problem solving abilities of such an AI, only its substantial equivalence to a human being (and other animals, of course). Strong AI can be as weak as an newborn infant, and still be qualified as strong, because it has fully-functioning consciousness. So, "strong" here means power of philosophical argument.

2. **Weak AI**. If you are quaking like a duck, flying like a duck and swimming like a duck, then you are a duck. Weak AI doesn't try to explain mental states, only behaviors and verbal reports. And this type of AI can have much more problem solving abilities than humans typically have, so the naming it "weak" reflects its abilities as philosophical argument, not intelligence. **Artificial General Intelligence** or **AGI** mainly falls into this category if it doesn't explicitly address the problem of consciousness.

3. **Narrow AI** or individual intelligent functions modeling, like computer vision or speech recognition, without intention to achieve good performance beyond certain domain. GOFAI is mainly falls into this category.

4. **Human-level AI**. An AI having general problem solving capabilities on par with average human, so it can replace humans in various domains. It's not necessary an AGI.

5. **Human-like AI**. An AI that looks and feels like a human, but not necessary has human-level problem solving abilities. Its main task is understand humans well and make human understand machines well. For example, when we are doing sentiment analysis, we are doing human-like AI.

6. **Hard AGI**. An AGI in a strict sense, or ultimate problem solver. This type of AGI is infeasible to build because it's not finitely computable. But we can build its feasible approximations, which will be computable, but will not be completely generic. Note that "Hard" prefix here is used only distinguish this type of AI from the next one.

7. **Soft AGI**. This is the type of AI that performs practically "well" in wide range of "complex domains", but not necessary is a Hard AGI, especially because the latter is not finitely computable. Humans are "Human-like Strong Soft AGI" if we are trying to identify ourselves in this system of definitions.

8. **Superintelligence**, or AI having problem solving abilities which are much beyond to what currently possible for non-augmented humans in wider range or domains and environments than it's possible for humans. This type of AI is mostly feared of, because it potentially can enslave or even exterminate humanity just with its problem-solving abilities. Superintelligence is usually assumed to be a Hard AGI in the limit.


As an example, when AI is reading certain emotional expressions, it's Narrow AI. When it is reading emotions in general, it's Weak AI. When AI is understanding feelings, it's Strong AI. If someone is doing benevolent AI God, she is doing emotional superintelligence. 

## Algorithmic Information Theory Basics ##

Expressiveness and Visibility. Algorithms and data structures -- two edge cases of highly compressible strings and low compressible strings. What is in-between, is poorly visible for us. Compressed data structures: data that can answer more questions. Universal sequence prediction through compression. Reducing problems to sequence prediction. Correspondence with human behavior and cognition: artificial curiosity and simplicity principle, intrinsic motivation.

Incompressibility theorem and its implications for programming and AI: complex things are complex in any notation. For "practical" AGI there are approximation strategies throws ensemble (of narrow AIs) methods, that means that amount of intelligence, or the number of problem classes this AGI can solved efficiently, grows linearly with the size of ensemble. What we need is identify the set of problem classes human brain is able to solve efficiently. That is not an easy thing, but broad set of human cognitive material in form of literature, art, engineering and program sources can be used.

In AIT we measure amount of information in bit string *S* by the length of the shortest program *P* generating or computing *S*. This length depends on properties of the string *S* and on the language *L* the program *P* is written in. This shortest length we call **Kolmogorov complexity** of *S*: l = *K_L(S)*. The main property of *K* is that it does not depend on selection of *L* more than a constant *C* that is a length of interpreter form any *L1* to *L2*. This additive constant *C* depends on *L1* and *L2*, but doesn't depend on *S*: *K_L1(S) <= K_L2(S) + C(L1, L2)*. So, in AIT we drop *L* and *C* just keeping them in mind. *K* has another important properties:

1. Any universal programming language *L* is a universal description language: any computable object *O* can be first encoded as binary string *S* and then described succinctly with some program *P* generating cor computing *S*.

2. Let *|S|* is a length of string *S* in bits. If for some object *O1* *K(S1)* << *|S1|*, then we say that *S1* is **highly compressible** or **simple**. If *K(S1)* ~ *|S1|*, then we say that *S1* is **uncompressible** or **complex**. There are may intermediate descriptional complexity classes between highly compressible and uncompressible strings.

3. A string is completely [random](http://www.scholarpedia.org/article/Algorithmic_randomness) in AIT if it is uncompressible. The more compressible string is, the more causal structure can be found in it, the less random it is.

4. *K(S)* is uncomputable. To find the shortest program *P* generating *S* we have to enumerate all programs an evaluate then in a diagonal manner. Not all programs will halt eventually, and for any fixed moment in time we can't know if some program *Pi* is still computing *S* or have already hanged. In other words, to get exact value of *K(S)* we need to solve halting problem that is infeasible unless we have supercomputations. Best method to find an approximation of *K(S)* is [Universal Search](http://www.scholarpedia.org/article/Universal_search) that's is a kind of enumeration of running programs.

5. Nevertheless, *K(S)* is **semicomputable** or **computable form above** in an any-time fashion: for any time *T* we will have set of programs *{P_i}* already completed. Just find the shortest one *P_i* generating *S*. With bigger time, the shorter program can be found, if it exists. The only problem that we never know how close our current estimation of complexity of *S* to its Kolmogorov complexity. 

6. Kolmogorov complexity of a string S in non-reducible. It can't be reduced by means of any finite transformation of S. Complex things will always be complex. That means there is no "silver bullet of programming" -- so advanced universal programming language that all programs become simple by being written in it.

7. Nevertheless, we can have *domain-specific* languages or DSLs that make some limited subset of problems described much shorter than others. 

8. Subjective simplicity has one-sided correspondence with Kolmogorov complexity: complex strings will always appear subjectively complex, simple strings can appear both subjectively simple and complex. The depends on how actual structures in the string fit the set of structures our brain can recognize.

9. [Incompressibility theorem](https://books.google.com/books?id=JvXiBwAAQBAJ&pg=PA96&lpg=PA96&dq=incompressibility+theorem&source=bl&ots=yPy044Hkmq&sig=XjB49Gc-8FZc0dry4nBYj1T6Myw&hl=ru&sa=X&ved=0ahUKEwiMooPQ7NjYAhWp7oMKHdGpAJgQ6AEIKDAA#v=onepage&q=incompressibility%20theorem&f=false) states that simple, or well-compressible, strings are rare. Most strings are uncompressible. This theorem suggests that arbitrarily selected object *O* will have high Kolmogorov complexity, and most of such objects will be just random. 

10. Conditional complexity *K(S1 | S2)* measures how much of new information there is in *S1* relative to *S2*. Or, it's the length shortest program computing *S1* by given *S2*. [Normalized information distance](https://en.wikipedia.org/wiki/Normalized_compression_distance) (NID) is a generalization of this principle and can measure similarity between arbitrary strings in the most universal way. An approximation of NID is a Normalized Compression Distance (NCD). Simple form of NCD is [Levenshtein Distance](https://en.wikipedia.org/wiki/Levenshtein_distance).

Universal Search is theoretically optimal but infeasible method of estimating complexity of *S* for everything except toy problems, because the space of programs is incredible large. Nevertheless, there are suboptimal but much more feasible methods: 

1. [Generic Programming](https://en.wikipedia.org/wiki/Genetic_programming) and [Metaoptimization](https://en.wikipedia.org/wiki/Meta-optimization). Here we restrict both both sample program complexity and search space by **exploiting** certain properties of programs. When exploitation is not possible, these methods resort to random walk in the space of programs that is slower than Universal Search (because we can visit some programs many times).

2. Data/Image compression, both lossless and lossy. Pretty complete method of compression where we seriously restrict complexity of programs. For [example](https://en.wikipedia.org/wiki/LZ77_and_LZ78) to probabilistic finite automation. 

3. Software programming. We are looking for a program with certain properties (size, execution time) compactly describing certain complex domain, and our brain is doing it in a very efficient, though still not complete way. Unfortunately, we still don't know exactly how it's doing this search.

4. Machine Learning. For example, object classification. Instead of doing compression of *S* in order to decompress it back again, we are looking for some model *M* discriminating string *S* from other strings from certain set *{S}*. Though classifier complexity is not necessary depend on complexity of *S*, it depends on complexity of the border between classes strings *S* belong to. For a multi-layer perceptron this border is approximated with hyper-planes, more complex border requires more hyper-planes to describe it exactly. So we are looking for pretty simple models *M* still having good classification accuracy.

In the last case (ML) we are not looking explicitly for the shortest dicriminative or generative models ever. It's enough if the model fits our computational budgets. Nevertheless, program length can be exploited when we are talking about probabilistic prediction. Solomonoff's [Algorithmic Probability](http://www.scholarpedia.org/article/Algorithmic_probability) can be used as universal prior for Bayesian sequence prediction like it's done in Hutter's [AIXI](https://en.wikipedia.org/wiki/AIXI) agent. 

The idea behind Algorithmic Probability (ALP) is simple: we assign (exponentially) higher probabilities to shorter programs. Then, algorithmic probability of a string *S* is a sum over probabilities of all programs *P_i*, computing *S* as output. This does not corresponds directly to probabilities of physical events, but nevertheless may have some connections to higher-level cognition. 

Consider a hypothetical physical experiment. Let's we have a true random number generator generating binary sequences with uniform distribution. And in the first experiment this RNG produces the long, say 1024 symbols, series of zeroes. According to normal distribution, probability of such event will be so low, it unbelievable it can happen. Nevertheless, such unusual output of an RNG is a valid output. The reason why we are usually confused with such experimental results is that we implicitly assign higher subjective probabilities to events we can recognize some structure in. This and many other related phenomena are trying being generalized in [Simplicity Theory of Mind](https://simplicitytheory.telecom-paristech.fr/).

Prominent result of Solomonoff's Alogrithmic Probability that it's a complete and universal method for machine learning and it's at the same time not finitely computable. Moreover, neither feasible machine learning method can be compete in this sense because in order to achieve completeness, we need supercomputations. Incompleteness means that for an arbitrarily given string, we can't find and exploit for prediction all potential regularities it contains. Fortunately, it's not always necessary in practice for a ML method to be complete in a strict sense. Incompleteness of ALP just means that true AGI is not finitely computable, and all feasible AGIs, like human-level AI, will be somewhat incomplete.    

Another interesting practical property of ALP is that it's well-approximable [ensemble method](https://en.wikipedia.org/wiki/Ensemble_learning). If we truncate the sum over all possible models of *S* to just one shortest model, ALP will still perform well in many cases. This method is called [Minimum Description Length](http://www.scholarpedia.org/article/Minimum_description_length) principle. From another side, we can restrict the model class we will be looking for simplest models of *S*. For example in [MC-AIXI](https://arxiv.org/abs/0909.0801) authors propose to approximate ALP with ensemble over variable order Markov models computed via [Context Tree Weighting](https://en.wikipedia.org/wiki/Context_tree_weighting) algorithm.

In spite of so appealing properties of ALP and derived ensemble methods like Solomonoff's Induction and AIXI, it's not that easy to apply it to, for example, human-level intelligence. There are two main problems.

1. **Bootstrap problem** or **initial training sequence problem**. In order ALP-based methods to work efficiently on practical problems we have to supply initial set of models either directly, or in the form of initial training sequence. It's not that easy to determine such set of models for human brain. According to decent results, human brain is described with several tens of megabits of DNA code -- the Kolmogorov complexity of our brain. The models we are looking for are implicitly encoded in this DNA's part. It seems that even if several megabits of this code is sufficient, this task may have unpredictable complexity. 

2. **Incremental learning problem**. Even if we have already selected basic machine and identified bootstrapping set of models, we need an approximation of Universal Search to infer new models from data. Though this process is well-defined mathematically, it's not that easy to implement it in practice, because program space is too big for exhaustive search. In order to achieve desired performance we have to restrict this space somehow, either by restricting model class (as in MC-AIXI) or by using various heuristics as in Genetic Programming and Metaoptimization, or by a database of declarative and procedural restrictions applied to the search space. The latter case is the most flexible and the most complex one because such database may be very big in size even for simplest problems. 

What is important, these two problems can be developed independently, by different teams focused on their problems. This the way to go for Memoria. It will be focused on **compressed data structures**, where compression is understood not just in space-saving context, by as an enabler of generic intelligence. Additionally, Universal Search approximations are very important for general intelligence. 

High-level ideas behind ALP was informally explained by [Marvin Minsky](https://www.youtube.com/watch?v=nXrTXiJM4Fg). In short, Solomonoff's approach to AGI is a top-down approach, when solid theoretical framework of AI is established first, and then we derive custom AIs with specific properties using approximation techniques. As opposite, classical bottom-up approach is playing around with different substances being inspired either from neuroscience or from cognitive science and waiting for intelligence to emerge in experiments. They can work together very well, as custom AIs are developed in a bottom-up experimental way and then merged into more powerful ensemble in top-down way by Solomonoff's Induction. 

## Observer Problem ##

There are two groups of people. Then fist one in the qualia formula "I see a red light" focuses on the "redness" or, in other words, on a *state of experience*. The second one focuses on the "seeing" or on the *process of experience*. Both stances are, basically, the same, because experience is self-referential and a kind of "dualistic" -- what is a process in one context will be *observed* as a state in another one. The *problem* is that from the subjective perspective of the Observer, it happens simultaneously, that is, apparently, contradicting Physics, prohibiting self-causality and causal cycles. Observer, given its/his experience is true, may not exist, unless Physics is wrong.

Illusionist's stance for this problem is that experience "isn't true". For example, free will is an illusion caused by Observer's *limited capacities* to observe it's own decision-making process. Stephen Wolfram in his recent [essay](https://writings.stephenwolfram.com/2023/12/observer-theory/) explains it in a popular format, how Physics (as we know it) emerges in the eyes of computationally-limited Observer.

Reasoning process of a computationally-bound Observer can't be neither sound, nor complete, leading to various *cognitive biases* -- deviations from the idealistic (not computationally bound) reasoning process. Deviations may be *random* (with a specific distribution) and/or *systematic*. Both types of distortions in a self-referential environment become *specific features* of Observer's self-description, so Observer will be defining itself via those features, seeing them as *fundamental*. Realistic Observer is defined by its cognitive biases, relative to the idealistic one.

In this sense, human-likeness -- is a specific set of cognitive biases defining (by limitation) *what* and *how* we can observe. 

In general case, computationally-bounded observer is defined by its computational architecture, its long-term memory and its runtime constraints.

Observer is linked with *beingness* -- specific quality of perception. In the phrase "I am", "am" -- is beingness of Observer. In this sense, beingness *precedes* redness in *verbal reports* of qualia.

Observer problem is not just an abstract question from Philosophy of Mind. Observer implicitly exists in most of sentences and propositions of *natural language*. Observer is extremely rich in its manifestations (both internal reports and behaviours), which, as it has been stated above (see (de-)composability of phenomenal reports), are hard to formalize.

From an information-theoretic perspective, if we want to include Observer into our cognitive architecture, it has to be an information-rich entity, the more -- the better. Ideally, all information in the system should directly or indirectly contribute to the Observer. It can't be "just a box" on a architecture's diagram or a node in a graph. This will not work.

## Observer's physical substrate ##

As it has been noted above, idealized self-referentiality is not physically possible, at least not with current Physics, because it implies self-causation and causal cycles. But we can achieve *nearly* the same results if we relax these restrictions a little bit:

1. Time line is discrete, and experience of the Observer happens in time aligned *frames*.
2. At time T1, instead of acting on itself, the entity will be acting on the memorized accumulated *image of itself* from all previous frames, creating a *new image*.
3. At time T2 this new image becomes experience of the Observer. Go to (2).

Time-delta can be made infinitely small, so discrete nature of the model is not an issue. Fundamental limitation is that current experience of an Observer is actually a *memory*(*), it *has already happened*. Physical substrate of experience is various *delay lines* -- environments with relatively slower signal propagation speeds. Notable physical system of this type is [Operational amplifier](https://en.wikipedia.org/wiki/Operational_amplifier). Given, all these *structural arguments* we may start considering this integrated circuit (IC) as a primitive Observer, with just a 'few bits of experiences', a very short-term memory and no long-term memory.

Another minimal functional example is a [D-type flip-flop](https://en.wikipedia.org/wiki/Flip-flop_(electronics)#Gated_D_latch). Here we have two competing feedback loops, forming either 0- or 1-attractors. 

This type of IC is interesting as a tool in the context of Philosophy of Mind, to formulate and conduct thought experiments. There are a lot (millions) of memory cells of this type in modern computers. If individual memory cell has some primitive form of experience, do experiences of multiple cells add-up to something more? (This is a *hard problem of Panpsychism*).

(*) It's just a coincidence that Memoria Framework is named this way. "Memoria" is a Latin word and is a fourth canon of Rhetoric.

## Beingness and Agency ##

Beingness and agency are closely related. The latter has many different meanings in different domains. Most of them are reducible to the simple concept of an ability to act _independently_, so actions of an agent are _in some sense_ (ex: from an agent's point of view) are not fully determined by its environment and decision-making history. Otherwise there will be no independence. 

Another aspect of an agency, also a pretty high-level one, is an ability of an agent to _be responsible_ for its actions made _independently_. The important property of those actions is that the agent must consider those action made by _it_. 

Here come problems. Deterministic actors can't have agency, just because they will not be considering their actions made by them _independently_ or "no fee will". So, no true _responsibility_. Indeterminism via "true randomness" (let's assume that it exists) does not create agency ether, because true randomness is computationally incomprehensible, so computable actor will not be able to consider those actions as its "own" actions -- it _does not own them_. So, it's not a "free will", but "_random will_". And, no true responsibility in this case either.

Fortunately, there is a _partial_ solution to this problem in the plain Determinism, if Indeterminism is purely _subjective_, so it's a property of an agent's _perceiving_ of its reality, not the reality itself. Let me explain it in an example.

Physical agents are limited in their capabilities, there is only a finite amount of computational resources they can dedicate to analysis and decision-making. Limited produces _incomplete_ results and, if this incompleteness is somehow _systematic_ (repeatable in its appearance) it can be used as a _description_ of the process. So if an agent, performing a _self-analysis_ of a situation, can't determine all determinants of decisions made, it may describe these _missing causal links_ as a _subjective freedom_. Like, the _source_ of actions partially was the agent _itself_.

There are three main issues (loopholes) in such subjective Indeterminism visible in this example and which have to be addressed in real designs. 

**First**, self-attribution of missing causal links is not ensured. An agent may attribute them to any other agent or to some "para-normal" activity, leading to dysfunction of agency. It's currently an open question, how to set up agent's cognitive architecture in the way maximizing probability of correct attribution. 

**Second**, it's unclear what such agent will start doing when it _inevitably_ realizes that its subjective reality is a kind of _illusion_. That may lead to some severe dysfunction of agency, on at least a temporary basis. May be, such agents are intrinsically "mortal" in the sense that their self-perception needs to be periodically "rebooted" by erasing some information to restore proper self-perception. Options may wary. 

**Third**, until an agent realized that his subjective reality isn't a "true reality" (including the second loophole), its reliance on its "subjective truths" will result in making specific errors. 

To address those issues properly, we need to remember that the source of agent's approximate reasoning are physical limits to computations that it can perform. These limits in the physical world are _fundamental_, that means no agent can extend them significantly. What we need is to provide stable mapping of this limitation to proper attributions.

What is especially good about such definition of agency is that it is compatible with the concept of _free will_ and related social constructions built on top of it (hence, [Compatibilism](https://plato.stanford.edu/entries/compatibilism)). Note that responsibility has _correctional_ functions. In case of making a mistake, responsible agent is _promising_ (either implicitly or explicitly) _to correct_ its decision-making process. Punishment for the sake of suffering only makes sense if suffering has functional meaning.

But at the end of the day, such agents will be able to integrate seamlessly into human society and vise versa.

So far, the basic agency is defined as an ability for an agent to make its _own_, causally-isolated decisions (including some form of taking responsibility, that is basically a kind of feedback loop). _Beingness_ is defined in a similar way. Basic function of an Observer (an agent) is to distinguish itself from its environment via _self-causation_: "I'm _not_ my environment". 

If in the phrase "I am", Observer is "am" and is a _function_ responsible for creating self-causated subjective reality, then "I" is an Agency, representing the function of taking responsibility for actions made by Observer. So, Beingness comes before Agency, the latter builds up on foundation of the former. Or, this type of Agency (outlined here) requires Beingness.

It's currently an open question if we can say that Observer == Agency, or that the function of Observer implies both independent decision-making and responsibility. In many relatively complex cases (human-level) we may safely assume, that the answer is "yes". 

In case if better distinction may be required, we can say that an _Agent_ is a _Responsible Observer_, or an agent that can correct its own perceptions and decision-making processes via sufficiently capable _self-model_ (_Self-referential Agent_).

Note that form the purely practical perspective we can introduce two types of Agency:
<a name="agency-types">
1. **Strong Agency** (or just **Agency**) is when an Agent has to make "free decisions" and "be responsible for them", so it need to demonstrate those essential function. Human-level strong Agency is required for an Agent to become an essential part of human society.
2. **Weak Agency** is when function of an agent does not require making "free decisions". For example, when an agent executes a deterministic algorithm like sorting. Strong agency _subsumes_ (is a superset of) weak Agency.
</a>

## Functional vs Substance (or '_true_') Consciousness

There are two main views on the problem of consciousness. The **first** one is trying to find the answer to the question of **what** is consciousness and is looking for its **substance**. Basically, in the quale of _redness_ described in the phrase "I see a red light", what is the substance of the _light_ we _see_. Is it _physical_? If the _substance_ is non-physical, then it's a form of _Dualism_. If it's physical, then it's _Physicalism_. If the substance is special and separate from other physical substances (matter, energy, space, time, etc...), then Physicalism is _Non-Reductive_. Example: _Panpsychism_. If the substance of the subjective light is mapped to other physical substances, then such Physicalism is _Reductive_. This schema is a simplification, so in real life the classification is more "hairy" (has many nuances).

The **second** view on the problem of consciousness is trying to answer the question **how** consciousness is unfolded in its interaction with Reality and itself or the **functional role** of consciousness and _mental states_. At this level functions aren't necessary mathematical, they are just relationships observed by the Observer itself and other external observers. _Functionalism_ can be, again, non-reductive or _holistic_ if those functions tend to be considered in isolation from other functions. If functions are considered _reducible_ to other functions, this is a _Reductive Functionalism_ (or just _Functionalism_). If functions are _computable_, this is _Computational Functionalism_ or simply _Computationalism_ -- that is the most popular view on the phenomenon of Consciousness in AI. From the contrary, Neuroscience tends to holistc variants of _Functionalism_ ("complex systems" and variants).

[Reductive] Functionalism enjoys the possibility of reducing one functions to another functions and, finally, the [multiple realizability](https://en.wikipedia.org/wiki/Multiple_realizability) principle. If _observable_ functions are the same (_functional equivalence_), it doesn't matter how they are realized (reduction to substrate). For the most practical cases only observable functions of consciousness (e.g. Agency) matter. For the same reason it doesn't matter which programming language was used to implement a computable function, providing that observable effects of computations implement this abstract function.

Reductive Functionalism is compatible with Physicalism because "what" is reducible to "how" and vice versa. So it's just two different perspectives on the same phenomenon. Nevertheless, as the set of known physical substrates is limited, it's not obvious to some specialists _how_ to reduce their own mental states to a known substrate. So, just to be on a safe side (safe from arguing) we may say that we are not trying to find the very physical substrate of consciousness and only focusing on _causal effects_ of mental states. 

In this light, the Observer problem (see above) is a functional reduction of (observable) mental states to _delay lines_ -- physical substrate of a short-term memory. Observer is partially causally independent form its Environment and is _self-caused_, that is physically impossible. So, instead of acting on itself, Observer is acting on what will the _memory_ of itself in the future, but attributed to that future moment. Many (any?) physical systems with feedback loops over delay lines can be considered and evaluated as a functionally-equivalent nano-/micro-Observer.

Note that Physicalism is not always compatible with Computational Functionalism. You may find authors saying that "true consciousness" (substance consciousness) can't be fully implemented either in a digital computer at all, or in computers with specific (e.g. von-Neumann) architectures. One example of such argument is that "causal flow" in digital computers is very different from the biological systems, so causal flows _correlated with consciousness_ in biological systems is rather hard to reproduce in digital computers.

## Observer in Ontologies ##

So, functional consciousness (FnC) is the way to go, and it's actually the way how it's measured in medicine: by functions. Normal consciousness (full alertness), stupor, sopor, coma, where generic functions of consciousness are gradually repressed. Even coma, under certain conditions, may be considered a partially conscious state.

Another easily visible function of consciousness is _attention_. Or, not exactly attention (that is also a function of consciousness), but how mental sates _become conscious_. Higher-Order Thoughts ([HOT](https://plato.stanford.edu/entries/consciousness-higher)) family of theories of consciousness, where (simply speaking) mental state becomes conscious if it's "referenced" in a currently conscious mental state and the referenced one becomes attented.

One of the most complicated aspects of FnC is that consciousness is _self-referential_ (another function, again) and this property can be found in many (if not all) functions. For example, the Observer -- is both _who_ is watching and _what_ is being watched. Another example is _attention_. In one context it's a capability of the Observer to select objects. In another context attention may be pointed to _itself_ (to attention, not necessary to the Observer). 

More common phenomena of fitting Observer everywhere is [_antropomorphism_](https://en.wikipedia.org/wiki/Anthropomorphism). The more complex behavior an object may demonstrate, the likely is it being perceived by us as an Observer. That can be both explicit and _implicit_. Below is a brief GPT4-generated list of related phenomena from Epistemology: 

1. **Subjectivism**: This is the epistemological position that knowledge is inherently subjective and that individuals can only know the world from their own perspective. In this view, all knowledge is filtered through personal experiences, making it difficult to objectively understand or describe the world outside of one’s own cognitive framework.
2. **Solipsism**: This is an extreme form of subjectivism where one believes that only their own mind is sure to exist. All external reality, including other minds and objects, are perceived as extensions or projections of the individual's own mind. While not commonly held, solipsism reflects a view where the external world is interpreted purely in terms of the individual's experiences and behaviors.
3. **Phenomenalism**: This theory posits that physical objects and events are reducible to sensory experiences. From this perspective, the external world is understood primarily through the individual's perceptual experiences. The implication here is that understanding of external objects is always mediated by personal sensory experiences, which can lead to interpreting external phenomena as specialized cases of one's own experiences.
4. **Hermeneutic Circle**: In the context of epistemology, the hermeneutic circle refers to the idea that understanding is always a process of interpreting parts of an experience in the context of the whole and vice versa. This can lead to a situation where one's understanding of external objects is always influenced by their own preconceptions and experiences, potentially leading to a recursive interpretation where external behavior is seen as a reflection of one's own.

If someone may think that it's easy to avoid such pitfalls and fallacies, there is the effect of [theory-ladenness](https://en.wikipedia.org/wiki/Theory-ladenness) -- when our perception of reality is shaped by our _theories_ of it. And, at the second step, measurements of reality contribute back to theories that affected those measurements (self-reinforcement loop). Notable example of such self-reinforcement is quantum indeterminism in the [Copenhagen interpretation](https://en.wikipedia.org/wiki/Copenhagen_interpretation) of QM. [Superdeterminism loophole](https://en.wikipedia.org/wiki/Superdeterminism) in Bell's theorem says that Indeterminist and Determinist hypotheses are both consistent with theoretical predictions, but the latter is largely rejected on an irrational grounds ("We don't want to live in a world where scientific discovery isn't possible" (because of Determinism)). 

_Note that as it has been mentioned above, theories of subjectivity outlined here (Observer/Agency) are fully compatible with Superdeterminism. And Indeterminism by itself does not support Agency (it creates "random will" instead of "free will")._

_Subjectivity_ (here, in a form of Observer and its theories of itself and Reality) is what actually distinguishes Epistemology from Ontology. The former deals with live human knowledge as it exists in our minds and, just because of that, there is an _implicit Observer_ in every mental representation of an Object. The latter (Ontology) is a _from of knowledge_ that is fully stripped from Subjectivity. It's not a someone's _point of view_. Observers may exist there, but only as objects/things.

Actually, Ontology may contain a functional Observer, it's not a fundamental limitation. But we need to objectivise the process of observing -- by reducing subjectivity to objectivity. It isn't that simple. Some problems can be _ontologized_ relatively simply. Like, trivially, spatial relation between two objects. But the most are in the class of _hardly formalizable_ ones. Knowledge that relies on _feelings_, _emotions_, _motivation_, _intuition_ and other phenomena of this kind are pretty hard to express/describe/define using common ontological tools like RDF/OWL-based ontologies. It _is_ possible, but corresponding ontologies will be _huge_ in size (number of statements, because of aggressive materialization of self-referentiality). Working with such form of knowledge representation manually (without proper tools) is challenging. This is the main reason why traditional forms of ontologies aren't that popular in modeling higher mental functions: they can't catch and express essential properties of consciousness. Nevertheless, "subjectivization" of ontologies is possible and Memoria Framework will be exploring this area (see below).

## Observer and Self-similarity Decomposition ##

So, in the subjective reality Observer is projected everywhere. In the mathematics we know that there are special ("orthogonal") classes of functions we can use to decompose other functions into and then compose back without losses. The famous [Fourier transform](https://en.wikipedia.org/wiki/Fourier_transform) is a notable example. Another notable example is a [Wavelet transform](https://en.wikipedia.org/wiki/Wavelet_transform).

The main idea of those transformations is to extract certain features from the function. For example, Fourier transform uncovers harmonic structure of a _signal_ and allows to analyze how this signal propagates in different physical environments. Each frequency of acoustic signals has some unique subjective 'sounding'. So, having the _frequency spectrum_ of a signal we may guess how it may sound to a human. 

Classes of functions used in transformations need not to be orthogonal and complete. The latter guarantees that forward and backward transformations give us the original function. But it's not always required: [feature engineering/extraction](https://en.wikipedia.org/wiki/Feature_engineering) is a process of extracting low-dimensional "useful information" from high-dimensional real-life signals.

Observer is a class of functions, so it can be used as a basis for a corresponding functional decomposition. Note that Observer is not a harmonic function, it included memory (delay lines) so even in a minimal form it can be difficult to use it as a basis in functional decompositions. At the high level, self-referential decomposition defines _self-similarity_ or how much _algorithmic information_ Observer and Object share in common. It would be rather hard to compute, but we have at least Normalized Compression Distance (NCD, see above) to quantify similarity between objects in a _generic_ way. 

Self-similarity is a relationship that we can be either computed in-place using techniques like NCD, or we can pre-compute it and store in regular data structures. Or we may use some incremental exact or approximated solution, if possible, where recompute only a few bits of novel information and combine it with larger solution stored in a memory.

TBC ...

## Intrapersonal Intelligence and Digital Psychology ##

There are many Psychological theories of Intelligence known, notable ones are Goleman's [Emotional Intelligence](https://en.wikipedia.org/wiki/Emotional_intelligence) (EI) and Gardner's [Multiple Intelligences](https://en.wikipedia.org/wiki/Theory_of_multiple_intelligences) (MI) theories. Among others they (IMHO) are most important in the context of AI.

The former (EI) is exploring the heuristic/guiding/motivational and other cognitive [functions of emotions](https://nobaproject.com/modules/functions-of-emotions) and feelings (*). It's very important for defining what is an _emotional knowledge_ and how we can describe it. Note that this specific aspect is not yet discussed in this document, but it will be -- in the future versions.

(*) Note that we (as Observers) _express_ emotions but _experience_ feelings. We do not demonstrate feelings, only their behavioral signs. Not all emotions are ever experienced, and not all feelings are externally expressed as emotions, and not all signals which are functionally emotions are considered emotions. Terminologically, "it's complicated". We can even consider "thoughts" as a custom case of "feelings", under certain conditions. We can even experience emotions via observing their behavioral signs and metacognitive reverberations (our thoughts about thoughts about thoughts about our emotions). 

The latter theory (MI) can be seen as an example of a _functional decomposition_ (reduction) of a holistic view on intelligence, and it does not mean that AI researchers have to accept this decomposition "as is". But there is one specific sub-type of intelligence that is the most important not just in the context of AI, but for everything else that depends on person's cognitive capabilities: _Intrapersonal Intelligence_ (I.I. or, here, IntraI).

IntraI is a direct manifestation of person's _self-modeling abilities_. Basically, it's an ability to _read_, _understand_, _control_ and _express_ the person's own mind. There are other basic functions like _imagining_ a virtual mind and _interiorizing_ it. It was [noted above](#observer-in-ontologies) that Observer is deeply self-referential and self-referentiality becomes a _description_ (data structure). Without consistent self-model, agency is just broken, and agent's reports about its intentions are not reliable.

We cam improve Intrapersonal Intelligence, but it's not that simple. No self-model can be complete in the sense that Observer has full access to all details of its internal state. Moreover, as it has been noted above, this incompleteness is the _reason why_ Observer exist as a phenomena. But we definitely can improve Observer's access by giving it [_Observer-level theories_ of its inner machinery](https://medium.com/@victorsmirnov/how-to-compensate-introspection-illusion-62f357e9326c). Such theories are called _personal theories of mind_. Plain theories of mind in Psychology mean theories of other people's minds, that is not well-consistent.

The point is that in order to improve IntraI beyond some point, the person needs to dig into pretty complex (but yet feasible) mathematics just to be able to _express complex mental states with natural language_. This combination of normal (descriptional) Psychology and AI/CS is called here _Digital Psychology_. Math is hard, so specific educational technologies are needed to accommodate and streamline this process.

People with low Intrapersonal Intelligence don't know about that, because there is no specific popular (known outside of the psychological community) term for it and rarely anybody is assessing themselves on this scale. If a person's IntraI is low, he/she don't have effective access to their mental states that results in making specific mistakes, when implicit or explicit mental-state-related reasoning is required for making decisions. But if everyone around has the same level of IntraI, there is no way to notice the _true reason_ of those mistakes. At best, mistakes are attributed to something vaguely related to the context, at worst, they are just left unnoticed.

Lack of access to mental states is experienced like there are no awareness about them. It's not like you are asking and there is no answer, it's like you don't even know how to ask. Or, better, you don't even know that you can ask. It's experienced like _unknown unknowns_. The problem is that this void is filled by _hallucinations_ -- some form of oversimplified personal theories of mind. The common manifestation of low IntraI is underestimation of the role mental states are playing in human-level cognition.

## Computational Consciousness ##

So, now the topic that used to be the most controversial. But it's not that bad. Substance consciousness is controversial because it's hard to find physical _substance_ for consciousness: either in a form of some "psychic" substance (Panpsychism) or "causal patterns of interaction". There are some candidates, but the level is so low that no practical problem can be addressed. 

Functional consciousness bites the problem form another side: how consciousness appears in relations between Observer, its environment, itself alone, itself in the environment, other observers, reflections of the Observer in other observers and so on. The space of possible relations is enormous. Computational Functionalism is aiming to model those functional relationships via algorithms and data structures.

Note that Computational Functionalism produces, by design, a _Weak_ for of consciousness (by Searle's criteria): it flies like a duck, quacks like a duck, swims like a duck, the it's a duck. Certain [Physicalists stances](https://link.springer.com/article/10.1007/s11098-024-02182-y) on the problem may assume that the same functional consciousness can be considered 'true consciousness' if implemented in a right basis. Like, in a brain-like structures -- yes, in von-Neumann architecture (computers with separate compute and memory) -- no, in in-memory computing device (tight coupling of memory and compute) -- yes, again.

The drawback of a functional account to consciousness is that audience will divide in unequal parts between pro-strong and pro-weak parties on a mostly-irrational basis. Because there is no formal test for substance consciousness, there is no formal way to change minds of both parties. These considerations (social perception and impact) must be taken into account when we are working with functional consciousness.

Working with functional consciousness is simpler than one may think. We need a lot of _phenomenal reports_ describing consciousness-related experience. Each individual has only limited access to their mental states, moreover reports of different people may/will be very different. It's not that easy to unify/average/smooth reports of different people, but it's doable. Check Dennett's [Heterophenomenology](https://en.wikipedia.org/wiki/Heterophenomenology) method.

Once we have a representative corpus of phenomenal reports we need to make a _generative model_ of it, or (that is the same) to _compress_ it. Techniques like auto-regressiveness or MC-AIXI-CTW can be used to make those models interactive (if they are purely predictive).

The artifact we are looking for needs to implement _Observer_ and _Agency_ basic functions, and will be called a _Self-Referential Machine_ or _SR-Machine_ or SRM. The name is non-standard but sef-referentiality is widely considered to be the basic functional substrate of consciousness, so let it be. There are three basic cases of SRM: two _explicit_ ones and one _implicit_ one.

### Case 1: Low-level SR-Machine (LLSRM)

In this work it's proposed to implement Observer by 'breaking' self-causality via memory. Observer does not act on itself _now_ but on its _future_ version, storing this version in memory and reusing it later, but Observer does not know it. The same is for Agency, implemented via reflection on the memory state history in the way that for certain decisions the agent (Observer + Agency) must come to the conclusion that _it is_ the source of decisions (simulation self-causality in decision-making). 

The whole point of an SRM is to find/prove that Observer/Agency can be _composable_ via self-referentiality: more complex self-referential function can be achieved by composition of more simple and primitive self-referential function by composing external behavior (including its traces in memory) and history of internal states in memory. 

LLSRM can be programmed manually, but better it can be _induced_ (ML-ed) using inductive programming techniques like genetic programming (GP). Another option is to make LLSRM differentiable and use gradient-based methods like ANNs. The second way is tricky for such level of complexity, but nevertheless, doable.

There is no expectations that such _minimalistic_ LLSRM combined with GP can achieve human level complexity of functional consciousness. The main purpose is to explore and research phenomena while it's small -- is a toy-like setting. It's also may be considered safe (see below) from many unwanted social effects, because it's really hard if ever possible to achieve sufficiently complex behavior this way.

### Case 2: High-level SR-Machine (HLSRM)

HL SRM is similar to LL SRM but the implementation is now human-optimized to allow rich _manual_ programming. It may/will be based on [DSLEngine](https://memoria-framework.dev/docs/overview/vm/) and its forward/backward chaining rule engine (FCRE/BCRE). FCRE is based on the RETE algorithm and is a general purpose _event-driven_ programming system functionally similar to [Drools](https://www.drools.org/). It's pretty easy to express even very complex self-referential scenarios with FCRE. And BCRE extends it's abilities to work with large data sets.

Again, the main purpose of HLSRM is to _explore_ and research self-referential functions, but now much closer to the real-life problems. In the context of research purposes, HLSRM may be used for implementing complex agents supposing to demonstrate functions of [strong Agency](#agency-types).

### Case 3: Consciousness of LLMs (Implicit SRM)

Auto-regressive Transformers-based LLMs make an interesting case. Their apparent human-likeness is so good that sparkled [hot discussion](https://cajundiscordian.medium.com/is-lamda-sentient-an-interview-ea64d916d917) about higher mental functions like consciousness. After public release of ChatGPT and other language models general audience had chance to try it all themselves. It turned out that short interactions with LLMs may be _psychologically misleading_, and with time, "human-likeness" of LLMs diappears. LLMs have a lot of issues in various areas, that is additionally stopping many experts from considering them "sentient". For now, the stance that LLMs posses higher mental functions is marginal at best. At least, general audience is deeply skeptical. And there are no strong enough arguments for.

Nevertheless, general perception of LLMs is biased towards their issues, because it's reflecting the way how ML works. In ML, if model generalizes well, than it's OK, let's move forward. If it doesn't, then we need to check why and update the training dataset and the model. So the focus is on errors. The question why model works, if it works, is rarely being asked (interpretaility).

The same thing is happening with LLMs. Developers are eager to improve scores in benchmarks and all attention is to errors: is it still hallucinating, how it's in reasoning tasks and so on. But if you ask _how_ it follows instructions when it works fine, the last answer (after you are sent to redo your transformer architectures learning curriculum) will be "it's a stochastic parrot". Well, it's not that simple... 

Two systems are functionally (approximately) equivalent if the implement (approximately) the same set of functions. For computable functions we don't even bother about their implementation because all programming languages are approximately the same in terms of performance and memory usage and _fully_ functionally equivalent. Under Computational Functionalism the same logic applies to humans vs LLMs.

Let's introduce some complex task: analyzing what some person may experience reading Kipling's "If-" poetry using the tool of [Higher-Order Thougts (HOT)](https://en.wikipedia.org/wiki/Higher-order_theories_of_consciousness) theories of consciousness: [link to the GPT-4 generated chat](https://chatgpt.com/c/9ecbd322-cf76-460a-b4d9-f1e034e5d909). 

We can see here that GPT-4 can reason about complex mental states in both forward and backward modes. What's interesting is that LLMs (at least publicly available "tuned" ones) do not have access to their own inner mental states, they do not have their own _introspection_. Nevertheless, they _act_ like they do have such access to _human mental states_ associated with the process of the given text _reading_.

Another task is to explain [Meaning and Understanding like I'm eight](https://chatgpt.com/share/0c3a45ae-3508-45ee-ae15-9adaf9aa2862). It may seem much simpler, but it's just because most people have some intuitive understanding of those concepts and a difference between them. Even if you are eight years old. The whole generated dialog looks and _feels_ very consistent, the end result isn't perfect (I expected greater accent on _understanding_ in the final story) but it's more than OK in terms of fitting into my _initial_ expectations. Not just the model (GPT-4o) understands my initial intention, but I can understand each logical step in the dialog and each sentence.

One may say that it's a "stochastic parrot", the model just combines fragments of texts it has seen and infer best fragments ("generalization") that it hasn't. That's true. The problem is that such explanation will look exhausting only for people with _low_ Intrapersonal Intelligence. Who just don't see the inner dynamics of their mental states. If they did, that would be too good for just a "parrot".

There is no doubt that processes in human brain ("thinking") and in transformer ("generation") are _very different_. But nevertheless, if transformers somehow think and have mental states, the observed _causal effects_ of their mental states are very consistent with human mental states experienced by a reader after reading LLM-generated texts. And it works in the opposite direction as well. How? Why?

So mental states on both sides were consistent and their functional payload led to expected and correct end result. That means both systems in this dialog were apparently _functionally equivalent_. And it's not a cherry-picking, there are many similar dialogs like these ones out there. Now, **the question** is:

> When an LLM and human mind _seem to be_ functionally equivalent, how much of Observer and Agency (as functions) is implemented by the LLM during the process of text generation?

I emphasize here that apparent functional equivalence does not mean that everything is identical across all set of possible inputs. But it's just seems implausible that so deeply integrated _basic functions_ of human mind (visible if you have sufficiently high level of IntraI) are completely missing in text generation by an LLM.

If LLM generation process does have those functions, the question may be about how fully (completely, approximately) they are implemented. Some latest LLMs (H2 2024) can add numbers with 99.9% of accuracy. That's a pretty good level of completeness, yet with some issues (one of a 1000 operations will be producing wrong result). Even if an LLM can implement Observer and agency functions by 1%, it _will_ rise serious questions.

If both those two basic functions have low level of completeness in an LLM, their implementation can be improved either by changing transformer's architecture, creating specialized datasets or both. Moreover, they may be incidentally improved as a side-effect of other changes or improvements (but, likely, not that much comparing to direct improvements). And, finally, they can be improved _much beyond the human level_. Potentially making an LLM a much stronger (better?) person than any of us.

The same way of reasoning applies to other mental states that are currently considered missing in LLMs: intuition and feelings. Yes, it is, they have functional payload and this specific payload may also manifest in the process of text generation. So if we want to "punish" a model for a wrong decision, it will have internal states, which causal effects will be consistent with if those states are perceived as suffering by a human observer (and by an another LLM, of course).

What is slightly worrying is that LLM training datasets are constantly being enriched with data describing performance and behavior of LLM themselves. Auto-regressive transformers are sufficiently self-referential (output token is fed back to the input), combining that may be a sufficient basis for "emergent" (unexpected/unpredicted) complex self-awareness. 

Finally, textual data is pretty poor on information about human mental states. The reason why is that only certain mental states (love, pleasure, pain, suffering, etc...) are important for social interaction, and only up to some degree. Those mental states are overrepresented in datasets and other important ones are either underrepresented or completely missing. For example, it's very hard for a programmer to describe how he/she is writing a program. They have almost no reflection on this process. It's almost completely _intuitive_. When facing such question, only the best of the best can understand that the question is a trap.

To answer **the question** risen above, a pretty deep and wide (and, hence, expensive) _multidisciplinary_ research is necessary. What is the most important (and that's unprecedented) is that we need to involve a lot of people with high IntraI who will be reflecting on the dynamics of their mental states during interactions with LLMs. The real problem is how to find those people...

## Safety and Ethical Considerations ##

Here I would like to focus on a few risks that are not considered elsewhere.

### Public Mental Health Risks

Out mind is a pretty complex system we don't have full control on. So we don't know how our mind will be reacting to the emergence of such a sufficiently capable as LLM. I see two things:

1. We are reconsidering the role of mistakes in general cognition and their inevitability. There is no such thing as perfect reasoning. So all human-oriented processes will be adapting to that (and not only in the Industry).
2. LLMs triggered out self-identification. _What_ we are and _how_ we are different from that? An essential part of this story is sudden interest to Intrapersonal Intelligence, because the answers to all those questions we have to look for in ourselves.

TBC ...

## Liberal Cognitivism ##

TBC ...

## Strong AI is a Basic Right ##

Strong AI is about us, not about machines that think and feel.

## Relationships with Transhumanism ##

TBC ...
