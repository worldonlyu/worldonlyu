# Embodied Cognition and the Foundations of Embodied AI

> Embodied cognition is the family of views holding that minds are shaped in a non-trivial way by having a body that acts in an environment. This chapter traces the position from Brooks's behaviour-based robots and Harnad's symbol grounding problem, through enactivism, sensorimotor contingency theory, grounded cognition, morphological computation and developmental robotics, to the predictive-processing synthesis that now dominates. It then sets out the critiques: that embodied cognition explains little in experimental psychology, that several flagship effects failed to replicate, and that large language models do surprisingly well with no body at all. That last point has reopened the oldest question in the field, whether meaning needs a body or only grounding, and a sharper one beside it, whether consciousness needs a living body. For a project on mind emulation the lesson is that a brain is not the whole of the system a mind runs on, and that whether a non-living substrate can be conscious is unresolved.

## Why this matters for the project

This dossier asks whether a mind can be preserved, emulated or moved to another substrate. Every position in this chapter is, in effect, a claim about how much of a mind lives outside the neurons, which makes embodied cognition the first hard constraint on that question.

Start with the naive picture: record a brain's wiring, run it on a computer, and the mind resumes. Sensorimotor contingency theory says that what seeing is like consists in mastery of the laws relating movement to sensory change [O'Regan & Noë, 2001](https://doi.org/10.1017/S0140525X01000115), and those laws belong to a particular body in a particular world. Enactivism ties meaning itself to the self-maintaining organisation of a living system [Varela et al., 1991](https://mitpress.mit.edu/9780262529365/the-embodied-mind/). Work on morphology shows that bodies do control-relevant work the nervous system never had to learn [Pfeifer & Bongard, 2006](https://doi.org/10.7551/mitpress/3585.001.0001), and developmental robotics shows that skills are acquired through a history of interaction tied to one body [Oudeyer et al., 2007](https://doi.org/10.1109/TEVC.2006.890271). On any of these views, an emulation run without a body, or in a very different one, would at best be a mind in a profoundly altered state and at worst not a mind. Seth's biological naturalism is sharper still: if consciousness depends on properties of living systems, a simulated brain need not be conscious at all, whatever body it drives [Seth, 2025](https://doi.org/10.1017/S0140525X25000032). Practitioners concede part of this; the 2025 State of Brain Emulation Report discusses embodiment as part of the emulation problem [Zanichelli et al., 2025](https://arxiv.org/abs/2510.15745), and [chapter 06](06-whole-brain-emulation-and-connectomics.md) takes that up.

The same literature supplies the hopeful side. The plasticity evidence O'Regan and Noë rely on, sensory substitution and adaptation, suggests sensorimotor mastery can be re-learned on a new body. The extended-mind thesis implies that a mind's boundary is already substrate-flexible [Clark & Chalmers, 1998](https://doi.org/10.1093/analys/58.1.7). Predictive processing says what matters is a generative model of body-world coupling, which a virtual body could in principle supply [Parr et al., 2022](https://direct.mit.edu/books/oa-monograph/5299/Active-InferenceThe-Free-Energy-Principle-in-Mind). And one live position holds that bodies are one route to grounding, not the only one [Mollo & Millière, 2023](https://arxiv.org/abs/2304.01481).

| Thesis | If true, an emulation needs | Status |
|---|---|---|
| Sensorimotor contingencies constitute perception | A body with matching movement-to-sensation laws, or long re-learning | Plasticity documented; constitutive claim contested |
| Sense-making requires living autonomy | Self-maintaining, norm-generating organisation | Philosophically developed; no agreed test |
| Morphology does control work | A faithful body model, not only a brain model | Well supported for control |
| Consciousness requires life | A living substrate, or no experience | Argued in 2025; contested |
| Grounding, not embodiment, suffices | Causal contact with the world by any route | Argued for LLMs; unmeasured |

Net assessment: brain-only emulation looks insufficient; "brain plus an adequately rich physical or virtual body plus interoceptive and homeostatic loops" is the minimum serious proposal; and whether any non-living substrate suffices for consciousness is open. For anyone hoping an animal's mind might one day be recovered from its preserved brain, the honest reading is that the brain is necessary but, on current theory, probably not sufficient. The body that trained it is part of what would have to be reconstructed.

## Key ideas

**Subsumption architecture.** Brooks's control scheme for the MIT robots Allen, Herbert and Genghis: independent layers of behaviour, each wired from sensors to actuators, run in parallel, and higher layers can suppress or "subsume" lower ones. There is no central world model or planner. Built incrementally and forced to interface with the world through perception and action, "reliance on representation disappears" [Brooks, 1991](https://people.csail.mit.edu/brooks/papers/representation.pdf).

**Moravec's paradox.** Tasks hard for humans (chess, algebra) proved easy for computers, while things a toddler does effortlessly (walking, picking up a cup) proved very hard. Moravec's Mind Children (1988) attributes this to the depth of sensorimotor evolution, on the order of a billion years of tuning.

**Symbol grounding problem.** How can the symbols of a formal system have meaning intrinsic to the system rather than parasitic on an external interpreter? A system whose symbols are defined only by other symbols is like someone learning Chinese from a Chinese-Chinese dictionary, so some symbols must be grounded bottom-up in sensorimotor (iconic and categorical) representations [Harnad, 1990](https://eprints.soton.ac.uk/250382/).

**Enactivism and sense-making.** Cognition is brought forth by a living organism's self-maintaining interaction with its environment, not by recovering a pre-given world [Varela et al., 1991](https://mitpress.mit.edu/9780262529365/the-embodied-mind/). Sense-making is an autonomous system's capacity to evaluate its coupling with the world against its own viability norms: the minimal form of meaning. Thompson's Mind in Life (2007) and Di Paolo and colleagues' Sensorimotor Life (2017) develop the theory.

**Sensorimotor contingencies and affordances.** Sensorimotor contingencies are the lawful ways sensory input changes as a function of the agent's movements; perceptual experience is the exercise of implicit mastery of these laws, not the having of an internal picture [O'Regan & Noë, 2001](https://doi.org/10.1017/S0140525X01000115). Gibson's affordances (1979) are the environment-side complement: possibilities for action a setting offers an animal relative to its body, held to be perceived directly.

**Grounded cognition.** The mainstream psychological version: conceptual knowledge is grounded in modal simulations, partial re-enactments of perceptual, motor and introspective states, plus bodily states and situated action, rather than in amodal symbols [Barsalou, 2008](https://doi.org/10.1146/annurev.psych.59.103006.093639). It keeps representations.

**Extended mind, parity principle and 4E.** If an external resource plays a role that, done in the head, we would count as cognitive, it is part of the cognitive process; a suitably coupled notebook is part of the mind [Clark & Chalmers, 1998](https://doi.org/10.1093/analys/58.1.7). "4E" (embodied, embedded, enacted, extended) is the umbrella label; the four differ on whether body and world merely influence, or partly constitute, cognition [Newen et al., 2018](https://doi.org/10.1093/oxfordhb/9780198735410.001.0001).

**Morphological computation.** A body's shape, materials and dynamics perform functions that would otherwise fall to neural control: passive-dynamic walkers, compliant hands, "cheap design" [Pfeifer & Bongard, 2006](https://doi.org/10.7551/mitpress/3585.001.0001). Müller and Hoffmann analysed four canonical cases and concluded that morphology usually facilitates control or perception, and that genuine computation by the body, as in physical reservoir computing, is rare [Müller & Hoffmann, 2017](https://doi.org/10.1162/ARTL_a_00219).

**Predictive processing and active inference.** The brain is a hierarchical generative model that continuously predicts sensory input and updates on prediction error; action is another way of reducing error, by selecting the next input [Clark, 2016](https://doi.org/10.1093/acprof:oso/9780190217013.001.0001). The free-energy principle formalises this: organisms minimise variational free energy, a bound on surprise, through perception and action under a generative model of how their actions affect their sensations [Parr et al., 2022](https://direct.mit.edu/books/oa-monograph/5299/Active-InferenceThe-Free-Energy-Principle-in-Mind).

**Intrinsic motivation and learning progress.** An agent rewarded for improvement in its own prediction ability selects activities of intermediate difficulty, where learning progress peaks, and developmental stages emerge without being scripted [Oudeyer et al., 2007](https://doi.org/10.1109/TEVC.2006.890271).

## State of the field (as of 2026-10-09)

### Origins

In AI the position crystallised in the late 1980s as a reaction against symbolic AI, which treated intelligence as manipulation of an internal world model. Brooks's robots and his 1991 paper made the engineering case [Brooks, 1991](https://people.csail.mit.edu/brooks/papers/representation.pdf); the companion essay "Elephants Don't Play Chess" (Robotics and Autonomous Systems 6, 1990) made it polemically. Harnad supplied the semantic argument [Harnad, 1990](https://eprints.soton.ac.uk/250382/). Hubert Dreyfus supplied the philosophical backdrop, arguing from Heidegger and Merleau-Ponty that skilled coping does not work by applying rules to represented facts, which is why symbolic AI kept hitting the frame problem; in 2007 he judged even Brooks's work not Heideggerian enough [Dreyfus, 2007](https://doi.org/10.1080/09515080701239510).

### Cognitive science and robotics

The parallel movement in cognitive science has several strands, now grouped as 4E cognition [Newen et al., 2018](https://doi.org/10.1093/oxfordhb/9780198735410.001.0001): enactivism [Varela et al., 1991](https://mitpress.mit.edu/9780262529365/the-embodied-mind/), sensorimotor contingency theory, offered as an explanation of change blindness, sensory substitution and colour perception without an internal picture [O'Regan & Noë, 2001](https://doi.org/10.1017/S0140525X01000115), grounded cognition [Barsalou, 2008](https://doi.org/10.1146/annurev.psych.59.103006.093639) and the extended mind [Clark & Chalmers, 1998](https://doi.org/10.1093/analys/58.1.7), with Clark's Being There (1997) connecting the philosophy to the robotics. Robotics gave the ideas engineering form, first as design principles argued from built systems [Pfeifer & Bongard, 2006](https://doi.org/10.7551/mitpress/3585.001.0001) and then with a corrective taxonomy [Müller & Hoffmann, 2017](https://doi.org/10.1162/ARTL_a_00219). Developmental robotics (Lungarella et al. 2003; Cangelosi and Schlesinger's textbook, MIT Press 2015) models how skills, concepts and language emerge through staged interaction, with Intelligent Adaptive Curiosity as its key algorithmic result [Oudeyer et al., 2007](https://doi.org/10.1109/TEVC.2006.890271).

### The synthesis

The most influential recent synthesis is predictive processing and active inference [Clark, 2016](https://doi.org/10.1093/acprof:oso/9780190217013.001.0001); the open-access textbook presents perception, action, learning and planning as variational inference under a generative model [Parr et al., 2022](https://direct.mit.edu/books/oa-monograph/5299/Active-InferenceThe-Free-Energy-Principle-in-Mind). Because the framework keeps internal models, it sits between classical cognitivism and radical enactivism, and both camps claim it.

### The LLM era

Large language models revived the grounding question. Bender and Koller argued that a system trained only on linguistic form has "a priori no way to learn meaning", understood as the relation between form and communicative intent [Bender & Koller, 2020](https://aclanthology.org/2020.acl-main.463). Mahowald and colleagues distinguished formal linguistic competence, where LLMs excel, from functional competence (reasoning, world knowledge), where they remain uneven [Mahowald et al., 2024](https://web.mit.edu/bcs/nklab/media/pdfs/Mahowald.TICs2024.pdf). Pezzulo and colleagues argued that living agents' generative models are tested through action and so are grounded in a way passively trained models are not [Pezzulo et al., 2024](https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613%2823%2900260-7). Harnad accepts that LLMs do not understand but asks how they do so well, suggesting that language at scale carries constraints that act as indirect grounding [Harnad, 2024](https://arxiv.org/abs/2402.02243). Against these, Mollo and Millière argue that teleosemantic grounding is achievable by LLMs and that multimodality and embodiment are "neither necessary nor sufficient" [Mollo & Millière, 2023](https://arxiv.org/abs/2304.01481).

Roboticists have turned the embodiment hypothesis into a benchmark. The embodied Turing test asks AI "animal models" to match living animals in sensorimotor competence, shifting attention from language and games to abilities shared across species [Zador et al., 2023](https://doi.org/10.1038/s41467-023-37180-x). A cat crossing a cluttered room in the dark is a fair example of the standard. Brooks argues that humanoids trained from video lack the touch and force sensing on which dexterity depends [Brooks, 2025](https://rodneybrooks.com/why-todays-humanoids-wont-learn-dexterity/); [chapter 02](02-embodied-ai-state-of-the-art.md) covers the systems he criticises. Fei-Fei Li's November 2025 essay argues that LLMs lack grounding and that physically consistent world models are needed to connect perception to action, an industry endorsement of grounding, though not of biological embodiment [Li, 2025](https://x.com/drfeifei/status/1987891210699379091).

### Consciousness

Whether consciousness, as opposed to intelligence, needs a body is sharper still. Seth's 2025 Behavioral and Brain Sciences target article defends biological naturalism, the view that consciousness depends on properties of living systems (not necessarily carbon-based), against computational functionalism [Seth, 2025](https://doi.org/10.1017/S0140525X25000032). The journal's open peer commentary on it was not checked for this chapter. [Chapter 04](04-machine-consciousness.md) takes this up.

## Debates and critiques

**Representation.** Brooks, enactivists and sensorimotor theorists hold that intelligence, or at least perception, does not require internal representations; Pylyshyn (in the BBS commentary on O'Regan and Noë), Clark and the active-inference school hold that generative models are indispensable.

**Strong versus weak embodiment, and replication.** Goldinger and colleagues argued that embodied cognition offers little purchase on classic phenomena of experimental psychology and generates few testable predictions [Goldinger et al., 2016](https://pmc.ncbi.nlm.nih.gov/articles/PMC4975666). Wołoszyn and Hohol replied that radical anti-representational embodiment is indeed a dead end but that the paper mischaracterised mainstream grounded cognition [Wołoszyn & Hohol, 2017](https://doi.org/10.3389/fpsyg.2017.00845). Separately, flagship "embodiment effects" fared badly in the replication crisis. The power-pose effect is the best-known casualty; the meta-analytic estimates of any surviving felt-power effect are disputed and were not verified for this chapter, so no numbers are given. The 2016 Registered Replication Report of the pen-in-mouth facial-feedback effect found a mean difference of 0.03 on a 10-point scale (95% CI -0.11 to +0.16), although a 2019 meta-analysis of 138 studies found a small but reliable facial-feedback effect. The general thesis that bodies matter for cognition is far better supported than many specific priming-style demonstrations.

**Morphological computation.** Does the body offload computation from the brain, as Pfeifer and Bongard and much soft robotics suggest, or mostly facilitate control and perception [Müller & Hoffmann, 2017](https://doi.org/10.1162/ARTL_a_00219)? Critics of the latter say its definition of computation is too restrictive.

**LLM grounding.** The positions are summarised below. A 2026 preprint said to argue that intelligence requires grounding but not embodiment (arXiv 2601.17588) was removed from the table on review because neither its title nor its authors could be confirmed; it can be restored once someone opens the arXiv page.

| Source | Claim | Is a body required? |
|---|---|---|
| Bender & Koller 2020 | Form alone cannot yield meaning | Grounding needed; body unspecified |
| Harnad 2024 | LLMs do not understand; language at scale gives indirect constraints | Yes, for understanding |
| Pezzulo et al. 2024 | Meaning comes from testing a generative model through action | Action-based testing required |
| Mahowald et al. 2024 | Formal competence strong, functional competence uneven | Agnostic |
| Mollo & Millière 2023 | Teleosemantic grounding is achievable by LLMs | "Neither necessary nor sufficient" |

**Enactivism confronting LLMs.** Classical enactivism ties sense-making to the adaptive autonomy of living systems, which implies that LLMs cannot make sense. Froese argues that enactivists face a dilemma and proposes that LLM competence is a non-biological sense-making grounded in technologically mediated embodiment [Froese, 2025](https://link.springer.com/article/10.1007/s11097-025-10132-0).

**The embodiment hypothesis in robotics.** Zador and colleagues and Brooks argue that animal-level sensorimotor competence, including touch and force sensing, is the missing foundation [Zador et al., 2023](https://doi.org/10.1038/s41467-023-37180-x); [Brooks, 2025](https://rodneybrooks.com/why-todays-humanoids-wont-learn-dexterity/). The vision-language-action programme [Ma et al., 2024](https://arxiv.org/abs/2405.14093) and Li's world-model agenda bet instead on scaling multimodal data and simulation.

**Consciousness and life.** Seth holds that neither disembodied computation nor a simulated brain need be conscious; computational functionalists reply that the relevant properties are organisational and substrate-independent [Seth, 2025](https://doi.org/10.1017/S0140525X25000032). Contested, not settled.

**Extended mind.** Aizawa's critical note in the Oxford Handbook argues that causal coupling to external resources does not make them constitutive of cognition, the coupling-constitution objection [Newen et al., 2018](https://doi.org/10.1093/oxfordhb/9780198735410.001.0001).

## Open questions

1. Which cognitive capacities are constitutively, not merely causally, dependent on bodily morphology, and can this be tested rather than argued? Müller and Hoffmann's taxonomy has few quantitative applications so far.
2. Is grounding (causal-informational contact with the world plus a selection history) sufficient for meaning, or is action-based testing of a generative model also required? Can fine-tuned or tool-using LLMs meet either criterion measurably?
3. Does sensorimotor mastery transfer across bodies? Sensory-substitution and prosthesis studies show plasticity, but there is no quantitative account of how much of a perceptual repertoire survives a radical change of sensors and effectors, which is what an emulation in a new body would face.
4. Can the embodied Turing test be turned into benchmarks with agreed metrics, and how far are current systems from animal-level performance?
5. What is the minimal body, physical or simulated, that supports open-ended intrinsically motivated development, and must interoception or homeostatic regulation be part of it?
6. Is consciousness tied to life or to organisation? No proposed test discriminates these for artificial systems.
7. Why do LLMs perform as well as they do without sensorimotor grounding? Indirect grounding and the formal/functional dissociation are hypotheses, not explanations with predictive power.
8. How much of the embodied-cognition literature survives rigorous replication? The field needs a preregistered meta-analytic audit separating robust phenomena from discredited priming-style effects.

## Where to start

1. Free, one evening: [Brooks, 1991](https://people.csail.mit.edu/brooks/papers/representation.pdf) and [Harnad, 1990](https://eprints.soton.ac.uk/250382/). Together they define the problem space in under 40 pages.
2. Free, the sceptic's counterweight: [Goldinger et al., 2016](https://pmc.ncbi.nlm.nih.gov/articles/PMC4975666) and the reply by [Wołoszyn & Hohol, 2017](https://doi.org/10.3389/fpsyg.2017.00845). Read these before any enthusiast's book.
3. Free textbook: [Parr et al., 2022](https://direct.mit.edu/books/oa-monograph/5299/Active-InferenceThe-Free-Energy-Principle-in-Mind). Chapters 1 to 4 give the conceptual story; later chapters give equations you can implement, a natural first coding project.
4. Inexpensive paperback: [Pfeifer & Bongard, 2006](https://doi.org/10.7551/mitpress/3585.001.0001), the most readable engineering introduction, with its design principles stated explicitly. Pair it with [Müller & Hoffmann, 2017](https://doi.org/10.1162/ARTL_a_00219).
5. Philosophical core: [Clark, 2016](https://doi.org/10.1093/acprof:oso/9780190217013.001.0001) for predictive processing, then [Varela et al., 1991](https://mitpress.mit.edu/9780262529365/the-embodied-mind/) for enactivism, with [Newen et al., 2018](https://doi.org/10.1093/oxfordhb/9780198735410.001.0001) as the reference work.
6. The LLM-era debate: [Bender & Koller, 2020](https://aclanthology.org/2020.acl-main.463), [Pezzulo et al., 2024](https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613%2823%2900260-7) and [Harnad, 2024](https://arxiv.org/abs/2402.02243) on one side, [Mollo & Millière, 2023](https://arxiv.org/abs/2304.01481) on the other; then [chapter 02](02-embodied-ai-state-of-the-art.md) and [Ma et al., 2024](https://arxiv.org/abs/2405.14093) for models you can run.

## References

1. Brooks, R. A. (1991). *Intelligence without representation*. Artificial Intelligence. https://people.csail.mit.edu/brooks/papers/representation.pdf
2. Harnad, S. (1990). *The Symbol Grounding Problem*. Physica D. https://eprints.soton.ac.uk/250382/
3. Dreyfus, H. L. (2007). *Why Heideggerian AI Failed and How Fixing It Would Require Making It More Heideggerian*. Philosophical Psychology. https://doi.org/10.1080/09515080701239510
4. Varela, F. J., Thompson, E. & Rosch, E. (1991). *The Embodied Mind: Cognitive Science and Human Experience*. MIT Press. https://mitpress.mit.edu/9780262529365/the-embodied-mind/
5. O'Regan, J. K. & Noë, A. (2001). *A sensorimotor account of vision and visual consciousness*. Behavioral and Brain Sciences 24(5): 939-973. https://doi.org/10.1017/S0140525X01000115
6. Barsalou, L. W. (2008). *Grounded Cognition*. Annual Review of Psychology. https://doi.org/10.1146/annurev.psych.59.103006.093639
7. Clark, A. & Chalmers, D. (1998). *The Extended Mind*. Analysis. https://doi.org/10.1093/analys/58.1.7
8. Newen, A., De Bruin, L. & Gallagher, S. (eds) (2018). *The Oxford Handbook of 4E Cognition*. Oxford University Press. https://doi.org/10.1093/oxfordhb/9780198735410.001.0001
9. Pfeifer, R. & Bongard, J. (2006/2007). *How the Body Shapes the Way We Think: A New View of Intelligence*. MIT Press. https://doi.org/10.7551/mitpress/3585.001.0001
10. Müller, V. C. & Hoffmann, M. (2017). *What Is Morphological Computation? On How the Body Contributes to Cognition and Control*. Artificial Life. https://doi.org/10.1162/ARTL_a_00219
11. Oudeyer, P.-Y., Kaplan, F. & Hafner, V. V. (2007). *Intrinsic Motivation Systems for Autonomous Mental Development*. IEEE Transactions on Evolutionary Computation. https://doi.org/10.1109/TEVC.2006.890271
12. Clark, A. (2016). *Surfing Uncertainty: Prediction, Action, and the Embodied Mind*. Oxford University Press. https://doi.org/10.1093/acprof:oso/9780190217013.001.0001
13. Parr, T., Pezzulo, G. & Friston, K. J. (2022). *Active Inference: The Free Energy Principle in Mind, Brain, and Behavior*. MIT Press, open access. https://direct.mit.edu/books/oa-monograph/5299/Active-InferenceThe-Free-Energy-Principle-in-Mind
14. Goldinger, S. D., Papesh, M. H., Barnhart, A. S., Hansen, W. A. & Hout, M. C. (2016). *The poverty of embodied cognition*. Psychonomic Bulletin & Review. https://pmc.ncbi.nlm.nih.gov/articles/PMC4975666
15. Wołoszyn, K. & Hohol, M. (2017). *Commentary: The poverty of embodied cognition*. Frontiers in Psychology. https://doi.org/10.3389/fpsyg.2017.00845
16. Bender, E. M. & Koller, A. (2020). *Climbing towards NLU: On Meaning, Form, and Understanding in the Age of Data*. Proceedings of ACL 2020. https://aclanthology.org/2020.acl-main.463
17. Mahowald, K., Ivanova, A. A., Blank, I. A., Kanwisher, N., Tenenbaum, J. B. & Fedorenko, E. (2024). *Dissociating language and thought in large language models*. Trends in Cognitive Sciences 28(6): 517-540. https://web.mit.edu/bcs/nklab/media/pdfs/Mahowald.TICs2024.pdf
18. Pezzulo, G., Parr, T., Cisek, P., Clark, A. & Friston, K. (2024). *Generating meaning: active inference and the scope and limits of passive AI*. Trends in Cognitive Sciences 28(2). https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613%2823%2900260-7
19. Harnad, S. (2024). *Language Writ Large: LLMs, ChatGPT, Meaning, and Understanding*. arXiv 2402.02243; journal version in Frontiers in Artificial Intelligence, article 1490698 (volume and year unconfirmed). https://arxiv.org/abs/2402.02243
20. Mollo, D. C. & Millière, R. (2023). *The Vector Grounding Problem*. arXiv 2304.01481; journal version in Philosophy and the Mind Sciences (year unconfirmed). https://arxiv.org/abs/2304.01481
21. Zador, A., et al. (2023). *Catalyzing next-generation Artificial Intelligence through NeuroAI*. Nature Communications. https://doi.org/10.1038/s41467-023-37180-x
22. Seth, A. K. (2025). *Conscious artificial intelligence and biological naturalism*. Behavioral and Brain Sciences, online first. https://doi.org/10.1017/S0140525X25000032
23. Froese, T. (2025). *Sense-making reconsidered*. Phenomenology and the Cognitive Sciences, online first. https://link.springer.com/article/10.1007/s11097-025-10132-0
24. Brooks, R. (2025). *Why Today's Humanoids Won't Learn Dexterity*. rodneybrooks.com, September 2025. https://rodneybrooks.com/why-todays-humanoids-wont-learn-dexterity/
25. Li, F.-F. (2025). *From Words to Worlds: Spatial Intelligence is AI's Next Frontier*. Essay, 10 November 2025. The URL given is the author's post announcing the essay, not the essay itself; the essay's own page was not reached in this session. https://x.com/drfeifei/status/1987891210699379091
26. Zanichelli, N., et al. (2025). *State of Brain Emulation Report 2025*. arXiv 2510.15745 (full author list unconfirmed). https://arxiv.org/abs/2510.15745
27. Ma, Y., et al. (2024). *A Survey on Vision-Language-Action Models for Embodied AI*. arXiv 2405.14093. https://arxiv.org/abs/2405.14093

*Verification status.* No reference above was checked against a live publisher page in the session that produced this chapter; every scholarly host tried was blocked. Entries 1, 2, 11, 13 to 14, 16 to 20, 22 to 25 and 27 carry URLs or identifiers from the research material behind the chapter. Entries 3 to 10, 12, 15 and 21 are canonical works whose DOI or publisher URLs were supplied from memory. Entry 26 is a recent preprint whose author list and contents are unconfirmed and is relied on only lightly. Eight works are cited by name and year in the body only and have no entry above: Brooks, "Elephants Don't Play Chess" (1990); Moravec, Mind Children (1988); Thompson, Mind in Life (2007); Di Paolo and colleagues, Sensorimotor Life (2017); Lungarella et al. (2003); Cangelosi and Schlesinger (2015); Clark, Being There (1997); Gibson (1979). The figures given in the Debates section for the 2016 facial-feedback replication report and the 2019 meta-analysis also have no source entry yet. A review pass on 2026-10-09 could reach no external host either, so nothing was checked then. Open each link and correct what is wrong before treating this chapter as settled.
