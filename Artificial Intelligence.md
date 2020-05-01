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

22. The idea of self-referential machine's solution to problem of qualia in AI is that there is no such thing as "red color", the minimal element of memory log of such machine is "I see the red color", that is not static strucure encoded in memory, but also a dynamic computation (in another context). In other words, some form of observer is always implied, and it is finally the machine itself. Note that this is a form of pan-proto-experientalism but in the "software" when higher-level experience is composed from lower-level ones in a computable way. Note also that this "experience" is also physical, because both the machine and information processing on it are physical.

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

2. **Incremental learning problem**. Even if we already selected basic machine and identified bootstrapping set of models, we need an approximation of Universal Search to infer new models from data. Though this process is well-defined mathematically, it's not that easy to implement it in practice, because program space is too big for exhaustive search. In order to achieve desired performance we have to restrict this space somehow, either by restricting model class (as in MC-AIXI) or by using various heuristics as in Genetic Programming and Metaoptimization, or by a database of declarative and procedural restrictions applied to the search space. The latter case is the most flexible and the most complex one because such database may be very big in size even for simplest problems. 

What is important, these two problems can be developed independently, by different teams focused on their problems. This the way to go for Memoria. It will be focused on **compressed data structures**, where compression is understood not just in space-saving context, by as an enabler of generic intelligence. Additionally, Universal Search approximations are very important for general intelligence. 

High-level ideas behind ALP was informally explained by [Marvin Minsky](https://www.youtube.com/watch?v=nXrTXiJM4Fg). In short, Solomonoff's approach to AGI is a top-down approach, when solid theoretical framework of AI is established first, and then we derive custom AIs with specific properties using approximation techniques. As opposite, classical bottom-up approach is playing around with different substances being inspired either from neuroscience or from cognitive science and waiting for intelligence to emerge in experiments. They can work together very well, as custom AIs are developed in a bottom-up experimental way and then merged into more powerful ensemble in top-down way by Solomonoff's Induction. 

## Self-Referential Machine ##

It's just a language to describe certain computational phenomena succinctly, there is nothing special from computational perspective.

## Psychology Basics ##

Psychological definitions of higher mental functions are not suitable for AI because they intermix subjective and objective planes, that leads to controversies. Better system of definitions is necessary.

## Emotional Intelligence ##

What it is and how it works from AIT's perspective. Rational intelligence as a custom case of emotional one, and not as a separate system. Rationality is illusion.

## Hard Problems of AI ##

## Process Introspection ##

Process introspection [can be improved.](https://medium.com/@victorsmirnov/how-to-compensate-introspection-illusion-62f357e9326c)

## Strong AI is a Basic Right ##

Strong AI is about us, not about machines that think and feel.

## Evolutionary Strategy for AGI ##