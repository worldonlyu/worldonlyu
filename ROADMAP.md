# Roadmap

A learning and research roadmap for a multi-year, part-time programme on embodied AI, consciousness science and whole brain emulation. Written 2026-10-09 for a programmer and security researcher who is starting from a strong software background and little formal neuroscience or philosophy. The chapters in `docs/` are the map of the field; this file is the plan for crossing it.

One sentence of honesty before the plan. Nothing in this roadmap leads to recovering an animal that has already died, and nothing in the current science suggests that it could. What the roadmap can do is make you competent enough to understand the question, to tell real progress from marketing, and to contribute to the parts of the field that are actually moving. See the final section for what that does and does not mean.

## How to use this roadmap

- **Three tracks run in parallel, not in sequence.** Track A (hands-on embodied AI) keeps you building. Track B (consciousness science and emulation) gives you the empirical core. Track C (philosophy and ethics) tells you what success would even mean. A reasonable split for a given month is roughly 40 percent A, 40 percent B, 20 percent C, shifting toward B and C as the project matures. If you skip C you will build things without knowing what they would mean; if you skip A you will theorise without ever feeling how hard sensorimotor competence is.
- **Time estimates assume 10 to 15 hours a week** alongside a job. Halve them for full-time study, and expect them to be optimistic anyway: every stage here took its original authors years.
- **Every stage names a chapter.** The chapter's "Where to start" section holds the URLs, prices and software names current as of October 2026. This file deliberately repeats few URLs, so that it goes stale more slowly.
- **Use the notebook.** Start every paper with `notes/templates/paper.md` and every week with `notes/templates/weekly.md`. Write `notes/00-why-i-started.md` before anything else. The weekly template asks what changed your mind; that question is the real progress metric.
- **Edit this file.** Dates, prices and the state of the field will drift. When a stage turns out to be wrong, too easy or too hard, rewrite it and note the date. When you close an open question, update `OPEN-QUESTIONS.md` in the same commit.
- **Prefer reproducing over reading.** Where a stage offers a choice between reading a paper and running its code, run the code. Most of what this field knows that it does not say is in the code.

## Prerequisites

You do not need all of this before starting. Treat the lists below as a menu, learn what the current stage requires, and come back for the rest. A programmer with a working knowledge of linear algebra and probability can start Track A in the first week. Expect three to six months of interleaved study to cover everything here to the "self-check" level.

### Mathematics

What you need, in decreasing order of urgency:

1. **Linear algebra** to the level of eigendecomposition, SVD and least squares. Gilbert Strang's *Introduction to Linear Algebra* and his MIT 18.06 lectures (free through MIT OpenCourseWare) are the standard route; the 3Blue1Brown *Essence of Linear Algebra* videos give the geometric intuition in a few hours.
2. **Probability and statistics**, including Bayesian inference, effect sizes, confidence intervals and what preregistration is for. Blitzstein and Hwang, *Introduction to Probability* (the Harvard Stat 110 textbook, with free lectures) covers the probability. David MacKay's *Information Theory, Inference, and Learning Algorithms* (free from the author's site) covers Bayesian inference and the information theory you will need for both Integrated Information Theory and the Perturbational Complexity Index. The replication-crisis material in `docs/01-embodied-cognition-foundations.md` is the reason to take the statistics seriously: a field can run for a decade on effects that are not there.
3. **Differential equations and dynamical systems.** Neuron models, enactivist "dynamical coupling", locomotion controllers and the free-energy principle are all written in this language. Strogatz, *Nonlinear Dynamics and Chaos*, is the readable standard. You need to be comfortable simulating a small system of ODEs numerically and reading a phase portrait.
4. **Optimisation.** Gradient descent and its variants, which the *Deep Learning* textbook (below) covers adequately. Boyd and Vandenberghe, *Convex Optimization* (free PDF from the authors) is for later, if active inference or control theory pulls you in.
5. **Graph theory basics**: degree distributions, paths, motifs, community structure. Connectomes are graphs. Any introductory text will do.

Self-check: derive backpropagation for a two-layer network by hand; simulate a two-dimensional ODE and plot its phase portrait; compute the mutual information of a small joint distribution; explain to a friend why a 95 percent confidence interval of -0.11 to +0.16 on a 10-point scale is a null result.

### Neuroscience

1. **A reference text**, not to be read cover to cover: Kandel et al., *Principles of Neural Science*, or Purves et al., *Neuroscience* (lighter). Use them to look things up when a paper assumes anatomy you do not have.
2. **Computational neuroscience**, which is the part that matters for emulation: Gerstner, Kistler, Naud and Paninski, *Neuronal Dynamics* (free online edition at neuronaldynamics.epfl.ch; print from Cambridge University Press), for integrate-and-fire and Hodgkin-Huxley models, plasticity rules and population dynamics. Dayan and Abbott, *Theoretical Neuroscience*, for the more mathematical treatment. The Neuromatch Academy computational neuroscience course materials are free and have exercises.
3. **Why brains are built the way they are**: Sterling and Laughlin, *Principles of Neural Design*, for the energy and wiring constraints that explain much of what the connectome papers find.
4. **Connectomics as a field**: Sebastian Seung, *Connectome* (2012), the standard popular introduction (`docs/06-whole-brain-emulation-and-connectomics.md`).
5. **Specific to this project**: the subcortical and brainstem systems (Merker's 2007 target article with its commentaries, in `docs/05-animal-consciousness-and-the-feline-mind.md`); the cat visual cortex (Hubel and Wiesel 1959 and 1962, same chapter); anaesthesia and the measurement of conscious level (`docs/03-science-of-consciousness.md`).

Self-check: explain what a synapse count does and does not tell you about synaptic strength; describe neuromodulation and why it is absent from a wiring diagram; state the difference between a point-neuron and a multi-compartment model and when each is adequate; name the main cortical and subcortical structures in a mammal and roughly what each does.

### Machine learning and robotics

1. **Deep learning**: Goodfellow, Bengio and Courville, *Deep Learning* (free online). You already program; the point is the concepts, not the framework. PyTorch is the practical default for everything in Track A.
2. **Reinforcement learning**: Sutton and Barto, *Reinforcement Learning: An Introduction* (free online, second edition), then OpenAI's *Spinning Up in Deep RL* for PPO and SAC with runnable code. Locomotion in `docs/02-embodied-ai-state-of-the-art.md` is the one place RL reliably works, and you should feel that for yourself.
3. **Robotics fundamentals**: Lynch and Park, *Modern Robotics* (free PDF, with a Coursera specialisation) for kinematics and dynamics; Russ Tedrake's MIT course notes *Underactuated Robotics* and *Robotic Manipulation* (free online) for control and manipulation; Thrun, Burgard and Fox, *Probabilistic Robotics*, for state estimation.
4. **The embodied-AI texts** cited in the chapters: Pfeifer and Bongard, *How the Body Shapes the Way We Think*; Cangelosi and Schlesinger, *Developmental Robotics*; Parr, Pezzulo and Friston, *Active Inference* (open access). All three are discussed in `docs/01-embodied-cognition-foundations.md`.
5. **Tooling**: Python, PyTorch, MuJoCo (with MuJoCo Playground or Genesis for massively parallel RL), Gymnasium environments, and a Linux machine with an NVIDIA GPU of 16 to 24 GB or an equivalent cloud budget of a few dollars an hour. Hugging Face's LeRobot library is the entry point for real robots (`docs/02-embodied-ai-state-of-the-art.md`).

Self-check: train a PPO agent on a continuous-control task from scratch and explain each hyperparameter you set; explain the difference between imitation learning and RL and why manipulation uses the former; explain the sim-to-real gap and the two main ways people close it; read a vision-language-action model's architecture diagram and say what each block does.

### Philosophy of mind

1. **A map of the positions**: Jaegwon Kim, *Philosophy of Mind*, is a standard textbook; the Stanford Encyclopedia of Philosophy entries on consciousness, functionalism, personal identity, embodied cognition and animal consciousness are free and authoritative. Read the SEP entry on personal identity (by Eric Olson) before anything in `docs/08-personal-identity-and-the-ethics-of-uploading.md`.
2. **The hard problem argued both ways**: Chalmers, *The Conscious Mind* (1996), and Dennett, *Consciousness Explained* (1991). You will not resolve their disagreement, but you need to be able to state both positions without caricature.
3. **Personal identity**: Parfit, *Reasons and Persons*, Part Three, is the single most important text for the central question (`docs/08-personal-identity-and-the-ethics-of-uploading.md`). Read it slowly.
4. **Animal minds**: Peter Godfrey-Smith, *Other Minds* (2016), for an evolutionary approach to the question of what it is like to be a very different animal; then Birch, *The Edge of Sentience* (2024, open access), for the precautionary framework (`docs/05-animal-consciousness-and-the-feline-mind.md`).
5. **Embodiment and enactivism**: Varela, Thompson and Rosch, *The Embodied Mind*; Clark, *Surfing Uncertainty* (`docs/01-embodied-cognition-foundations.md`).

Skills matter more than coverage here: distinguishing a conceptual claim from an empirical one; writing the strongest version of a view you reject; noticing when an argument has quietly assumed functionalism or its denial.

Self-check: state Parfit's fission argument and the animalist reply in one paragraph each; say what Global Neuronal Workspace Theory and Integrated Information Theory predict differently about the same experiment, and why that disagreement is empirical rather than conceptual; explain why "the upload says it is conscious" is weak evidence.

### A note for a security researcher

Several of your existing skills transfer directly, and it is worth noticing where.

- **Reverse engineering.** Jonas and Kording's attempt to understand a MOS 6502 with neuroscience methods (`docs/06-whole-brain-emulation-and-connectomics.md`, `docs/09-recording-simulation-and-hardware.md`) is a reverse-engineering problem with full ground truth, and they failed. You know what it takes to recover function from a binary; ask whether connectomics has the equivalent of a disassembler, let alone a decompiler.
- **Adversarial evaluation.** Shortcut learning in robot policies, LIBERO-Plus perturbations and RoboArena's double-blind comparisons (`docs/02-embodied-ai-state-of-the-art.md`) are red-teaming. So is Birch's "gaming problem" for AI consciousness tests (`docs/04-machine-consciousness.md`).
- **Threat modelling.** The precautionary frameworks for sentience candidates and emulation welfare (`docs/04-machine-consciousness.md`, `docs/08-personal-identity-and-the-ethics-of-uploading.md`) are threat models with the harm falling on the system you build. You know how to write one.
- **Scepticism about vendor claims.** Most robotics numbers in `docs/02-embodied-ai-state-of-the-art.md` are company-reported; most preservation prices in `docs/07-brain-preservation.md` are unverified. Treat them as you would a vendor's security whitepaper.
- **Data at scale.** A cat brain at current imaging density is tens of exabytes of raw data (`docs/06-whole-brain-emulation-and-connectomics.md`). The storage, integrity and provenance problems are engineering you already understand.

## Track A: Embodied AI (hands-on)

Purpose: to understand, by building, what a body contributes to a mind, how competence is acquired, and how far current systems are from any animal. Budget tiers: everything through A2 is free given a GPU or modest cloud spend; A3 costs roughly 150 to 500 USD in parts; anything beyond A3 is optional and the chapter marks the point where hardware becomes institutional rather than personal.

Chapters: `docs/02-embodied-ai-state-of-the-art.md` (A1 to A4, A8), `docs/01-embodied-cognition-foundations.md` (A5 to A7).

### A1. Simulated locomotion with reinforcement learning

- **Goal.** Reproduce the one result in robot learning that reliably works: a legged robot trained to walk in minutes by simulating thousands of copies in parallel.
- **Build or read.** Install MuJoCo and MuJoCo Playground (or Genesis), train a quadruped walking policy with PPO; on an RTX-class GPU, install Isaac Lab and run its locomotion examples, which recreate Rudin et al.'s result. Read the Rudin et al. paper and the chapter's section on locomotion.
- **Success looks like.** A policy you trained walks on flat and then rough terrain in simulation; you can explain the reward terms, the domain randomisation and why sim-to-real works here and not for manipulation; you have a plot of training curves in `notes/experiments/`.
- **Time.** 4 to 8 weeks.

### A2. Run, evaluate and fine-tune an open vision-language-action model

- **Goal.** See what a "generalist" robot policy actually does, and how it fails.
- **Build or read.** Download a LIBERO suite or a DROID subset in LeRobot format. Run OpenVLA-7B, or the LeRobot ports of pi0.5 and GR00T N1.7, in evaluation. Then run the LIBERO-Plus perturbations (camera, lighting, layout) and measure the degradation. Fine-tune on 50 episodes with parameter-efficient methods. Read RT-2, Open X-Embodiment and pi0 in that order, and the shortcut-learning analysis the chapter cites.
- **Success looks like.** A table of success rates for one policy on the standard suite and under each perturbation class; a paragraph explaining the gap in terms of data homogeneity and shortcut learning; a fine-tuned checkpoint that improves on at least one task.
- **Time.** 6 to 10 weeks. Needs a 16 to 24 GB GPU or a few dollars of cloud time.

### A3. A real robot: teleoperate, imitate, measure

- **Goal.** Close the loop on physical hardware and learn why every unit of real skill is expensive.
- **Build or read.** Build an SO-101 leader-follower pair (kits from about 130 to 250 USD, plus a 3D printer or print service and a USB webcam). Follow the LeRobot documentation, teleoperate 50 demonstrations of a pick-and-place, train ACT or a diffusion policy overnight, then fine-tune pi0.5 or GR00T N1.7 on the same data. This is the Mobile ALOHA loop at roughly a hundredth of the cost.
- **Success looks like.** A policy that succeeds on the trained layout, a measured success rate on a held-out layout you did not demonstrate, and an honest write-up of the gap. The second number is the one that matters; it is usually bad.
- **Time.** 3 to 4 months including the build and debugging. Mechanical and electrical problems will take longer than the learning.

### A4. World models

- **Goal.** Understand model-based RL and learned simulators, which are the prerequisite for hosting any agent in a virtual body.
- **Build or read.** Run the open DreamerV3 code on a DeepMind Control task and read the Nature paper. Read V-JEPA 2 and the chapter's discussion of generative video world models (Genie 3, Cosmos) with its warning that robot-control results from them are mostly company demos.
- **Success looks like.** A Dreamer agent that learns a task from pixels; a note explaining the latent world model, planning in imagination and why this is and is not a step toward simulating an environment for an emulated animal.
- **Time.** 6 to 8 weeks.

### A5. Intrinsic motivation and active inference

- **Goal.** Build an agent that chooses what to learn, the algorithmic core of developmental robotics, and implement the active-inference framework that `docs/01-embodied-cognition-foundations.md` presents as the main synthesis of embodiment and prediction.
- **Build or read.** Implement Oudeyer, Kaplan and Hafner's Intelligent Adaptive Curiosity on a simulated arm and watch developmental stages emerge without scripting. Then implement a small discrete active-inference agent from Parr, Pezzulo and Friston's textbook (the `pymdp` Python package is a reference implementation) and compare it with a reward-maximising baseline.
- **Success looks like.** Plots showing the curiosity-driven agent's choice of activity shifting with its learning progress; an active-inference agent whose behaviour you can explain in terms of expected free energy; a paragraph on what each framework claims about bodies that a disembodied model cannot satisfy.
- **Time.** 2 to 3 months.

### A6. Interoception and homeostasis in an artificial agent

- **Goal.** Test, in the smallest possible setting, the claim that self-regulation of a body is part of what makes a mind (Seth's "beast machine", enactive autonomy, open question 5 of `docs/01-embodied-cognition-foundations.md`).
- **Build or read.** Give a simulated agent internal variables (energy, temperature, damage) with homeostatic set points and let them shape reward or precision. Compare learning, exploration and robustness with and without the interoceptive loop. Read Di Paolo on autonomy and Seth's biological-naturalism target article with its commentaries.
- **Success looks like.** A controlled comparison with a clear result either way, and a written judgement of what it does and does not show about the constitutive-versus-causal question. A null result is a fine result.
- **Time.** 2 to 3 months. Year two.

### A7. Toward an embodied Turing test

- **Goal.** Measure the gap between an artificial agent and an animal on a sensorimotor task, which is how `docs/01-embodied-cognition-foundations.md` says the embodiment hypothesis should be tested.
- **Build or read.** Choose one animal-like sensorimotor competence with published behavioural data (prey pursuit, navigation to a remembered location, obstacle negotiation) and build a simulated agent with a body of roughly the right morphology. Define the metric before you build. Read Zador et al. on the embodied Turing test and the chapter's open question on operationalising it.
- **Success looks like.** A benchmark definition others could run, a baseline number, and a documented gap to the animal. Do not expect to close it.
- **Time.** Open-ended; years two to three.

### A8. Evaluation, data and contribution

- **Goal.** Turn what you build into something the field can use.
- **Build or read.** Contribute multi-camera, language-annotated episodes in LeRobot format to the Hugging Face hub; replicate one published result and publish the replication, including failures; build or extend a robustness evaluation harness in the spirit of LIBERO-Plus and RoboArena.
- **Success looks like.** At least one public dataset contribution and one public replication report with code.
- **Time.** Ongoing from month 9.

A frank note on scope. A solo researcher cannot train a frontier VLA or run a humanoid programme. What a solo researcher can do, and what the field is short of, is careful evaluation, honest replication, open data and small controlled experiments that test a specific claim about embodiment. Aim there.

## Track B: Consciousness science and whole brain emulation (theory and tools)

Purpose: to understand what is known about how brains produce experience, what a connectome does and does not contain, what can be recorded and simulated at what scale, and how any emulation could be validated. This is the empirical centre of the project.

Chapters: `docs/03-science-of-consciousness.md`, `docs/05-animal-consciousness-and-the-feline-mind.md`, `docs/06-whole-brain-emulation-and-connectomics.md`, `docs/07-brain-preservation.md`, `docs/09-recording-simulation-and-hardware.md`.

### B1. Neuron models from scratch

- **Goal.** Build the smallest pieces an emulation is made of, so that every later "we modelled the neurons as X" has concrete meaning.
- **Build or read.** Working from *Neuronal Dynamics*, implement a leaky integrate-and-fire neuron, a Hodgkin-Huxley neuron and a small recurrent network with spike-timing-dependent plasticity in plain Python or NumPy. Then reproduce Hubel and Wiesel's receptive-field logic with a Gabor-filter model of simple and complex cells, as `docs/05-animal-consciousness-and-the-feline-mind.md` suggests; it is the cheapest way to understand what cat visual cortex computes.
- **Success looks like.** Tuning curves and f-I curves that match the textbook; a model complex cell that is phase-invariant; a one-page note on what each abstraction throws away.
- **Time.** 6 to 8 weeks.

### B2. Connectomes by hand

- **Goal.** Feel the "which connectome?" problem and see what a wiring diagram looks like at every scale that exists.
- **Build or read.** Install the OpenWorm Connectome Toolbox and load the Cook 2019 and Witvliet 2021 C. elegans datasets; document where they disagree. Browse FlyWire through Codex, query the Janelia male CNS through neuPrint, and work through the MICrONS Explorer tutorial on the mouse cubic millimetre. Read Bargmann and Marder, then Jonas and Kording.
- **Success looks like.** A short report on inter-dataset disagreement in the worm, with numbers; a diagram you traced yourself from fly sensory neuron to motor neuron; the ability to say, for each dataset, what it records (topology, synapse counts, predicted transmitter) and what it does not (weights, modulators, glia, plasticity).
- **Time.** 4 to 6 weeks.

### B3. Reproduce the fly whole-brain model

- **Goal.** Run the strongest existing evidence that structure plus simple dynamics can predict behaviour, then find its edges.
- **Build or read.** Reproduce Shiu et al.'s connectome-constrained leaky integrate-and-fire model of the Drosophila brain in Brian2 from the public repository (it runs on a laptop or in Colab). Activate sugar-sensing neurons and confirm the predicted feeding-circuit activation. Then perturb: silence neurons, change the weight scaling, try a crude neuromodulatory gain term, and see what breaks.
- **Success looks like.** A reproduced prediction with the paper's figure next to yours; a list of the model's assumptions (zero baseline firing, no gap junctions, no modulation beyond sign) with your own experiment on at least one of them; a judgement of whether the approach can extend to learning and internal state (open question 4 of `docs/06-whole-brain-emulation-and-connectomics.md`).
- **Time.** 2 to 3 months.

### B4. Consciousness science: theories, and the one adversarial test

- **Goal.** Learn the theory families, the validated measures of conscious level, and what happened when two theories were tested against each other.
- **Build or read.** Read Seth and Bayne's review, then the Cogitate Nature paper with the Quanta account and the Brain Inspired episode as guides. Download a sample of the Cogitate open dataset and reproduce one analysis (content decoding in visual cortex, or duration tracking). Read the PCI papers and the 2024 cognitive-motor-dissociation study for what clinical measurement looks like.
- **Success looks like.** A table of the four theory families with what each predicts about prefrontal cortex, report and substrate; a reproduced decoding result with its confidence interval; a one-paragraph account of why both GNWT and IIT were challenged and why both camps kept their theories.
- **Time.** 2 to 3 months.

### B5. Integrated Information Theory on a toy system

- **Goal.** Make the only theory precise enough to code concrete, including its tractability problem and its verdict on digital hardware.
- **Build or read.** Working from IIT 4.0 (open access), compute the cause-effect structure and Φ for a three- or four-node system, either from scratch or with the PyPhi package. Then try five, six and seven nodes and watch the combinatorics. Read the 2023 open letter, the 2025 Nature Neuroscience exchange and the replies.
- **Success looks like.** A working Φ computation you understand line by line; a plot of runtime against node count; a written argument, in your own words, for and against the claim that a neuron-level emulation on clocked serial hardware would have negligible Φ regardless of fidelity (open questions in `docs/03-science-of-consciousness.md`).
- **Time.** 4 to 6 weeks.

### B6. Recording: what can be read from a living brain

- **Goal.** Understand the gap between the best recording technology and a whole mammalian brain.
- **Build or read.** Work through the UCL Neuropixels course videos. Pull real units from the International Brain Laboratory brain-wide map through the ONE API and look at what tens of thousands of neurons recorded during behaviour actually look like. Refit Stevenson's doubling-time dataset with any post-2020 studies you can add, and extend the extrapolation honestly.
- **Success looks like.** A notebook with real spike rasters and your own doubling-time fit; a one-page comparison of electrophysiology, optical imaging and connectomics on what each measures (activity versus structure, living versus fixed, channels versus neurons); an explicit statement of why recording spikes is not reading a brain.
- **Time.** 6 to 8 weeks.

### B7. Large-scale simulation and its real costs

- **Goal.** Find out where brain simulation is bound (memory and communication, not FLOPs) by running into the limits yourself, then make your own cat-scale estimate.
- **Build or read.** Install NEST and scale a balanced random network from 10^4 to the largest size your machine allows, recording wall time and memory. Run the Allen Institute mouse V1 GLIF model through the Brain Modeling ToolKit. Try Nengo for the functional-modelling counterpoint. Read Sandberg and Bostrom's levels-of-emulation table, Carlsmith's compute report, and the chapter's account of IBM's 2009 "cat-scale" run and why Markram called it a hoax.
- **Success looks like.** Scaling plots with the knee where communication dominates; a written estimate, with stated assumptions, of what a cat brain at point-neuron and at compartmental fidelity would cost on 2026 hardware; a clear statement that the binding constraint is parameters, not FLOPs.
- **Time.** 2 to 3 months.

### B8. Preservation and decay: what survives death

- **Goal.** Know what each preservation method fixes, what an emulation would need, and how fast structure is lost after death.
- **Build or read.** Read McIntyre and Fahy on aldehyde-stabilised cryopreservation, the 2024 structural-preservation review, Krassner et al. on postmortem decay, and the Hendricks versus Hayworth exchange. Read the engram papers the chapter cites. Build a table: rows are features an emulation might need (connectivity, synapse size, receptor composition, ion channels, neuromodulator state, glial state, gene expression, plasticity rules); columns are preservation methods and postmortem intervals; cells are what the evidence says survives.
- **Success looks like.** The table, with a source in every cell or an explicit "unknown"; a one-page assessment of the claim that a preserved brain holds the information needed for emulation, written for someone who is grieving and deserves the truth.
- **Time.** 3 to 4 weeks.

### B9. A research contribution

- **Goal.** Pick one open question you can move with the tools you now have.
- **Build or read.** Candidates, in rough order of tractability: a validation benchmark for connectome-constrained models, specifying what a model must predict to count as faithful (open question in `docs/06-whole-brain-emulation-and-connectomics.md` and `docs/09-recording-simulation-and-hardware.md`); an analysis of which inter-individual wiring differences in the Witvliet worm series would change simulated behaviour; a quantitative review of postmortem decay curves (`docs/07-brain-preservation.md`); an entry in the Carboncopies Brain Emulation Challenge; extending the fly model with a documented neuromodulatory mechanism and testing it against published behaviour.
- **Success looks like.** A preprint or a well-documented public repository that a specialist would take seriously, with a limitations section you wrote before the results section.
- **Time.** Years two and three. Pick one, not three.

## Track C: Philosophy, ethics and personal identity

Purpose: to decide, as rigorously as you can, what it would mean for a mind to be emulated or transferred, whether the result would be the same mind, whether it would be conscious, and what you would owe to anything you built. This track produces documents, not code. Each stage ends in something written.

Chapters: `docs/01-embodied-cognition-foundations.md`, `docs/03-science-of-consciousness.md`, `docs/04-machine-consciousness.md`, `docs/05-animal-consciousness-and-the-feline-mind.md`, `docs/07-brain-preservation.md`, `docs/08-personal-identity-and-the-ethics-of-uploading.md`.

### C1. The grounding debate in forty pages

- **Goal.** Get the embodiment question into sharp form before reading any enthusiast.
- **Read.** Brooks, "Intelligence without representation"; Harnad, "The symbol grounding problem"; Goldinger et al., "The poverty of embodied cognition" and the reply. Then the LLM-era round: Bender and Koller against Mollo and Millière and Ma and Narayanan, with Pezzulo et al. in between.
- **Success looks like.** A two-page note stating the strongest version of "intelligence requires a body", the strongest version of "grounding yes, body no", and which empirical finding would move you between them.
- **Time.** 3 to 4 weeks.

### C2. Personal identity and the copy problem

- **Goal.** Form a defended view on whether an emulation could be the same individual, and apply it to a non-human animal.
- **Read.** The SEP entry on personal identity; Dennett, "Where Am I?"; Parfit, *Reasons and Persons*, Part Three; Williams on the body-swap case; Olson on animalism; Chalmers, "The Singularity: A Philosophical Analysis", on gradual versus destructive uploading; Wiley and Koene's reply; Cerullo on branching identity; Schneider, *Artificial You*.
- **Success looks like.** A position paper of about 3,000 words that states which account you hold (psychological, biological, no-self, further-fact), why, and what it implies for an emulated cat. Include the case against your own view. Revisit it annually; the weekly template's question "what changed my mind" applies most to this document.
- **Time.** 2 to 3 months.

### C3. Consciousness and substrate

- **Goal.** Decide how much weight to put on computational functionalism, which every pro-uploading argument assumes.
- **Read.** Chalmers, "Could a Large Language Model be Conscious?"; Butlin, Long et al. on indicator properties; Seth's biological-naturalism target article with a selection of the commentaries and his reply; Aru, Larkum and Shine; Schwitzgebel on substrate flexibility and on the audience problem; Birch on the gaming problem.
- **Success looks like.** A credence table: for each of (current LLMs, a connectome-plus-LIF fly emulation, a hypothetical compartmental cat emulation on GPUs, the same on neuromorphic hardware), your probability that it is conscious, the theory assumptions behind the number, and what evidence would shift it. Numbers with reasons, not numbers alone.
- **Time.** 2 to 3 months.

### C4. Animal minds, and one cat in particular

- **Goal.** Apply the best available method for assessing sentience to the domestic cat, and see where the evidence runs out.
- **Read.** The Cambridge and New York declarations; the LSE review of cephalopod and decapod sentience as a worked example; Birch, *The Edge of Sentience*; Merker's target article and commentaries; the feline primary papers in `docs/05-animal-consciousness-and-the-feline-mind.md` (name recognition, owner localisation, attachment, slow blink, grimace scale, grief surveys).
- **Success looks like.** The eight LSE criteria applied to the cat with a confidence level and a citation for each; a list of what is known about cats as a population versus what is known about any individual cat (the second list is very short, and that matters for the central question).
- **Time.** 1 to 2 months.

### C5. The ethics of emulation, and a protocol for your own work

- **Goal.** Decide what you owe to anything you simulate, before you simulate anything that could matter.
- **Read.** Sandberg, "Ethics of brain emulations"; Metzinger's moratorium proposal; Shulman and Bostrom on digital minds; Long, Sebo et al., "Taking AI Welfare Seriously"; Hanson, *The Age of Em*; Anthropic's model-welfare pages as a live case study.
- **Success looks like.** A written welfare protocol for this project: which classes of system you will run without review (a LIF fly, a reward-driven simulated arm), which trigger a pause and a reasoned assessment, which indicators you would look for, what "pause and preserve state" means for your systems, and what you would do if an indicator appeared. Keep it in `notes/` and apply it.
- **Time.** 1 to 2 months.

### C6. Self, no-self, and grief

- **Goal.** Read the views that dissolve the identity question, and the evidence on technologies that promise to soften loss.
- **Read.** Thompson, *Waking, Dreaming, Being*; Metzinger, *The Ego Tunnel*; Hollanek and Nowaczyk-Basinska on griefbots; the grief surveys in `docs/05-animal-consciousness-and-the-feline-mind.md` for what is known about animals' own grief.
- **Success looks like.** A short essay on what, if the self is a process rather than a thing, "the same cat" could and could not mean; and a decision, written down, about whether you will use any digital memorial technology and on what terms.
- **Time.** 4 to 6 weeks. There is no deadline on this one.

### C7. Keep current

- **Goal.** Stay ahead of the field's drift without drowning.
- **Read.** The Behavioral and Brain Sciences debate as it continues; the Association for the Scientific Study of Consciousness programme each year; the Digital Minds newsletter and Eleos AI's reports; Rodney Brooks's annual prediction scorecards; the Carboncopies journal clubs; the second Cogitate experiment and the He, Chalmers and Block collaboration when they report.
- **Success looks like.** The chapters in `docs/` stay accurate, with dated corrections.
- **Time.** Two to three hours a week, indefinitely.

## Milestones for the first 12 months

Months 1 to 3

- [ ] `notes/00-why-i-started.md` written, in your own words, before any other work
- [ ] Read the "Pets specifically" section of `docs/07-brain-preservation.md` and the opening of `docs/08-personal-identity-and-the-ethics-of-uploading.md` first, then the chapters in the README's suggested order (05, 06, 03, then 01 and 02), one paper note per chapter on the primary source that struck you most
- [ ] Linear algebra and probability refreshed to the self-check level
- [ ] A1 complete: a simulated quadruped you trained walks on rough terrain
- [ ] B1 complete: LIF, Hodgkin-Huxley and a Gabor simple/complex cell model, with plots
- [ ] C1 complete: two-page note on the grounding debate
- [ ] Twelve consecutive weekly reviews written

Months 4 to 6

- [ ] A2 complete: one open VLA evaluated on a standard suite and under perturbation, degradation table written
- [ ] SO-101 pair built, calibrated and teleoperating
- [ ] B2 complete: worm connectome disagreement report; fly and mouse datasets browsed
- [ ] B3 complete: fly whole-brain LIF model reproduced, one prediction confirmed, one assumption perturbed
- [ ] C2 draft: position paper on personal identity, including the cat case
- [ ] Welfare protocol (C5) drafted before any further simulation work, even if it only says "nothing here qualifies yet"
- [ ] At least 15 paper notes in `notes/papers/`

Months 7 to 9

- [ ] A3 complete: 50 demonstrations, a trained imitation policy, and a measured success rate on a held-out layout
- [ ] B4 complete: one Cogitate analysis reproduced from the open data
- [ ] B5 complete: Φ computed for a toy system, runtime-against-size plot, written view on digital hardware
- [ ] C3 complete: credence table with reasons
- [ ] C4 complete: LSE sentience criteria applied to the domestic cat
- [ ] First public contribution: a dataset, a replication report or a bug fix to an open tool

Months 10 to 12

- [ ] A4 complete: Dreamer agent learning from pixels; note on world models as hosts for virtual bodies
- [ ] A5 begun: curiosity-driven agent showing emergent developmental stages
- [ ] B6 complete: real units pulled from the brain-wide map; your own recording doubling-time fit
- [ ] B7 complete: scaling plots and a written cat-scale cost estimate with assumptions
- [ ] B8 complete: preservation-versus-requirements table and the one-page assessment
- [ ] C6 complete: essay on self and no-self; decision on memorial technology
- [ ] Year-one review: at least one belief about the central question changed and documented; `ROADMAP.md` and `OPEN-QUESTIONS.md` revised; at least three factual corrections made to chapters with sources; a single year-two contribution (B9 or A7) chosen

What not to expect in twelve months: a working emulation of anything larger than an insect, hardware beyond a desktop arm, a settled view on consciousness, or a settled grief. Expect instead to be able to read any paper in these nine chapters critically, to run most of their open code, and to know exactly which claims you believe and why.

## How the tracks connect to the central question

The central question has three parts, and they are answered by different kinds of evidence.

**Can a mind be emulated?** This is empirical and belongs to Track B. The honest state of the evidence in 2026 (`docs/06-whole-brain-emulation-and-connectomics.md`, `docs/09-recording-simulation-and-hardware.md`): complete wiring diagrams exist for a worm and a fly; a crude spiking model built on the fly connectome predicts some reflex-like behaviours; the mammalian frontier is one cubic millimetre, obtained destructively; a connectome omits synaptic weights, receptor composition, neuromodulatory state, glia, gene expression and plasticity, and nobody has shown these can be read from fixed tissue at scale; the worm, mapped for forty years, still has no emulation that predicts its behaviour. Compute is not the obstacle. Data is. A calibrated reading: insect-scale emulation of sensorimotor behaviour is plausible within a decade; a mouse is plausible in one to two decades if connectomics scales and the dynamics problem is solved; for a cat (roughly 250 million cortical neurons, perhaps 750 million in total) or a human there is no timeline the evidence supports.

**Would it need a body, and which one?** This is where Track A earns its place (`docs/01-embodied-cognition-foundations.md`, `docs/02-embodied-ai-state-of-the-art.md`). Everything known about cat cognition is sensorimotor: orienting to a name, locating a voice, returning a slow blink. If enactivism or sensorimotor contingency theory is even partly right, a brain emulation without a body of roughly the right morphology and sensory statistics would be a mind in a state no neuroscience has described, or not a mind at all. Track A teaches, by doing, how much of competence lives in the body and in the history of interaction with it, how expensive that history is to acquire, and what a virtual body would have to supply. It also keeps you honest about hype, because you will have watched your own policies fail on a slightly moved cup.

**Would it be the same mind, and would it be conscious?** The first is conceptual and belongs to Track C; the second is both conceptual and empirical and belongs to Tracks B and C together. On identity (`docs/08-personal-identity-and-the-ethics-of-uploading.md`), psychological and pattern views say a faithful emulation preserves everything that matters, animalism says it is a new individual whatever its fidelity, and no-self views say the question has no determinate answer; the copy problem shows that a destructive scan cannot be more identity-preserving than a non-destructive copy, and the non-destructive copy plainly leaves the original behind. On consciousness (`docs/03-science-of-consciousness.md`, `docs/04-machine-consciousness.md`), functionalist theories say a faithful emulation would be conscious, Integrated Information Theory says a digital emulation would not be, biological naturalism says it might depend on being alive, and the one preregistered adversarial test challenged both leading theories without choosing. There is no test that could tell a conscious emulation from a behaviourally perfect one that is not, and the emulation's own reports would carry little weight.

**What follows for an animal that has already died.** This is the question that started the project, and it deserves a direct answer (`docs/07-brain-preservation.md`, especially its "Pets specifically" section, the opening of `docs/08-personal-identity-and-the-ethics-of-uploading.md`, and `docs/05-animal-consciousness-and-the-feline-mind.md`).

- An animal whose brain was not preserved within hours of death cannot be emulated, uploaded or recovered by any known or foreseeable method. Memory, photographs, video, DNA and cloning preserve information about the animal, or produce a genetic twin with a different coat and a different life; none of them is the animal. Nothing in these nine chapters offers a route around this, and this roadmap will not pretend to.
- Even where a brain was preserved at the highest quality available, no memory has ever been decoded from preserved tissue, no preserved mammalian brain has been revived or emulated, and the probability that any brain preserved today is ever emulated with its memories intact is unknown and may be near zero.
- If, decades from now, an emulation of a preserved cat were built, the three views of identity would disagree about whether it was that cat, and all of them agree that the first question to settle would be whether it could suffer, not whether it was the same individual.
- What this programme can honestly offer is different: understanding of what a cat's mind was, as far as science can say (`docs/05-animal-consciousness-and-the-feline-mind.md`); a contribution to a field that is trying to find out whether preservation and emulation can ever be made real for animals and people who are still alive; and the discipline to keep grief from turning into credulity, which the README names as the point of the notebook.

Grief does not need the uncertainty resolved. The work does not need the grief to justify it. Keep them in separate notes and let both be true.
