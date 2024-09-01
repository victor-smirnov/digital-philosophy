# Memoria and Artificial Intelligence #

**Note that this page is work in progress, as well as other parts of Memoria. So be patient. Thanks!** 

Since AI is getting a hot topic and many folks started asking me about participating in AGI startups, I decided to outline my view on the topic using easy language. The following is my (Victor Smirnov) personal view on AI that other committers and contributors may not necessary share or support.

[TOC]

## Too Long; Don't Read ##

My views on AGI are largely influenced by or mostly consistent with the following theories: 

1. Graziano's Attention Schema Theory (AST), explaining how self-referentiality contributes to phenomenal reports.

2. Damasio's Somatic Markers Theory (SMT) explaining basics of emotional intelligence: guiding function of emotions in decision making.

3. Jean-Louis Dessalles' Simplicity Theory explaining subjective attractiveness in a fundamental way.

4. Tononi's Integrated Information Theory (IIT), linking conscious states with descriptional complexity.

5. Daniel Dennett's Cartesian Theater and Multiple Drafts. Consciousness is not an illusion in a strict sense. But traditional first-person view on it is heavily biased, that leads to various paradoxes. 

6. Ray Solomonoff's theory of Universal Induction (UI). This theory explains theoretical and practical limits of problem solving. 

7. Jurgen Schmidhuber's Artificial Curiosity (AC) and his theory of intrinsic reward, explaining highest emotions in a mathematically universal way.

8. Schmidhuber's Goedel Machine, explaining limits of recursive self-improvements. 

AST gives clever insights into how certain important subjective phenomena emerges in a self-referential structures like "attention schemes" but it leaves some important questions unexplored. In this page I introduce a semi-formal self-referential machine, self-referential algorithms and self-referential data structures constituting self-models. There is nothing special about them from mathematical perspective, but they have certain properties by turning computational phenomena into descriptions. For example, how gradual incompleteness of self-referentiality leads to the lack of "process introspection" and, by that, leads to "inexplicable" elements in phenomenal reports, like qualia, which are 

Damassio introduces guiding function of emotions in its SMT that manifests by affecting decision making in an unconscious way. Schmidhuber proposes universal scheme for certain higher emotions, but emotions are not feelings. Conceptual jump from emotions to feelings requires subjectivity, and I'll try to show how feelings are self-models of emotions. 

Self-models can be learned directly from data via induction. Solomonoff's UI is complete but not computable. Computable induction can't be complete, but can be approximated with various techniques. If self-models are expressive enough to emulate universal computer, they can be used to host they inductive learning, giving functionally complete metacognition. It turns out that phenomenal consciousness is not just a side-effect of intelligence, it's a substrate-independent AI by itself, capable for problem solving.

Hard problem of consciousness then can be reformulated the following way: **can all phenomenal reports be composable and decomposable in a computable way**. To prove this, it is necessary to provide minimalistic but universal self-model that can evolve with algorithmic induction into any human phenomenal report *in the limit*. So, no subjective phenomena will be left unexplained in the limit.

Memoria provides decent environment for self-modeling. It has framework for advanced data structures like self-indexes, that can turn self-models into advanced databases, and allows deploying such structures at scale in distributed and decentralized manner. Memoria has vertically integrated AIO subsystem from raw block devices to networking and C++-based heterogeneous computations unifing CPUs, GPUs and ASICs. It's primary goal to make approximations of Universal Induction practical, which is necessary to evolve self-models.


## A Sketch of Main Ideas ##

1. There are theoretical schemes for AGI, but they are not finitely computable. Any finitely computable AGI will not be complete or, in other words, truly generic. These schemes can be approximated, if we are agree to sacrifice some generality to achieve desirable performance in certain domains.

2. Human brain is not an AGI in that narrow sense, though it can be true AGI in the limit, providing infinite time and space. Being an approximation of AGI, it can solve some problem classes efficiently (fast), being slow on all other classes.

3. One of possible AGI approximation strategies is trading memory for speed. AGI is based on search in Turing-complete programs space that is too huge to be tractable for anything except toy domains. 

4. To speedup this process we can apply restrictions to the program space, so the search will be performed only within small subset of the space. The method is no more complete but can be flexibly tuned for very wide variety of problem classes just by changing the system of restrictions. 

5. In most cases the system of such restrictions is poorly compressible, so the only way to specify it, is by direct description via data structures. In other words, an AGI approximation, built on this principle, will have huge database. The bigger the database, the more generic intelligence such a system will have. There are theoretical results that practical AGI will be complex in any means, and present complexity of advanced ANNs is reflecting this principle. 

6. This database will be much more complex than those ones currently in use. It will be based on very advanced coding schemes and data structures. Memoria is all about that.

7. It's not that easy to determine classes of problems brain-AGI can solve efficiently: human-like AGI approximation problem.

8. Hard problem of AI reformulated: does phenomenal consciousness have any problem-solving abilities by itself? Yes, it does. 

9. Sentiments and emotional Intelligence: emotions, feelings and guiding function of emotions.

10. From emotion to feeling. Self-referential machines have a "dualistic" property represent computations as data and vise versa. They can build self-model allowing them to act on the stored log of their own previous states in the way increasing global and local utility functions. Entire universal Turing machine can be implemented this way, performing self-referential operations on self-referential data structures. 

11. Particularly, this type of machine can catch certain fundamental computational phenomena and use them as descriptions. For example, inherent incompleteness of self-referentiality (infeasibility to build a complete self-model) results in simplified self-models systematically lacking some causality links. Everything systematic (even if this systemacy is stochastic) can be turned into description. 

12. For example, if we can somehow arrange this lack of causal structure in self-descriptions in a multi-scale way, we can turn corresponding records in memory logs into multiscale data structures, analogous to [wavelet trees](https://bitbucket.org/vsmirnov/memoria/wiki/Multiary%20Wavelet%20Tree), instantly enabling many sophisticated algorithms on top of such data structures. 

13. A set of such structures with "dualistic" properties emerging in self-referential computations can be viewed as a formal language, describing "phenomenal reports" in memory logs of self-referential machine. This formal language can be Turing-complete, so, in principle we can build another self-referential machine inside a self-referential machine. 

14. Finally, a Normalized Information Distance (NID) scheme can be build on top of this formal language, measuring similarities and differences between everything in a pretty generic way. NID-based encoding enables differential encoding when new data is represented as old data + some delta of novelty. NID can be efficiently approximated with Normalized Compression Distance (NCD). Simpler schemes are also possible.

15. NCD aligns naturally with mutiscale data structures from (12) and efficiently generalizes them to any domain where there is a more-or-less efficient compression scheme, that is Multiscale NCD-decomposition. NCD works fine with lossy compression.

16. Particularly, self-referential decomposition of an object can efficiently implement its Mutiscale NCD decomposition relative to the entire history of the self-referential machine. In such decomposition some information, that is completely new to the machine, will appear as a very rude approximation or "vagueness" in phenomenal reports. Nevertheless, it contains some bits of actual data that contribute to the difference between vague elements of phenomenal report guiding decision-making.  

17. If we define needs and emotions somehow for the self-referential machine, then motivations and feelings are self-models of needs and emotions correspondingly. Both needs and emotions are kind of internal stimulus, so motivations and feelings are sub-type of senses. 

18. All senses have "motivational" component that is a manifestation of guiding function of emotions to decision making reflected in phenomenal reports. It looks similar an attractor in non-linear dynamics, or gravity in physics. So, "something" happens behind the scene, at the level that is not accessible, and at the accessible level we have results of this hidden process.

19. If needful portrait codes the set of agent's goals, and emotional portrait codes some stimulus relatively to the needful portrait, then sentiment is a self-model of emotional portrait of the stimulus.

20. Until this moment it was not implied that self-referential machine has any special properties enabling it to learn like a human just because it resembles our core cognitive abilities. Nothing special is about such machine relative to learning. It's implied that self-models are learned separately from self-referentiality with some kind of approximated program induction mentioned above: (1) - (7). 

21. But if a self-referential machine is expressive enough, it can host such inductive learning partially or entirely, resembling not just cognition as thinking but also cognition as obtaining new knowledge in a unified way. By separating cognition to self-referentiality and induction over it we are making entire problem much simpler to tackle.

22. The idea of self-referential machine's solution to problem of qualia in AI is that there is no such thing as "red color", the minimal element of memory log of such machine is "I see the red color", that is not static structure encoded in memory, but also a dynamic computation (in another context). In other words, some form of observer is always implied, and it is finally the machine itself. Note that this is a form of pan-proto-experientalism but in the "software" when higher-level experience is composed from lower-level ones in a computable way. Note also that this "experience" is also physical, because both the machine and information processing on it are physical.

23. From the functional perspective, qualia are soft bounds in building self-model of stimulus. Self-model developing is a computationally very hard task, but this complexity is not evenly distributed. Some elements of phenomenal report emerges faster than others. Some elements will remain underdeveloped forever and, because of their stable hardness, may become descriptions themselves, like qualia.

24. Note that if we accept that "rational" problem solving ability can be unsound and incomplete, then we can reduce rational intelligence to emotional one and implement it on the same computational substrate. Then such rationality will be heavily biased in many ways, and reduces to specific type of phenomenal report like "I'm reasoning logically here". Note that sound and complete inference not feasible for everything except very narrow sets of problems.

25. The last question is "why" self-referentiality. Any on-line learning system must maintain consistency of its knowledge base, so it must somehow reason about itself. Any sufficiently large computer has non-perfect hardware that becomes more error-prone with size and has some kind of "homeostasis" to maintain. Self-referentiality emerges naturally in such environments. Moreover, all modern IT systems not just stores part of their computational states into logs, but can even act on this stored state, thus having some rudimentary self-model. Artificial consciousness is inevitable for sufficiently large and generic AI. 

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

36. Memoria's design follows bottom-up evolutionary path to AGI. Instead of building "AGI-in-a-box", Memoria's approach consists in decomposing such complex thing as human-level metacognition into well-manageable building blocks that can be used together or independently, to bring new qualities into existing applications.

## Types of AI ##

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

## Computational Consciousness ##

### Self-Referential Machine ###

Note that there may be many types of self-reference. One type is a program that can read it's own [description](https://en.wikipedia.org/wiki/Kleene%27s_recursion_theorem). Here, self-referentiality is meant in a broader sense, as ability of a program to observe and react on its own *progress in computation*. 

> *Definition*. In this context, Self-referential machine (**SR-machine**) is a class of computational formalisms (computation + memory architecture) ensuring that sufficiently good approximations of Observer/Agency-like behavior and self-reporting, defined above, will be discovered faster by an algorithmic induction process than it can be achieved for other classes of formalisms.

So, there is *nothing special* in a SR-machine *by itself*. It does not have any extra expressive or computational power relative to other types of machines. Specific features, that make it essentially self-referential, may not be necessary immediately visible, for example, with using some "self-referential data structures". What matters is actual *efficiency of algorithmic induction* resulting in Observer-like behavior and *self-reporting*.

There are currently three types of algorithmic induction, that work in practice:

1. *Manual process*, the same one we are using for writing programs, with human programmer deeply in the loop.
2. *Program-space exploration*, like Genetic Programming and other Metaoptimization techniques.
3. *High-dimensional differential methods* for metric spaces like Deep Learning.

So the question is if there is a way to speed up specific class of algorithmic induction is the direction we need. The entire point of this article is that we can use [introspection](https://medium.com/@victorsmirnov/how-to-compensate-introspection-illusion-62f357e9326c) to get those bits of information. 

To facilitate this process there will be the *ObserverKit* (or *AgentKit*, depending on a conjuncture) sub-project in the  Memoria Framework. [DSLEngine](https://memoria-framework.dev/docs/overview/vm/) will be containing a [Drools](https://www.drools.org/)-like RETE-based forward-chaining rule engine (FCRE). RETE works by finding patterns in events in the working memory and it seems to be a perfect fit to unify the process/state duality in a single set of abstractions. 

ObserverKit is meant to be used for *studying* Observer-related computational phenomena in a manual way or by using a simple ML (producing easily interpretable results). It's also expected to be completely *safe* (see below). Given the history of AI and ML, it's highly unlikely that it may demonstrate significant level of human-likeness or achieve/exceed human level in autonomy.

### Computational Consciousness of LLMs ###

**Note that this section is currently being rewritten to take into account my recent thoughts and findings.**

In 2023 LLMs made sensation demonstrating very high level of human-likeness in reasoning together with pretty good (even superhuman) generality, but *without any autonomy*. For me it was huge surprise, I didn't expect that. Despite other things, this specific feature set opens a completely new design space: if LLMs can have an Observer, what type of entity it will be?

Going fast forward, no, LLMs are not conscious in a human-like/level way, but it's not that simple. 

Surprising level of human-likeness triggered discussions if this human-likeness is indeed backed by human-level higher mental functions. It's a purely psychological effect, short interactions with LLM may be deceiving. And after some time it starts being obvious that (on long texts) their behavior becomes much less human-like. Actually, neither human-level, nor even human-likeness is required for consciousness (argument: newborn infants are conscious), but it's overall *human-like behaviour* that forces people *to feel* that this thing may be or is conscious. Unfortunately, if some person starts feeling this way, there are no *rational* arguments to disprove it. As it has been noted above, even Operational Amplifier can be considered as a primitive Observer -- an entity having *some* phenomenal experience. Nevertheless, some tests can be proposed.

> *Definition*. Computable Observer's *metal state* is a part of computational state that is available for self-reporting, either *passively* (experience) or *actively* (volutionary processes, communication).

It has been noted above that phenomenal consciousness is very hard to compose from and decompose to more primitive elements from the Observer's perspective. In other words, it tends to be _holistic_. Human mental states are very rich in their manifestations, so the intuition is that if an LLM has comaprable-to-human general verbal intelligence, it *may* have comparable level of *mental states reporting*. How do they perform? Actually, we need a *special* benchmark for that. Psychological benchmarks developed for humans are not directly applicable to LLMs. These benchmarks implicitly assume specific cognitive architecture (human brain), that LLMs do not have. So, extrapolations will not work...

Counter-intuitively, human-level mental states reporting is [poor at best](https://home.csulb.edu/~cwallis/382/readings/482/nisbett%20saying%20more.pdf) (an attempt to report a mental state apparently interfere with it), except a few areas closely related to *basic needs* and professional occupations. For example, if you are a programmer, try explaining *how* you write a program. For most people such *intermediary cognitive activity* is not reportable. As a consequence, textual datasets are extremely poor on mental states description. There is some information, of course, but it's skewed towards rather narrow domains.

I haven't conducted an extensive research yet, but ad-hoc interactions with LLMs shows that their abilities to *mental-states-level reasoning* do not exceed what is possible given the corpus of training texts. 

For example, LLMs can reason about possible Alice's *feelings* in a given circumstances, but no deeply than it's usually described in psychological literature. And asking the model to elaborate does not help -- it starts circling around some pre-existing disposition. The same thing happens when they don't have enough statistics for elaboration on some topic.

Another example is reasoning in [Higher-Order Thoughts (HOT)](https://en.wikipedia.org/wiki/Higher-order_theories_of_consciousness) theories. LLM can do it at a surprisingly good level, but no deeper than it's possible given the training set. Nevertheless, even this level of HOT-reasoning was surprising, it opens up *completely new* applications.

Despite inherent difficulties, human reporting on their mental states is qualitatively different than LLM's one, when they are asked to *elaborate of their feelings*. Speaking figuratively, for a person with decent mental-state reflection abilities, speaking with an LLM in this context may feel like you are speaking with a scarecrow. Don't expect that current (2023) generation of LLMs may be your *soulmate*. But it may change in the future...

If we want (see below safety consideration) to make LMs more human-like in this area, or, what is *the same*, to give them better emotional (intra-personal) intelligence, we need two things. Form other side, this is also what we should avoid doing *if we want to limit* our LMs in their human-likeness (at least, until we are ready to handle it gracefully).

1. *Better*, more recurrent, *architecture* of the LM to support required Observer's machinery.
2. *Enriching* training datasets with mental states descriptions.

In order to do it efficiently, we need a very special skill, that we even don't realize we are lacking it, -- *verbal reports on mental processes*. IT can be trained, but [training](#process-introspection) will be *slow* and *expensive*.

In the context of Memoria I will be working on special tools for capturing mental states and corresponding data enrichment. 

## Safety and Ethical Considerations ##

TBC ...

## Strong AI is a Basic Right ##

Strong AI is about us, not about machines that think and feel.

## Relationships with Transhumanism ##

TBC ...
