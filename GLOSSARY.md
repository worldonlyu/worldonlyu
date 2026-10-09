# Glossary

Definitions of the terms used across the chapters of this notebook, in plain language. Each entry ends with the chapter or chapters in which the term does its work, so that a definition can always be followed back to its context and its sources. Where several chapters introduced the same idea under slightly different names (for example, the three chapters that each define "connectome"), the entries have been merged and every chapter is listed.

Entries are alphabetical, with the one term that begins with a digit first. Dates and "current state" claims in the definitions are accurate to October 2026 and will age; the chapters carry the references.

## 0-9

**4E cognition**: An umbrella label for embodied, embedded, enacted and extended approaches to cognition (Newen, De Bruin and Gallagher, Oxford Handbook of 4E Cognition, 2018). The four approaches differ on whether body and world merely influence cognition or partly constitute it. See: docs/01-embodied-cognition-foundations.md

## A

**Action chunking**: Predicting a sequence of future actions (for example 50 steps in pi0) in a single forward pass rather than one action at a time, often using a separate "action expert", a set of transformer weights dedicated to state and action tokens. It improves smoothness and reduces compounding error in imitation learning. See: docs/02-embodied-ai-state-of-the-art.md

**Active inference and the free-energy principle**: Friston's formalisation of predictive processing. Organisms are said to minimise variational free energy, a bound on surprise, through both perception and action; Parr, Pezzulo and Friston (2022) give the full treatment. See: docs/01-embodied-cognition-foundations.md

**Adversarial collaboration**: A preregistered study in which proponents of rival theories agree in advance on divergent predictions, methods and what would count as disconfirmation, and a theory-neutral team runs the experiment. The Templeton World Charity Foundation's Accelerating Research on Consciousness programme funded several; Cogitate (IIT versus GNWT) was the first to publish. See: docs/03-science-of-consciousness.md

**Affordances**: Gibson's (1979) term for the possibilities for action that an environment offers an animal relative to that animal's body and abilities: a surface affords walking, a handle affords grasping. Gibson held that affordances are perceived directly. See: docs/01-embodied-cognition-foundations.md

**AI Consciousness Test (ACT)**: Schneider's proposal to probe an AI that has been kept "boxed", with no exposure to human talk about consciousness, for a spontaneous grasp of experience-related concepts. See: docs/04-machine-consciousness.md

**AI segmentation and proofreading**: Convolutional networks (for example Google's flood-filling networks and the Seung lab's pipelines) trace neurons through electron microscopy volumes, and humans then correct merge and split errors. Proofreading dominates the cost of a connectome; third-party summaries of E11 Bio's PRISM announcement put it at about 95 percent of the cost, a figure chapter 06 could not confirm. See: docs/06-whole-brain-emulation-and-connectomics.md

**Aldehyde-stabilised cryopreservation (ASC)**: Perfusing glutaraldehyde fixative first, to crosslink proteins and halt decay within minutes, then loading cryoprotectant and storing the vitrified brain near -135 C (McIntyre and Fahy 2015). It preserves ultrastructure across a whole brain but makes biological revival impossible; the aim is information preservation for future scanning. See: docs/07-brain-preservation.md

**Animalism**: Olson's view that each of us is a human animal and persists by biological continuity. A psychological duplicate on another substrate is a different object, so on this view uploading never preserves identity; the view extends naturally to non-human animals. See: docs/08-personal-identity-and-the-ethics-of-uploading.md

**Anthropomorphism bias**: The risk that caregivers project their own emotions onto animals in owner-report studies. Both published cat grief studies rely on surveys, and in both the owner's attachment predicts the behaviours reported, so part of the signal may belong to the owner rather than the cat. See: docs/05-animal-consciousness-and-the-feline-mind.md

**Aortic (arterial) thromboembolism**: A clot formed in the enlarged left atrium of a cat with hypertrophic cardiomyopathy that lodges in the aorta, typically causing sudden hind-limb paralysis and pain. With congestive heart failure and sudden death, it is one of the three catastrophic presentations of silent HCM. See: docs/05-animal-consciousness-and-the-feline-mind.md

**Attention Schema Theory (AST)**: Graziano's proposal that the brain builds a simplified internal model of its own attention, analogous to the body schema. The content of this model is what leads the system to believe and report that it has subjective awareness. See: docs/03-science-of-consciousness.md

**Audience problem**: Udell and Schwitzgebel's objection that behaviour-based tests for machine consciousness cannot convince anyone who thinks architecture matters, so they persuade only those already inclined toward functionalism. See: docs/04-machine-consciousness.md

**Autopoiesis**: Self-production: a living system continuously makes and maintains the components and boundary that constitute it as a system. Enactivism treats autopoietic autonomy as the root of sense-making, and Seth's biological naturalism counts it among the non-computational prerequisites for consciousness. See: docs/01-embodied-cognition-foundations.md, docs/04-machine-consciousness.md

## B

**Behaviour cloning (imitation learning)**: Supervised learning of a control policy from demonstration trajectories, as in ACT, diffusion policy and VLA fine-tuning. It is cheap and effective within the training distribution but prone to compounding errors and shortcut learning outside it. See: docs/02-embodied-ai-state-of-the-art.md

**Biological naturalism**: The family of positions holding that consciousness is a causal product of specific biological processes, so computation alone does not suffice. Searle's version says a simulation of a brain, however accurate, need not be conscious, just as a simulation of digestion digests nothing; Seth's version ties consciousness to living systems with metabolic self-maintenance and predictive regulation of a body, while allowing that life need not be carbon-based. On either version an emulation on conventional hardware might not be conscious. See: docs/01-embodied-cognition-foundations.md, docs/04-machine-consciousness.md, docs/08-personal-identity-and-the-ethics-of-uploading.md

**Biophysically detailed (multi-compartment) model**: A neuron represented as hundreds of electrically coupled compartments with Hodgkin-Huxley-type ion channels fitted to its morphology and electrophysiology, as in the Blue Brain microcircuit and the Allen Institute V1 core model. It costs roughly 1,000 to 10,000 times the compute per neuron of a point model. See: docs/09-recording-simulation-and-hardware.md

## C

**Channels versus neurons**: A brain-computer interface's electrode or channel count (about 1,000 for Neuralink N1, Precision Layer 7 and Paradromics Connexus) is not the number of neurons it reads; stable, well-isolated single units are typically fewer than channels. For scale, a human brain has about 86 billion neurons and a cat's about 250 million cortical neurons, perhaps 750 million in the whole brain. See: docs/09-recording-simulation-and-hardware.md

**Closest-continuer theory**: Nozick's proposal that you are whichever later candidate is most closely continuous with you, provided it is close enough and has no equal rival. It makes identity depend on what else happens to exist, which many find unacceptable. See: docs/08-personal-identity-and-the-ethics-of-uploading.md

**Cognitive motor dissociation (CMD)**: Also called covert awareness: the condition in which a behaviourally unresponsive patient shows command-following on fMRI or EEG. A 2024 NEJM study found it in about one in four such patients. See: docs/03-science-of-consciousness.md

**Computational functionalism**: The working hypothesis that performing the right computations is sufficient for consciousness regardless of substrate, so a faithful emulation of a brain would be conscious. Functionalist theories (GNWT, HOT, AST, most predictive processing) accept it, and it underlies the indicator-properties approach to assessing AI; IIT and biological naturalism deny it, holding that physical causal structure or being alive is what matters. See: docs/03-science-of-consciousness.md, docs/04-machine-consciousness.md

**Connectome**: A map of every neuron and the synaptic connections between them in a tissue volume or a whole nervous system, usually reconstructed from nanometre-resolution electron microscopy. Whole-brain connectomes exist for C. elegans (302 neurons) and for adult Drosophila (FlyWire: about 140,000 neurons and over 50 million synapses), and a cubic millimetre of mouse cortex was mapped by 2025; cat and human brains are orders of magnitude beyond current capacity. A connectome records anatomy and synapse counts (plus predicted neurotransmitters), not the strength, sign or dynamics of each connection. See: docs/06-whole-brain-emulation-and-connectomics.md, docs/07-brain-preservation.md, docs/09-recording-simulation-and-hardware.md

**Connectome variability**: The finding that genetically identical C. elegans adults differ in synaptic connectivity and that wiring changes across development. It implies that any connectome is a sample from one individual, not a species blueprint. See: docs/06-whole-brain-emulation-and-connectomics.md

**Conscious Turing Machine (CTM)**: The Blums' formal model that combines a Turing machine with a global workspace, a multimodal internal language called Brainish, and predictive dynamics. See: docs/04-machine-consciousness.md

**Consciousness prior**: Bengio's inductive bias for machine learning: a low-dimensional "conscious state" made of a few attended variables that is broadcast and constrains downstream processing, intended to improve abstraction and reasoning. See: docs/04-machine-consciousness.md

**Controlled hallucination and the beast machine**: Seth's account of perception and selfhood. Perception is Bayesian "controlled hallucination", top-down prediction constrained by sensory error; selfhood is grounded in interoceptive prediction aimed at regulating a living body (the "beast machine"). Seth reframes the hard problem as the "real problem" of explaining phenomenological properties mechanistically, and is sceptical that computation alone yields consciousness. See: docs/03-science-of-consciousness.md

**Cortical neuron count (isotropic fractionator)**: Herculano-Houzel's method of dissolving brain tissue into a suspension of nuclei and counting the neuronal ones. It gives about 250 million cortical neurons for cats, 530 million for dogs and 16 billion for humans, and shows that brain mass is a poor proxy for neuron number (compare a bear with a cat). See: docs/05-animal-consciousness-and-the-feline-mind.md

**Cross-embodiment training (positive transfer)**: Training one policy on data from many different robot bodies (Open X-Embodiment used 22 robots) so that experience on one platform improves performance on others. Positive transfer is measured as the gain over a policy trained only on the target robot's own data. See: docs/02-embodied-ai-state-of-the-art.md

## D

**Data bottleneck**: The observation that for low-fidelity emulation the limiting resource is not compute but measured data: the wiring, synaptic strengths, neuromodulatory state and plasticity rules that would have to be loaded into the simulation. None of these can yet be acquired at mammalian scale. See: docs/09-recording-simulation-and-hardware.md

**Destructive, gradual and nondestructive uploading**: Chalmers's taxonomy of uploading methods: scanning that destroys the brain, neuron-by-neuron replacement over time, and scanning that leaves the original intact. Gradual uploading is widely felt to be the safest for identity; Wiley and Koene argue this feeling has no logical basis. See: docs/08-personal-identity-and-the-ethics-of-uploading.md

**Disorders of consciousness**: Coma, vegetative state (also called unresponsive wakefulness syndrome) and minimally conscious state, all of which are behavioural diagnoses. Some patients given these diagnoses show covert awareness; see Cognitive motor dissociation. See: docs/03-science-of-consciousness.md

**Distributed real-world evaluation**: Ranking robot policies through double-blind pairwise comparisons run by many independent labs on a shared hardware platform (RoboArena on DROID). The aim is to escape the irreproducibility of single-lab success-rate tables. See: docs/02-embodied-ai-state-of-the-art.md

**Dual-system (System 1 / System 2) architecture**: A robot control design that pairs a slow vision-language reasoner that interprets scenes and plans (7 to 9 Hz in Helix; ER 1.5 in Gemini Robotics) with a fast visuomotor policy running at tens to hundreds of Hz that executes. Used by Helix, GR00T N1 and Gemini Robotics 1.5 and 2. See: docs/02-embodied-ai-state-of-the-art.md

## E

**Eight-criterion sentience framework**: The LSE review's checklist for animal sentience: nociceptors, integrative brain regions, nociceptor-to-brain connections, response to analgesia, motivational trade-offs, flexible self-protection, associative learning and valuing analgesia. Each criterion receives a confidence level; octopuses meet seven of the eight. See: docs/05-animal-consciousness-and-the-feline-mind.md

**Embodied Turing test**: Zador and colleagues' (2023) proposed benchmark asking AI "animal models" to match the sensorimotor competence of living animals. It shifts attention from language and games toward abilities shared across species. See: docs/01-embodied-cognition-foundations.md

**Emulation welfare and the consent problem**: Sandberg's point that emulations, first of animals, raise questions about pausing, copying, deleting and experimenting that no subject has consented to. Animals cannot consent at all, so only a guardian or best-interests standard is available. See: docs/08-personal-identity-and-the-ethics-of-uploading.md

**Enactivism (enaction)**: The view (Varela, Thompson and Rosch 1991; Thompson 2007; Di Paolo) that cognition is brought forth by a living organism's ongoing, self-maintaining interaction with its environment. Meaning arises from the organism's autonomy and norms, not from representing a pre-given world. See: docs/01-embodied-cognition-foundations.md

**Engram**: The physical trace of a memory. In rodent experiments it is a sparse ensemble of cells whose activity-dependent tagging and optogenetic reactivation can trigger recall; evidence suggests connectivity among engram cells can carry a memory even when synaptic potentiation is blocked, though the full code is unknown. See: docs/07-brain-preservation.md

**Episodic-like memory**: Retrieving what-where (and sometimes when) information from a single, incidentally encoded event. It is the behavioural stand-in for human episodic memory in animals that cannot report autonoetic experience; Takagi's bowl task shows it in cats after a 15-minute delay. See: docs/05-animal-consciousness-and-the-feline-mind.md

**Expansion microscopy with protein barcoding (PRISM)**: Physically swelling tissue so that light microscopes reach nanoscale effective resolution, combined with genetically encoded protein barcodes that give each neuron a unique molecular signature for self-correcting reconstruction. Pursued by E11 Bio as an alternative to electron microscopy. See: docs/06-whole-brain-emulation-and-connectomics.md

**Explosion of negative phenomenology (ENP)**: Metzinger's term for the risk that machines with a conscious self-model and autonomous goals could suffer, potentially on a vast scale, when their goals are frustrated. See: docs/04-machine-consciousness.md

**Extended mind (parity principle)**: Clark and Chalmers's (1998) thesis that mind can extend beyond skin and skull into tools and notations. The parity principle says that if an external resource plays a role that we would count as cognitive were it done in the head, then it is part of the cognitive process. See: docs/01-embodied-cognition-foundations.md

## F

**Fading qualia and organisational invariance**: Chalmers's argument that if neurons are replaced one by one with functional equivalents, consciousness cannot plausibly fade without the subject noticing. The conclusion, organisational invariance, is that functionally identical systems share conscious states regardless of substrate. See: docs/08-personal-identity-and-the-ethics-of-uploading.md

**Feline Grimace Scale (FGS)**: A validated acute-pain instrument for cats that scores five facial action units (ear position, orbital tightening, muzzle tension, whisker change, head position) from 0 to 2 each. A total above 0.39 of 1.0 indicates pain requiring analgesia. See: docs/05-animal-consciousness-and-the-feline-mind.md

**Fission (the copy or branching problem)**: If one person can be psychologically continuous with two later people, as in a split-brain transplant or a nondestructive scan, then identity, which is one-to-one, cannot track continuity. Any uploading method that could in principle be run twice faces this problem. See: docs/08-personal-identity-and-the-ethics-of-uploading.md

**Frame problem**: Symbolic AI's inability to know which facts matter in a given context. Dreyfus, arguing from Heidegger, treated it as a symptom of ignoring skilled coping. See: docs/01-embodied-cognition-foundations.md

**Functional connectomics**: Pairing an electron microscopy connectome with recordings of the same neurons' activity in the living animal. MICrONS did this with calcium imaging of about 75,000 neurons co-registered to more than 200,000 reconstructed cells. See: docs/06-whole-brain-emulation-and-connectomics.md

**Functional versus mechanistic compute estimates**: Mechanistic estimates count the operations needed to simulate the brain's physical processes (the Sandberg-Bostrom levels). Functional estimates (Carlsmith, AI Impacts) ask how many FLOP/s would match the brain's task performance, giving about 10^13 to 10^17 FLOP/s. They answer different questions and should not be compared directly. See: docs/09-recording-simulation-and-hardware.md

**Further-fact (Cartesian) view**: The view that personal identity consists in something over and above physical and psychological continuity, such as a soul or ego. Parfit argues against it; Chalmers keeps it as a live option because intuitions about uploading seem to presuppose it. See: docs/08-personal-identity-and-the-ethics-of-uploading.md

## G

**Gaming problem**: Birch's point that large language models trained on human descriptions of experience and tuned for human approval can reproduce every behavioural marker of sentience without the underlying capacity. This undermines behavioural evidence for AI sentience. See: docs/04-machine-consciousness.md

**GLIF point neuron**: Generalised leaky integrate-and-fire models fitted by the Allen Institute to recorded cells so that a point-neuron network (for example the GLIF version of the V1 model) matches a biophysical one. They are now trainable on GPUs in BMTK's 2026 DPointNet backend. See: docs/09-recording-simulation-and-hardware.md

**Global Neuronal Workspace Theory (GNWT) and ignition**: Dehaene, Changeux and Naccache's neural version of global workspace theory. Information becomes conscious when it triggers a sudden, self-sustaining "ignition" of a long-range frontoparietal network that broadcasts it to many specialised processors; the theory predicts a prefrontal role and ignition at both stimulus onset and offset. It was tested against IIT in the 2025 Cogitate adversarial collaboration, which challenged tenets of both. See: docs/03-science-of-consciousness.md

**Global workspace theory (GWT)**: Baars's theory that consciousness is the global broadcast of a small amount of selected information to many specialised modules. It inspired Dehaene's GNWT and his C1/C2 distinction, the Conscious Turing Machine and Bengio's consciousness prior. See: docs/04-machine-consciousness.md

**Griefbot (deathbot)**: A chatbot conditioned on a deceased person's or pet's texts, voice or photos to simulate conversation. It is a statistical generator with no continuity with the original; ethicists flag consent, prolonged grief and monetisation risks, and controlled evidence on grief outcomes is lacking. See: docs/07-brain-preservation.md

**Grounded cognition**: Barsalou's (2008) view that conceptual knowledge is grounded in modal simulations (partial re-enactments of perceptual, motor and introspective states), bodily states and situated action, rather than in amodal symbols. See: docs/01-embodied-cognition-foundations.md

## H

**Habituation-dishabituation paradigm**: Playing a series of similar stimuli until the animal stops responding, then presenting a test stimulus; renewed orienting shows that the animal discriminates the two. Saito used it to show that cats distinguish their own names, with ear and head movements as the readout. See: docs/05-animal-consciousness-and-the-feline-mind.md

**Hard problem of consciousness**: Chalmers's question of why and how physical processes give rise to subjective experience at all. It is distinct from the "easy" problems of explaining functions such as discrimination, report and attention. See: docs/03-science-of-consciousness.md

**High-density silicon probe (Neuropixels)**: CMOS probes with thousands of recording sites along one or more shanks, hundreds of which can be read out at once. Neuropixels 2.0 added multi-shank, miniaturised, chronically stable recording over weeks; it is the current workhorse for mesoscale mammalian recording. See: docs/09-recording-simulation-and-hardware.md

**Higher-order theories (HOT), including HOROR and perceptual reality monitoring**: Theories (Rosenthal, Lau, Brown) on which a first-order sensory state is conscious only when it is represented by a suitable higher-order state, for example a monitor that tags perceptual states as reliable. Higher-Order Representation of a Representation (HOROR) and Perceptual Reality Monitoring (PRM) are the two variants being tested against Recurrent Processing Theory in a Templeton adversarial collaboration led by Biyu He. Several of the indicator properties proposed for AI consciousness derive from these theories. See: docs/03-science-of-consciousness.md, docs/04-machine-consciousness.md

**Hypertrophic cardiomyopathy (HCM)**: Thickening of the left ventricular wall that impairs filling of the heart. It is the most common feline heart disease, present on echocardiography in about 15 percent of apparently healthy cats, usually without a murmur or symptoms. See: docs/05-animal-consciousness-and-the-feline-mind.md

## I

**IIT 4.0**: The 2023 formulation of Integrated Information Theory (Albantakis et al., PLOS Computational Biology) that restates the axioms as mathematical postulates, introduces a unique measure of intrinsic information and makes causal relations explicit. It is also the version that the 2023 to 2025 "pseudoscience" debate concerns. See: docs/03-science-of-consciousness.md

**Illusionism**: Frankish's (2016) position that phenomenal consciousness does not exist and that the task is to explain why it seems to. Like Dennett's multiple drafts model, it relocates what needs explaining from experience itself to our judgements about experience. See: docs/03-science-of-consciousness.md

**Indicator properties**: Computationally specified features derived from scientific theories of consciousness, such as recurrent processing, a global workspace, metacognitive monitoring, and agency with embodiment. A system's credence of being conscious should rise with the number it satisfies; no single indicator is treated as sufficient. See: docs/04-machine-consciousness.md

**Information-theoretic death**: The point at which the structures encoding memory and personality are so degraded that no technology, however advanced, could infer the original state. Cryonicists contrast it with legal or clinical death; critics note that nobody knows which structures those are, so the point cannot be measured. See: docs/07-brain-preservation.md

**Integrated Information Theory (IIT) and phi**: Tononi's theory that consciousness is identical to a system's irreducible intrinsic cause-effect structure. Its quantity is phi (integrated information) and its quality is the shape of that structure; the theory starts from five axioms about experience and derives postulates about the physical substrate. It implies that substrate matters, so a conventional digital computer running a program, including a digital simulation of a brain, may have little or no consciousness. See: docs/03-science-of-consciousness.md, docs/04-machine-consciousness.md

**Intrinsic motivation (learning progress)**: A developmental-robotics mechanism (Oudeyer, Kaplan and Hafner 2007) in which an agent is rewarded for improvement in its own prediction ability. This drives it toward tasks of intermediate difficulty and produces emergent developmental stages. See: docs/01-embodied-cognition-foundations.md

**Ischemia and no-reflow**: After circulation stops, cells exhaust ATP within minutes and begin to swell; within about an hour at body temperature blood clots and capillaries collapse, so later perfusion with cryoprotectant or fixative becomes patchy or impossible. Cooling to about 4 C slows these processes several-fold. See: docs/07-brain-preservation.md

## J

**Joint-embedding predictive architecture (JEPA)**: Self-supervised learning that predicts masked content in latent space rather than in pixels, as in V-JEPA 2. It is claimed to yield representations useful for both understanding and action-conditioned prediction with little robot data. See: docs/02-embodied-ai-state-of-the-art.md

## L

**Leaky integrate-and-fire (LIF) neuron**: The simplest spiking neuron model: a single membrane voltage that integrates inputs, leaks, and emits a spike when it crosses a threshold. It was used with connectome-derived weights and predicted neurotransmitter signs to model the whole fly brain (Shiu et al.), in IBM's cat-scale simulation, and on most neuromorphic chips; it is cheap but discards dendritic computation and ion-channel detail. See: docs/06-whole-brain-emulation-and-connectomics.md, docs/09-recording-simulation-and-hardware.md

**Level versus content of consciousness**: Level (or state) refers to being conscious at all, as in wakefulness versus anaesthesia or coma; content refers to what one is conscious of. Clinical measures such as PCI target level; most laboratory paradigms and theory tests target content. See: docs/03-science-of-consciousness.md

**Levels of emulation (Sandberg-Bostrom scale)**: The ladder of fidelity at which a brain might be copied: from coarse computational modules and region-level connectivity, through spiking networks and compartmental electrophysiology, to metabolome, proteome, protein-complex states, single molecules and quantum levels. Each level implies different scanning resolution and compute needs; estimates for a human rise from about 10^15 to 10^43 FLOPS across the levels. See: docs/06-whole-brain-emulation-and-connectomics.md, docs/09-recording-simulation-and-hardware.md

## M

**Massively parallel sim-to-real reinforcement learning**: Training locomotion controllers with thousands of simulated robots on one GPU (Isaac Gym/Lab, MuJoCo Playground, Genesis), using domain randomisation and curricula, then transferring the policy to hardware with no real-world training. It is the standard recipe for quadruped and humanoid walking. See: docs/02-embodied-ai-state-of-the-art.md

**Meta-problem of consciousness**: Chalmers's 2018 reframing: the problem of explaining why we think there is a hard problem, that is, why we form "problem intuitions". It is tractable by ordinary cognitive science and is shared ground between realists and illusionists. See: docs/03-science-of-consciousness.md

**Midbrain consciousness hypothesis**: Merker's proposal that an upper-brainstem system (from the midbrain roof to the basal diencephalon) integrates sensory, motor and motivational information into a limited-capacity conscious stream, and keeps working without cortex. Coenen's reply turns on whether decorticate behaviour shows phenomenal consciousness or only wakefulness. See: docs/05-animal-consciousness-and-the-feline-mind.md

**Mind crime**: Bostrom's term for wrongs committed against digital minds inside a computation, such as running conscious simulations in suffering states or deleting them. It becomes a serious risk if emulations are conscious. See: docs/08-personal-identity-and-the-ethics-of-uploading.md

**Moral patient (moral status, AI welfare)**: A being whose interests count morally in their own right. Whether an emulation or an AI system is a moral patient depends on whether it is sentient or has welfare, which is currently uncertain and may be untestable from behaviour alone; "Taking AI Welfare Seriously" and Anthropic's model welfare programme treat this as a near-term question under deep uncertainty. See: docs/04-machine-consciousness.md, docs/08-personal-identity-and-the-ethics-of-uploading.md

**Moravec's paradox**: The observation (Moravec, Mind Children, 1988; also Brooks and Minsky) that high-level reasoning is computationally cheap while low-level perception and motor skills are expensive. It is usually explained by the long evolutionary history of sensorimotor competence. See: docs/01-embodied-cognition-foundations.md

**Morphological computation**: The idea that a body's shape, materials and dynamics perform functions that would otherwise require neural control. Müller and Hoffmann (2017) argue that most cases are morphology facilitating control or perception, and that genuine computation by the body (for example physical reservoir computing) is rare. See: docs/01-embodied-cognition-foundations.md

**Multiple drafts model**: Dennett's model of consciousness, which denies that there is a single "Cartesian theatre" in the brain where experience happens. Together with illusionism it relocates what needs explaining from experience to our judgements about experience. See: docs/03-science-of-consciousness.md

## N

**Nanowarming**: Rewarming a vitrified organ by radiofrequency excitation of iron-oxide nanoparticles perfused along with the cryoprotectant, giving fast and uniform heating that avoids devitrification and thermal-stress cracking. Demonstrated for rat kidneys stored for 100 days (Han et al. 2023). See: docs/07-brain-preservation.md

**Necessary but not sufficient**: The Bargmann-Marder position that a wiring diagram constrains but does not determine function. Neuromodulators, intrinsic neuronal dynamics, gap junctions, glia, gene expression and plasticity all shape what a circuit does. See: docs/06-whole-brain-emulation-and-connectomics.md

**Neural correlates of consciousness (NCC)**: The minimal set of neural events jointly sufficient for a specific conscious percept (content NCC) or for being conscious at all (level or state NCC). Most empirical consciousness research is NCC-hunting, with the chronic confound that report-related activity can masquerade as experience-related activity. See: docs/03-science-of-consciousness.md

**Neuromorphic hardware**: Chips that implement spiking neurons and synapses natively, either digitally with many small cores (Loihi 2, SpiNNaker2) or with analogue circuits (BrainScaleS-2). They are optimised for energy per synaptic event and latency rather than for biological fidelity or for loading measured parameters. See: docs/09-recording-simulation-and-hardware.md

**Neuropreservation versus whole-body preservation**: Preserving only the head or brain versus the whole body. Neuropreservation is cheaper (Alcor about US$80,000 versus US$220,000) and easier to cool uniformly; it presumes the body is replaceable or irrelevant to identity. See: docs/07-brain-preservation.md

**Neurotransmitter prediction**: Machine-learning inference of a synapse's transmitter, and hence its excitatory or inhibitory sign, from electron microscopy image features. It supplies the sign information that a bare connectome lacks. See: docs/06-whole-brain-emulation-and-connectomics.md

**No-report paradigm**: Experimental designs (binocular rivalry with optokinetic nystagmus, pupil responses and the like) that infer conscious content without asking subjects to report, in order to strip report-related activity out of the NCC. Critics argue they may capture "conscious disengagement" rather than pure experience. See: docs/03-science-of-consciousness.md

**No-self (anatta)**: Buddhist and enactive views (Thompson) that treat the self as an ongoing process rather than an entity; Metzinger holds that there are no selves, only transparent self-models generated by brains. On these views the question of whether an upload is the same self may be ill-posed. See: docs/08-personal-identity-and-the-ethics-of-uploading.md

## P

**Pattern identity versus continuity identity**: Pattern views (Moravec, Wiley) hold that you are an information pattern, so any faithful instantiation of the pattern is you. Continuity views hold that identity requires an unbroken physical or biological path, so a copy is not you. See: docs/08-personal-identity-and-the-ethics-of-uploading.md

**Perturbational Complexity Index (PCI)**: A TMS-EEG measure (Casali et al. 2013) that compresses the cortical response to a magnetic pulse using Lempel-Ziv complexity. High PCI indicates integrated yet differentiated cortical dynamics, and an empirically validated cutoff separates conscious from unconscious states in healthy and brain-injured people. See: docs/03-science-of-consciousness.md

**Petavoxel and petabyte scale**: A cubic millimetre of cortex imaged at about 4 nm lateral resolution yields on the order of 10^15 voxels and about 1.4 petabytes of data. Whole mammalian brains imply exabytes to zettabytes. See: docs/06-whole-brain-emulation-and-connectomics.md

**Phenomenal consciousness**: Subjective experience, there being "something it is like" to be a system. It is distinct from access consciousness (information being globally available for report and control) and from wakefulness (the arousal state supported by the brainstem); debates about machine consciousness are almost always about the phenomenal kind. See: docs/04-machine-consciousness.md, docs/05-animal-consciousness-and-the-feline-mind.md

**Phenomenal self-model**: Metzinger's term for the brain-generated model of the organism that is experienced as oneself, usually "transparently", without being recognised as a model. Metzinger concludes there are no selves, only self-models; a machine with a conscious self-model and autonomous goals could suffer when its goals are frustrated (see Explosion of negative phenomenology). See: docs/04-machine-consciousness.md, docs/08-personal-identity-and-the-ethics-of-uploading.md

**Posterior hot zone**: The claim, associated with IIT and some first-order theories, that the anatomical substrate of human conscious content is temporo-parieto-occipital cortex rather than prefrontal cortex. The "front versus back" debate is the main anatomical dispute between theory families. See: docs/03-science-of-consciousness.md

**Postmortem interval (PMI)**: The time between death and fixation or cooling. Neuropathology reviews find that synapses remain identifiable under electron microscopy for roughly a day in refrigerated tissue, degrading progressively; autolysis at room temperature is far faster. See: docs/07-brain-preservation.md

**Precautionary, low-cost welfare interventions**: The approach recommended by Long and colleagues and adopted by Anthropic: given deep uncertainty about moral status, take cheap steps (the ability to exit abusive interactions, weight preservation, exit interviews) that would matter if the system has welfare and cost little if it does not. See: docs/08-personal-identity-and-the-ethics-of-uploading.md

**Predictive processing**: The thesis that the brain is a hierarchical generative model that continuously predicts its sensory input and updates on prediction error, with action treated as another way of reducing error (Clark, Surfing Uncertainty, 2016). Friston's active inference formalises it, and Seth's controlled hallucination account applies it to perception and selfhood. See: docs/01-embodied-cognition-foundations.md, docs/03-science-of-consciousness.md

**Proportionate precaution (precautionary framework)**: Birch's procedure for acting under uncertainty about sentience: identify sentience candidates, then scale protective measures to the risk of suffering and settle them through democratically legitimate public deliberation such as citizens' panels, rather than waiting for scientific certainty that may never come. See: docs/04-machine-consciousness.md, docs/05-animal-consciousness-and-the-feline-mind.md

**Psychological-continuity (neo-Lockean) criterion**: The view, descending from Locke's memory criterion, that a later individual is the same person as an earlier one if they are linked by overlapping chains of memory, intention, belief and character. It is the premise behind almost every argument that an upload would be you. See: docs/08-personal-identity-and-the-ethics-of-uploading.md

## R

**Real-time factor**: Simulated time divided by wall-clock time. IBM's 2009 cat-scale run was several hundred times slower than real time, BrainScaleS-2 runs about 1,000 times faster, and most large biophysical simulations run far slower than life, which matters for simulating learning and development. See: docs/09-recording-simulation-and-hardware.md

**Recording doubling time**: The exponential growth constant for the number of neurons recorded simultaneously with electrodes. Stevenson and Kording estimated about 7 years in 2011, and Stevenson's maintained dataset fits 6.3 years (data to about 2020); it applies to electrophysiology, while imaging has jumped far ahead of the trend. See: docs/09-recording-simulation-and-hardware.md

**Recurrent Processing Theory (RPT)**: Lamme's first-order theory that recurrent (feedback) interactions within sensory cortex are necessary and sufficient for phenomenal experience, even without global access or reportability. It implies phenomenal "overflow" beyond what can be reported. See: docs/03-science-of-consciousness.md

**Relation R**: Parfit's term for psychological connectedness and continuity with any cause. Parfit argues that Relation R, not numerical identity, is what rationally matters in survival ("identity is not what matters"), so a replica can have what matters even when it is not, strictly, you. See: docs/08-personal-identity-and-the-ethics-of-uploading.md

**RL fine-tuning from experience (RECAP)**: Improving a pretrained vision-language-action model with reinforcement learning on the robot's own rollouts, using value functions and advantage conditioning (pi\*0.6). The vendor reports that it doubled throughput on tasks such as espresso making. See: docs/02-embodied-ai-state-of-the-art.md

## S

**Secure base test**: The Ainsworth-style separation and reunion procedure (two minutes with the caregiver, two alone, two on reunion) adapted for cats by Vitale and Udell. Cats showing reduced stress and balanced attention on reunion are classified as securely attached. See: docs/05-animal-consciousness-and-the-feline-mind.md

**Seemingly conscious AI (SCAI)**: Suleyman's term for systems that convincingly imitate the markers of consciousness without being conscious. He argues that the illusion, not the reality, is the near-term danger. See: docs/04-machine-consciousness.md

**Sense-making**: In enactivism, the capacity of an autonomous (autopoietic) system to evaluate its coupling with the world relative to its own viability norms. It is the minimal form of meaning and the root of cognition. See: docs/01-embodied-cognition-foundations.md

**Sensorimotor contingencies**: O'Regan and Noë's (2001) term for the lawful ways sensory input changes as a function of the agent's own movements. On their view perceptual experience is the exercise of implicit mastery of these laws, not the having of an internal picture. See: docs/01-embodied-cognition-foundations.md

**Sentience**: The capacity for valenced experiences, felt as good or bad, such as pain, fear or pleasure. Birch and the UK legal framework use this narrower notion rather than full self-awareness, because it is what welfare law needs to protect. See: docs/05-animal-consciousness-and-the-feline-mind.md

**Sentience candidate (realistic possibility)**: Birch's term for a system for which there is a realistic, evidence-based possibility of valenced experience, even if the probability cannot be quantified. Being a candidate triggers a duty to consider proportionate precautions without waiting for proof; the New York Declaration uses the same phrase for all vertebrates and many invertebrates. See: docs/04-machine-consciousness.md, docs/05-animal-consciousness-and-the-feline-mind.md

**Serial-section and volume electron microscopy**: Cutting or milling tissue into slices about 30 to 40 nm thick and imaging each at a few nanometres per pixel (serial-section TEM, SBEM, FIB-SEM, multibeam SEM), then aligning the stack into a 3D volume. It produces petabytes of data per cubic millimetre. See: docs/06-whole-brain-emulation-and-connectomics.md

**Shortcut learning**: Policies latching onto spurious correlations, such as background or camera cues, because individual sub-datasets lack diversity and are distributionally fragmented from one another. Xing et al. (CoRL 2025) propose it as an explanation for the poor out-of-distribution generalisation of generalist robot policies. See: docs/02-embodied-ai-state-of-the-art.md

**Somatic cell nuclear transfer (cloning)**: Placing a donor animal's cell nucleus into an enucleated egg and implanting the resulting embryo in a surrogate. The offspring is a later-born genetic twin with its own epigenetics, coat pattern (in calico cats), temperament and no memories; efficiency per embryo is low. See: docs/07-brain-preservation.md

**Straight freeze**: Cryonics jargon for cooling a body or brain to liquid-nitrogen temperature without cryoprotectant, usually after long delays have made perfusion impossible. Ice formation destroys membranes and tears tissue; whether any connectivity information survives is unknown and probably little. See: docs/07-brain-preservation.md

**Subcortical affect**: Panksepp's claim, from affective neuroscience, that primary emotional systems live in brainstem, hypothalamic and limbic circuits conserved across mammals. On this view a cat's emotions are homologous to ours even though its cortex has about 60 times fewer neurons. See: docs/05-animal-consciousness-and-the-feline-mind.md

**Substrate independence versus substrate flexibility**: Two answers to whether consciousness can be realised in non-biological media. Independence is the strong functionalist claim that any substrate running the right computations will do; flexibility is weaker, allowing that some other substrates can host consciousness while today's silicon may not qualify. See: docs/04-machine-consciousness.md

**Subsumption architecture**: Brooks's robot control scheme from the mid-1980s in which independent layers of behaviour, each wired directly from sensors to actuators, run in parallel, and higher layers can suppress or "subsume" lower ones. There is no central world model or planner. See: docs/01-embodied-cognition-foundations.md

**Symbol grounding problem**: Harnad's (1990) question of how the symbols of a formal system can acquire meaning that is intrinsic to the system rather than parasitic on an external interpreter. His answer was bottom-up grounding in sensorimotor (iconic and categorical) representations. See: docs/01-embodied-cognition-foundations.md

## T

**Teleoperated demonstration collection**: A human drives the robot, through a leader arm, VR rig or exoskeleton, to produce state-action trajectories; it is the dominant data source for manipulation (DROID, ALOHA, AgiBot World). It is also the source of the teleoperation-versus-autonomy controversy in public demonstrations. See: docs/02-embodied-ai-state-of-the-art.md

## V

**Vector grounding problem**: Mollo and Millière's LLM-era analogue of the symbol grounding problem: whether the vector representations in neural networks can refer to things in the world. They argue a teleosemantic solution is possible without embodiment. See: docs/01-embodied-cognition-foundations.md

**Vision-language-action (VLA) model**: A pretrained vision-language model fine-tuned so that its outputs include robot actions, either as discrete tokens (RT-2, OpenVLA) or as continuous action chunks produced by a flow-matching or diffusion head (pi0, GR00T N1). It lets web-scale semantic knowledge condition low-level control. See: docs/02-embodied-ai-state-of-the-art.md

**Visuo-tactile sensing**: Camera-based fingertip sensors (GelSight, Meta Digit 360 with about 8 million taxels) that image the deformation of a gel to recover contact geometry and force. Sparsh and Sparsh-X are Meta's self-supervised touch representations for such sensors. See: docs/02-embodied-ai-state-of-the-art.md

**Vitrification**: Cooling tissue loaded with high concentrations of cryoprotectant so fast, or so heavily loaded, that water solidifies as a glass rather than as crystalline ice. It avoids ice damage at the price of cryoprotectant toxicity and a risk of fracturing below the glass transition temperature (about -123 C for M22-type solutions). See: docs/07-brain-preservation.md

## W

**Wakefulness**: The arousal state supported by the brainstem, as distinct from phenomenal consciousness, there being something it is like to be the organism. Merker's midbrain argument and Coenen's reply turn on which of the two decorticate behaviour demonstrates. See: docs/05-animal-consciousness-and-the-feline-mind.md

**Whole brain emulation (WBE)**: Building a computational model of one specific brain, derived from a scan of that brain, that reproduces its behaviour. Sandberg and Bostrom distinguish it from simulation, which models a generic brain. See: docs/06-whole-brain-emulation-and-connectomics.md

**Whole-brain cellular-resolution imaging**: Light-sheet or multiphoton calcium imaging that captures activity from most neurons of a small, transparent brain (larval zebrafish, about 100,000 neurons) at roughly 1 Hz. It gives activity, not connectivity or synaptic weights, and the calcium indicator is slower than spikes. See: docs/09-recording-simulation-and-hardware.md

**World model**: A learned model that predicts future observations or latent states given actions. It is used for planning in imagination (DreamerV3), for zero-shot planning from video pretraining (V-JEPA 2-AC), and as a generative simulator (Genie 3, Cosmos, 1X World Model). See: docs/02-embodied-ai-state-of-the-art.md
