# Embodied Cognition and the Foundations of Embodied AI

> Embodied cognition is the family of views holding that minds are shaped in a non-trivial way by having a body that acts in an environment. This chapter traces the position from Brooks's behaviour-based robots and Harnad's symbol grounding problem, through enactivism, sensorimotor contingency theory, grounded cognition, morphological computation and developmental robotics, to the predictive-processing synthesis that now dominates. It then sets out the critiques: that embodied cognition explains little in experimental psychology, that several flagship effects failed to replicate, and that large language models do surprisingly well with no body at all. That last point has reopened the oldest question in the field, whether meaning needs a body or only grounding, and a sharper one beside it, whether consciousness needs a living body. For a project on mind emulation the lesson is that a brain is not the whole of the system a mind runs on, and that whether a non-living substrate can be conscious is unresolved.

## Why this matters for the project

This dossier asks whether a mind can be preserved, emulated or moved to another substrate. Every position in this chapter is a claim about how much of a mind lives outside the neurons, which makes embodied cognition the first hard constraint on that question.

Start with the naive picture: record a brain's wiring, run it on a computer, and the mind resumes. Sensorimotor contingency theory says that what seeing is like consists in mastery of the laws relating movement to sensory change [O'Regan & Noë, 2001](https://doi.org/10.1017/S0140525X01000115), and those laws belong to a particular body in a particular world. Enactivism ties meaning itself to the self-maintaining organisation of a living system [Varela et al., 1991](https://mitpressbookstore.mit.edu/book/9780262529365). Work on morphology shows that bodies do control-relevant work the nervous system never had to learn [Pfeifer & Bongard, 2006](https://mitpressbookstore.mit.edu/book/9780262537421), and developmental robotics shows that skills are acquired through a history of interaction tied to one body [Oudeyer et al., 2007](https://doi.org/10.1109/TEVC.2006.890271). On any of these views, an emulation run without a body, or in a very different one, would at best be a mind in a profoundly altered state and at worst not a mind. Seth's biological naturalism is sharper still: if consciousness depends on properties of living systems, a simulated brain need not be conscious at all, whatever body it drives [Seth, 2025](https://doi.org/10.1017/S0140525X25000032). Practitioners concede part of this; the 2025 State of Brain Emulation Report lists emulation and embodiment as one of the field's three core capabilities [Zanichelli et al., 2025](https://arxiv.org/abs/2510.15745), and [chapter 06](06-whole-brain-emulation-and-connectomics.md) takes that up.

The same literature supplies the hopeful side. The plasticity evidence O'Regan and Noë rely on, sensory substitution and adaptation, suggests sensorimotor mastery can be re-learned on a new body. The extended-mind thesis implies that a mind's boundary is already substrate-flexible [Clark & Chalmers, 1998](https://doi.org/10.1093/analys/58.1.7). Predictive processing says what matters is a generative model of body-world coupling, which a virtual body could in principle supply [Parr et al., 2022](https://doi.org/10.7551/mitpress/12441.001.0001). One live position holds that bodies are one route to grounding, not the only one [Mollo & Millière, 2023](https://arxiv.org/abs/2304.01481).

| Thesis | If true, an emulation needs | Status |
|---|---|---|
| Sensorimotor contingencies constitute perception | A body with matching movement-to-sensation laws, or long re-learning | Plasticity documented; constitutive claim contested |
| Sense-making requires living autonomy | Self-maintaining, norm-generating organisation | Philosophically developed; no agreed test |
| Morphology does control work | A faithful body model, not only a brain model | Well supported for control |
| Consciousness requires life | A living substrate, or no experience | Argued in 2025; contested |
| Grounding, not embodiment, suffices | Causal contact with the world by any route | Argued for LLMs; unmeasured |

Net assessment: brain-only emulation looks insufficient; "brain plus an adequately rich physical or virtual body plus interoceptive and homeostatic loops" is the minimum serious proposal; and whether any non-living substrate suffices for consciousness is open. For anyone hoping an animal's mind might one day be recovered from its preserved brain, the honest reading is that the brain is necessary but, on current theory, probably not sufficient. The body that trained it is part of what would have to be reconstructed.

## Key ideas

**Subsumption architecture.** Brooks's control scheme for his MIT robots: independent layers of behaviour, each wired from sensors to actuators, run in parallel, and higher layers can suppress or "subsume" lower ones. There is no central world model or planner. Built incrementally and forced to interface with the world through perception and action, "reliance on representation disappears" [Brooks, 1991](https://doi.org/10.1016/0004-3702(91)90053-M).

**Moravec's paradox.** Tasks hard for humans (chess, algebra) proved easy for computers, while things a toddler does effortlessly (walking, picking up a cup) proved very hard. Moravec's Mind Children attributes this to the far longer evolutionary history of sensorimotor skills [Moravec, 1988](https://www.ri.cmu.edu/publications/mind-children-the-future-of-robot-and-human-intelligence).

**Symbol grounding problem.** How can the symbols of a formal system have meaning intrinsic to the system rather than parasitic on an external interpreter? A system whose symbols are defined only by other symbols is like someone learning Chinese from a Chinese-Chinese dictionary, so some symbols must be grounded bottom-up in sensorimotor (iconic and categorical) representations [Harnad, 1990](https://eprints.soton.ac.uk/250382/).

**Enactivism and sense-making.** Cognition is brought forth by a living organism's self-maintaining interaction with its environment, not by recovering a pre-given world [Varela et al., 1991](https://mitpressbookstore.mit.edu/book/9780262529365). Sense-making is an autonomous system's capacity to evaluate its coupling with the world against its own viability norms: the minimal form of meaning. Thompson (2007) and [Di Paolo et al., 2017](https://academic.oup.com/book/5967) develop the theory.

**Sensorimotor contingencies and affordances.** Sensorimotor contingencies are the lawful ways sensory input changes as a function of the agent's movements; perceptual experience is the exercise of implicit mastery of these laws, not the having of an internal picture [O'Regan & Noë, 2001](https://doi.org/10.1017/S0140525X01000115). Gibson's affordances (Gibson, 1979) are the environment-side complement: possibilities for action a setting offers an animal relative to its body, held to be perceived directly.

**Grounded cognition.** The mainstream psychological version: conceptual knowledge is grounded in modal simulations, partial re-enactments of perceptual, motor and introspective states, plus bodily states and situated action, rather than in amodal symbols [Barsalou, 2008](https://doi.org/10.1146/annurev.psych.59.103006.093639). It keeps representations.

**Extended mind, parity principle and 4E.** If an external resource plays a role that, done in the head, we would count as cognitive, it is part of the cognitive process; a suitably coupled notebook is part of the mind [Clark & Chalmers, 1998](https://doi.org/10.1093/analys/58.1.7). "4E" (embodied, embedded, enacted, extended) is the umbrella label; the four differ on whether body and world merely influence, or partly constitute, cognition [Newen et al., 2018](https://academic.oup.com/edited-volume/28083).

**Morphological computation.** A body's shape, materials and dynamics perform functions that would otherwise fall to neural control: passive-dynamic walkers, compliant hands, "cheap design" [Pfeifer & Bongard, 2006](https://mitpressbookstore.mit.edu/book/9780262537421). Müller and Hoffmann analysed four canonical cases and concluded that morphology usually facilitates control or perception, and that genuine computation by the body, as in physical reservoir computing, is rare [Müller & Hoffmann, 2017](https://doi.org/10.1162/ARTL_a_00219).

**Predictive processing and active inference.** The brain is a hierarchical generative model that continuously predicts sensory input and updates on prediction error; action is another way of reducing error, by selecting the next input [Clark, 2016](https://doi.org/10.1093/acprof:oso/9780190217013.001.0001). The free-energy principle formalises this: organisms minimise variational free energy, a bound on surprise, through perception and action under a generative model of how their actions affect their sensations [Parr et al., 2022](https://doi.org/10.7551/mitpress/12441.001.0001).

**Intrinsic motivation and learning progress.** An agent rewarded for improvement in its own prediction ability selects activities of intermediate difficulty, where learning progress peaks, and developmental stages emerge without being scripted [Oudeyer et al., 2007](https://doi.org/10.1109/TEVC.2006.890271).

## State of the field (as of 2026-10-09)

### Origins

In AI the position crystallised in the late 1980s as a reaction against symbolic AI, which treated intelligence as manipulation of an internal world model. Brooks's robots and his 1991 paper made the engineering case [Brooks, 1991](https://doi.org/10.1016/0004-3702(91)90053-M); the companion essay "Elephants Don't Play Chess" (Brooks, 1990) made it polemically. Harnad supplied the semantic argument [Harnad, 1990](https://eprints.soton.ac.uk/250382/). Hubert Dreyfus supplied the philosophical backdrop, arguing from Heidegger and Merleau-Ponty that skilled coping does not apply rules to represented facts, which is why symbolic AI kept hitting the frame problem; in 2007 he judged even Brooks's work not Heideggerian enough [Dreyfus, 2007](https://doi.org/10.1080/09515080701239510).

### Cognitive science and robotics

The parallel movement in cognitive science has several strands, now grouped as 4E cognition [Newen et al., 2018](https://academic.oup.com/edited-volume/28083): enactivism [Varela et al., 1991](https://mitpressbookstore.mit.edu/book/9780262529365), sensorimotor contingency theory, offered to explain change blindness, sensory substitution and colour perception without an internal picture [O'Regan & Noë, 2001](https://doi.org/10.1017/S0140525X01000115), grounded cognition [Barsalou, 2008](https://doi.org/10.1146/annurev.psych.59.103006.093639) and the extended mind [Clark & Chalmers, 1998](https://doi.org/10.1093/analys/58.1.7), with Clark's Being There connecting the philosophy to the robotics [Clark, 1997](https://mitpressbookstore.mit.edu/book/9780262531566). Robotics gave the ideas engineering form, first as design principles argued from built systems [Pfeifer & Bongard, 2006](https://mitpressbookstore.mit.edu/book/9780262537421) and then with a corrective taxonomy [Müller & Hoffmann, 2017](https://doi.org/10.1162/ARTL_a_00219). Developmental robotics ([Lungarella et al., 2003](https://doi.org/10.1080/09540090310001655110); [Cangelosi & Schlesinger, 2015](https://mitpressbookstore.mit.edu/book/9780262028011)) models how skills, concepts and language emerge through staged interaction, with Intelligent Adaptive Curiosity as its key algorithmic result [Oudeyer et al., 2007](https://doi.org/10.1109/TEVC.2006.890271).

### The synthesis

The most influential recent synthesis is predictive processing and active inference [Clark, 2016](https://doi.org/10.1093/acprof:oso/9780190217013.001.0001); the open-access textbook presents perception, action, learning and planning as variational inference under a generative model [Parr et al., 2022](https://doi.org/10.7551/mitpress/12441.001.0001). Because the framework keeps internal models, it sits between classical cognitivism and radical enactivism, and both camps claim it.

### The LLM era

Large language models revived the grounding question. Bender and Koller argued that a system trained only on linguistic form has "a priori no way to learn meaning", understood as the relation between form and communicative intent [Bender & Koller, 2020](https://doi.org/10.18653/v1/2020.acl-main.463). Mahowald and colleagues distinguished formal linguistic competence, where LLMs excel, from functional competence (reasoning, world knowledge), where they remain uneven [Mahowald et al., 2024](https://doi.org/10.1016/j.tics.2024.01.011). Pezzulo and colleagues argued that living agents' generative models are tested through action and so are grounded in a way passively trained models are not [Pezzulo et al., 2024](https://doi.org/10.1016/j.tics.2023.10.002). Harnad accepts that LLMs do not understand but asks how they do so well, suggesting that language at scale carries constraints that act as indirect grounding [Harnad, 2024](https://arxiv.org/abs/2402.02243). Against these, Mollo and Millière argue that teleosemantic grounding is achievable by LLMs and that multimodality and embodiment are "neither necessary nor sufficient" [Mollo & Millière, 2023](https://arxiv.org/abs/2304.01481).

Roboticists have turned the embodiment hypothesis into a benchmark. The embodied Turing test asks AI "animal models" to match living animals in sensorimotor competence, shifting attention from language and games to abilities shared across species [Zador et al., 2023](https://doi.org/10.1038/s41467-023-37180-x). Brooks argues that humanoids trained from video lack the touch and force sensing on which dexterity depends [Brooks, 2025](https://rodneybrooks.com/why-todays-humanoids-wont-learn-dexterity/); [chapter 02](02-embodied-ai-state-of-the-art.md) covers the systems he criticises. Fei-Fei Li's November 2025 essay argues that LLMs lack grounding and that physically consistent world models are needed to connect perception to action, an industry endorsement of grounding, though not of biological embodiment [Li, 2025](https://drfeifei.substack.com/p/from-words-to-worlds-spatial-intelligence).

### Consciousness

Whether consciousness, as opposed to intelligence, needs a body is sharper still. Seth's 2025 Behavioral and Brain Sciences target article defends biological naturalism, the view that consciousness depends on properties of living systems, against computational functionalism [Seth, 2025](https://doi.org/10.1017/S0140525X25000032). [Chapter 04](04-machine-consciousness.md) takes this up.

## Debates and critiques

**Representation.** Brooks, enactivists and sensorimotor theorists hold that intelligence, or at least perception, does not require internal representations; Pylyshyn, replying to O'Regan and Noë, holds that vision still requires representation [Pylyshyn, 2001](https://discovery-pp.ucl.ac.uk/4257/1/4257.pdf); Clark and the active-inference school hold that generative models are indispensable.

**Strong versus weak embodiment, and replication.** Goldinger and colleagues argued that embodied cognition offers little purchase on classic phenomena of experimental psychology and generates few testable predictions [Goldinger et al., 2016](https://pmc.ncbi.nlm.nih.gov/articles/PMC4975666). Wołoszyn and Hohol replied that radical anti-representational embodiment is indeed a dead end but that the paper mischaracterised mainstream grounded cognition [Wołoszyn & Hohol, 2017](https://doi.org/10.3389/fpsyg.2017.00845). Separately, flagship "embodiment effects" fared badly in the replication crisis. The power-pose effect is the best-known casualty; a Bayesian meta-analysis of six preregistered studies, covering self-reported felt power only, found strong evidence for that effect but only moderate evidence among participants unfamiliar with it [Gronau et al., 2017](https://cris.maastrichtuniversity.nl/en/publications/a-bayesian-model-averaged-meta-analysis-of-the-power-pose-effect-). The 2016 Registered Replication Report of the pen-in-mouth facial-feedback effect found a mean difference of 0.03 on a 10-point scale (95% CI -0.11 to +0.16) against 0.82 in the original [Wagenmakers et al., 2016](https://doi.org/10.1177/1745691616674458), although a 2019 meta-analysis of 138 studies found a small but reliable facial-feedback effect [Coles et al., 2019](https://doi.org/10.1037/bul0000194). The general thesis that bodies matter for cognition is far better supported than many specific priming-style demonstrations.

**Morphological computation.** Does the body offload computation from the brain, as Pfeifer and Bongard and much soft robotics suggest, or mostly facilitate control and perception [Müller & Hoffmann, 2017](https://doi.org/10.1162/ARTL_a_00219)? Critics of the latter say its definition of computation is too restrictive.

**LLM grounding.** The newest entry in the table below, a January 2026 preprint, argues that a grounded but non-embodied agent can have every property that defines intelligence, so that embodiment is sufficient for intelligence but not necessary [Ma & Narayanan, 2026](https://arxiv.org/abs/2601.17588).

| Source | Claim | Is a body required? |
|---|---|---|
| Bender & Koller 2020 | Form alone cannot yield meaning | Grounding needed; body unspecified |
| Harnad 2024 | LLMs do not understand; language at scale gives indirect constraints | Yes, for understanding |
| Pezzulo et al. 2024 | Meaning comes from testing a generative model through action | Action-based testing required |
| Mahowald et al. 2024 | Formal competence strong, functional competence uneven | Agnostic |
| Mollo & Millière 2023 | Teleosemantic grounding is achievable by LLMs | "Neither necessary nor sufficient" |
| Ma & Narayanan 2026 | Intelligence needs grounding; embodiment is sufficient but not necessary | No |

**Enactivism confronting LLMs.** Classical enactivism ties sense-making to the adaptive autonomy of living systems, which implies that LLMs cannot make sense. Froese argues that enactivists face a dilemma and proposes that LLM competence is a non-biological sense-making grounded in technologically mediated embodiment [Froese, 2025](https://link.springer.com/article/10.1007/s11097-025-10132-0).

**The embodiment hypothesis in robotics.** Zador and colleagues and Brooks argue that animal-level sensorimotor competence, including touch and force sensing, is the missing foundation [Zador et al., 2023](https://doi.org/10.1038/s41467-023-37180-x); [Brooks, 2025](https://rodneybrooks.com/why-todays-humanoids-wont-learn-dexterity/). The vision-language-action programme [Ma et al., 2024](https://arxiv.org/abs/2405.14093) and Li's world-model agenda bet instead on scaling multimodal data and simulation.

**Consciousness and life.** Seth holds that neither disembodied computation nor a simulated brain need be conscious; computational functionalists reply that the relevant properties are organisational and substrate-independent [Seth, 2025](https://doi.org/10.1017/S0140525X25000032).

**Extended mind.** Aizawa's critical note in the Oxford Handbook argues that causal coupling to external resources does not make them constitutive of cognition, the coupling-constitution objection [Aizawa, 2018](https://academic.oup.com/edited-volume/28083).

## Open questions

1. Which cognitive capacities are constitutively, not merely causally, dependent on bodily morphology, and can this be tested rather than argued?
2. Is grounding (causal-informational contact with the world plus a selection history) sufficient for meaning, or is action-based testing of a generative model also required? Can fine-tuned or tool-using LLMs meet either criterion measurably?
3. Does sensorimotor mastery transfer across bodies? Sensory-substitution and prosthesis studies show plasticity, but no quantitative account says how much of a perceptual repertoire survives the radical change of sensors and effectors that an emulation in a new body would face.
4. Can the embodied Turing test be turned into benchmarks with agreed metrics, and how far are current systems from animal-level performance?
5. What is the minimal body, physical or simulated, that supports open-ended intrinsically motivated development, and must interoception or homeostatic regulation be part of it?
6. Is consciousness tied to life or to organisation? No proposed test discriminates these for artificial systems.
7. Why do LLMs perform as well as they do without sensorimotor grounding? Indirect grounding and the formal/functional dissociation are hypotheses, not explanations with predictive power.
8. How much of the embodied-cognition literature survives rigorous replication? A preregistered meta-analytic audit separating robust phenomena from priming-style effects is overdue.

## Where to start

1. One evening: [Brooks, 1991](https://doi.org/10.1016/0004-3702(91)90053-M) and [Harnad, 1990](https://eprints.soton.ac.uk/250382/). Together they define the problem space in under 40 pages, and both are available free online.
2. Free, the sceptic's counterweight: [Goldinger et al., 2016](https://pmc.ncbi.nlm.nih.gov/articles/PMC4975666) and the reply by [Wołoszyn & Hohol, 2017](https://doi.org/10.3389/fpsyg.2017.00845).
3. Free textbook: [Parr et al., 2022](https://doi.org/10.7551/mitpress/12441.001.0001). Chapters 1 to 4 give the conceptual story; later chapters give equations you can implement.
4. Inexpensive paperback: [Pfeifer & Bongard, 2006](https://mitpressbookstore.mit.edu/book/9780262537421), the most readable engineering introduction. Pair it with [Müller & Hoffmann, 2017](https://doi.org/10.1162/ARTL_a_00219).
5. Philosophical core: [Clark, 2016](https://doi.org/10.1093/acprof:oso/9780190217013.001.0001) for predictive processing, then [Varela et al., 1991](https://mitpressbookstore.mit.edu/book/9780262529365) for enactivism, with [Newen et al., 2018](https://academic.oup.com/edited-volume/28083) as the reference work.
6. The LLM-era debate: [Bender & Koller, 2020](https://doi.org/10.18653/v1/2020.acl-main.463), [Pezzulo et al., 2024](https://doi.org/10.1016/j.tics.2023.10.002) and [Harnad, 2024](https://arxiv.org/abs/2402.02243) on one side, [Mollo & Millière, 2023](https://arxiv.org/abs/2304.01481) on the other; then [chapter 02](02-embodied-ai-state-of-the-art.md) and [Ma et al., 2024](https://arxiv.org/abs/2405.14093) for models you can run.

## References

Sourcing: 41 of 41 references confirmed by web search on 2026-10-09; entries marked [not confirmed by search] could not be confirmed and should be checked before use.

1. Brooks, R. A. (1991). *Intelligence without representation*. Artificial Intelligence 47(1-3): 139-159. https://doi.org/10.1016/0004-3702(91)90053-M
2. Harnad, S. (1990). *The Symbol Grounding Problem*. Physica D 42(1-3): 335-346. https://eprints.soton.ac.uk/250382/
3. Dreyfus, H. L. (2007). *Why Heideggerian AI Failed and How Fixing It Would Require Making It More Heideggerian*. Philosophical Psychology 20(2): 247-268; also published in Artificial Intelligence 171(18): 1137-1160. https://doi.org/10.1080/09515080701239510 [URL not confirmed by search]
4. Varela, F. J., Thompson, E. & Rosch, E. (1991). *The Embodied Mind: Cognitive Science and Human Experience*. MIT Press (revised edition 2017). https://mitpressbookstore.mit.edu/book/9780262529365
5. O'Regan, J. K. & Noë, A. (2001). *A sensorimotor account of vision and visual consciousness*. Behavioral and Brain Sciences 24(5): 939-1031, target article with open peer commentary. https://doi.org/10.1017/S0140525X01000115
6. Barsalou, L. W. (2008). *Grounded Cognition*. Annual Review of Psychology 59: 617-645. https://doi.org/10.1146/annurev.psych.59.103006.093639
7. Clark, A. & Chalmers, D. (1998). *The Extended Mind*. Analysis 58(1): 7-19. https://doi.org/10.1093/analys/58.1.7
8. Newen, A., De Bruin, L. & Gallagher, S. (eds) (2018). *The Oxford Handbook of 4E Cognition*. Oxford University Press. https://academic.oup.com/edited-volume/28083
9. Pfeifer, R. & Bongard, J. (2006). *How the Body Shapes the Way We Think: A New View of Intelligence*. MIT Press, published October 2006 with a 2007 copyright date. https://mitpressbookstore.mit.edu/book/9780262537421
10. Müller, V. C. & Hoffmann, M. (2017). *What Is Morphological Computation? On How the Body Contributes to Cognition and Control*. Artificial Life 23(1): 1-24. https://doi.org/10.1162/ARTL_a_00219
11. Oudeyer, P.-Y., Kaplan, F. & Hafner, V. V. (2007). *Intrinsic Motivation Systems for Autonomous Mental Development*. IEEE Transactions on Evolutionary Computation 11(2), April 2007. https://doi.org/10.1109/TEVC.2006.890271
12. Clark, A. (2016). *Surfing Uncertainty: Prediction, Action, and the Embodied Mind*. Oxford University Press. https://doi.org/10.1093/acprof:oso/9780190217013.001.0001
13. Parr, T., Pezzulo, G. & Friston, K. J. (2022). *Active Inference: The Free Energy Principle in Mind, Brain, and Behavior*. MIT Press, open access (CC BY-NC-ND 4.0). https://doi.org/10.7551/mitpress/12441.001.0001
14. Goldinger, S. D., Papesh, M. H., Barnhart, A. S., Hansen, W. A. & Hout, M. C. (2016). *The poverty of embodied cognition*. Psychonomic Bulletin & Review 23(4): 959-978. https://pmc.ncbi.nlm.nih.gov/articles/PMC4975666
15. Wołoszyn, K. & Hohol, M. (2017). *Commentary: The poverty of embodied cognition*. Frontiers in Psychology 8: 845. https://doi.org/10.3389/fpsyg.2017.00845
16. Bender, E. M. & Koller, A. (2020). *Climbing towards NLU: On Meaning, Form, and Understanding in the Age of Data*. Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics: 5185-5198. https://doi.org/10.18653/v1/2020.acl-main.463
17. Mahowald, K., Ivanova, A. A., Blank, I. A., Kanwisher, N., Tenenbaum, J. B. & Fedorenko, E. (2024). *Dissociating language and thought in large language models*. Trends in Cognitive Sciences 28(6): 517-540. https://doi.org/10.1016/j.tics.2024.01.011
18. Pezzulo, G., Parr, T., Cisek, P., Clark, A. & Friston, K. (2024). *Generating meaning: active inference and the scope and limits of passive AI*. Trends in Cognitive Sciences 28(2): 97-112. https://doi.org/10.1016/j.tics.2023.10.002
19. Harnad, S. (2024). *Language Writ Large: LLMs, ChatGPT, Grounding, Meaning and Understanding*. arXiv 2402.02243, February 2024; journal version, titled *Language Writ Large: LLMs, ChatGPT, Meaning, and Understanding*, Frontiers in Artificial Intelligence 7: 1490698, published 12 February 2025, https://doi.org/10.3389/frai.2024.1490698. https://arxiv.org/abs/2402.02243
20. Mollo, D. C. & Millière, R. (2023). *The Vector Grounding Problem*. arXiv 2304.01481; journal version in Philosophy and the Mind Sciences 7(1), 2026. https://arxiv.org/abs/2304.01481
21. Zador, A., Escola, S., Richards, B., et al. (2023). *Catalyzing next-generation Artificial Intelligence through NeuroAI*. Nature Communications 14: 1597. https://doi.org/10.1038/s41467-023-37180-x
22. Seth, A. K. (2025). *Conscious artificial intelligence and biological naturalism*. Behavioral and Brain Sciences, target article published online 21 April 2025. https://doi.org/10.1017/S0140525X25000032
23. Froese, T. (2025). *Sense-making reconsidered: large language models and the blind spot of embodied cognition*. Phenomenology and the Cognitive Sciences, online first (listed as forthcoming; some sources give 2026). https://link.springer.com/article/10.1007/s11097-025-10132-0 [URL not confirmed by search]
24. Brooks, R. (2025). *Why Today's Humanoids Won't Learn Dexterity*. rodneybrooks.com, September 2025. https://rodneybrooks.com/why-todays-humanoids-wont-learn-dexterity/
25. Li, F.-F. (2025). *From Words to Worlds: Spatial Intelligence is AI's Next Frontier*. Essay, drfeifei.substack.com, 10 November 2025. https://drfeifei.substack.com/p/from-words-to-worlds-spatial-intelligence
26. Zanichelli, N., Schons, M., Freeman, I., Shiu, P. & Arkhipov, A. (2025). *State of Brain Emulation Report 2025*. arXiv 2510.15745 (v1 17 October 2025; v3 5 November 2025). https://arxiv.org/abs/2510.15745
27. Ma, Y., Song, Z., Zhuang, Y., Hao, J. & King, I. (2024). *A Survey on Vision-Language-Action Models for Embodied AI*. arXiv 2405.14093 (v1 May 2024; v7 February 2026). https://arxiv.org/abs/2405.14093
28. Ma, M. & Narayanan, S. (2026). *Intelligence Requires Grounding But Not Embodiment*. arXiv 2601.17588, submitted 24 January 2026. https://arxiv.org/abs/2601.17588
29. Brooks, R. A. (1990). *Elephants Don't Play Chess*. Robotics and Autonomous Systems 6(1-2): 3-15.
30. Moravec, H. (1988). *Mind Children: The Future of Robot and Human Intelligence*. Harvard University Press. https://www.ri.cmu.edu/publications/mind-children-the-future-of-robot-and-human-intelligence
31. Thompson, E. (2007). *Mind in Life: Biology, Phenomenology, and the Sciences of Mind*. Belknap Press of Harvard University Press.
32. Di Paolo, E. A., Buhrmann, T. & Barandiaran, X. E. (2017). *Sensorimotor Life: An Enactive Proposal*. Oxford University Press. https://academic.oup.com/book/5967
33. Gibson, J. J. (1979). *The Ecological Approach to Visual Perception*. Houghton Mifflin.
34. Lungarella, M., Metta, G., Pfeifer, R. & Sandini, G. (2003). *Developmental robotics: a survey*. Connection Science 15(4): 151-190. https://doi.org/10.1080/09540090310001655110
35. Cangelosi, A. & Schlesinger, M. (2015). *Developmental Robotics: From Babies to Robots*. MIT Press. https://mitpressbookstore.mit.edu/book/9780262028011
36. Clark, A. (1997). *Being There: Putting Brain, Body, and World Together Again*. MIT Press. https://mitpressbookstore.mit.edu/book/9780262531566
37. Pylyshyn, Z. W. (2001). *Seeing, acting, and knowing*. Commentary on O'Regan and Noë, Behavioral and Brain Sciences 24(5). https://discovery-pp.ucl.ac.uk/4257/1/4257.pdf
38. Aizawa, K. (2018). *Critical Note: So, What Again is 4E Cognition?* In Newen, De Bruin & Gallagher (eds), The Oxford Handbook of 4E Cognition, Oxford University Press: 117-126. https://academic.oup.com/edited-volume/28083
39. Wagenmakers, E.-J., Beek, T., Dijkhoff, L., Gronau, Q. F., et al. (2016). *Registered Replication Report: Strack, Martin, & Stepper (1988)*. Perspectives on Psychological Science 11(6): 917-928. https://doi.org/10.1177/1745691616674458
40. Coles, N. A., Larsen, J. T. & Lench, H. C. (2019). *A meta-analysis of the facial feedback literature: Effects of facial feedback on emotional experience are small and variable*. Psychological Bulletin 145(6): 610-651. https://doi.org/10.1037/bul0000194
41. Gronau, Q. F., van Erp, S., Heck, D. W., Cesario, J., Jonas, K. J. & Wagenmakers, E.-J. (2017). *A Bayesian model-averaged meta-analysis of the power pose effect with informed and default priors: the case of felt power*. Comprehensive Results in Social Psychology 2(1): 123-138. https://cris.maastrichtuniversity.nl/en/publications/a-bayesian-model-averaged-meta-analysis-of-the-power-pose-effect-
