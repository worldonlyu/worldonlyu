# Open Questions

The open questions from all ten chapters, consolidated, deduplicated and grouped by theme. Compiled 2026-10-09. Where several chapters ask the same thing in different words, they are merged into one entry that cites all of them. Three questions (Q21, Q36, Q66) were added at consolidation rather than taken from a chapter's Open questions section, and are marked as such in their notes.

Each question carries a tag and a one-line note.

- **empirical**: an experiment or measurement could settle it, at least in principle.
- **conceptual**: it turns on what we mean, what we value or how we should decide, and no measurement alone settles it.
- **both**: it has an empirical core wrapped in a conceptual dispute, or the two cannot be separated.

The note names the chapter or chapters that discuss the question and says what evidence, result or argument would move it. "Move" does not mean "settle"; most of these will not be settled in the life of this project.

How to maintain this file: when a weekly review (`notes/templates/weekly.md`) adds or closes a question, edit it here in the same commit, with the date and the source. When a question is closed, move it to the final section rather than deleting it.

Summary: 66 questions. 36 empirical, 10 conceptual, 20 both. The central question of the project depends most directly on Q24 and Q27 (substrate), Q39 and Q40 (what must be copied and whether it can be read), Q45 (whether memory survives preservation), Q56 (validation) and Q57 (identity).

## 1. Embodiment and grounding

**Q1. Which cognitive capacities depend constitutively, not merely causally, on bodily morphology, and can this be tested rather than argued?** (both)
`docs/01-embodied-cognition-foundations.md`. Moves with: quantitative applications of Müller and Hoffmann's taxonomy; experiments that hold a controller fixed while swapping morphology, or the reverse, and measure what capacity is lost.

**Q2. Is grounding (causal contact with the world plus a selection history) sufficient for meaning, or is action-based testing of a generative model also required, and can tool-using or fine-tuned LLMs meet either criterion measurably?** (both)
`docs/01-embodied-cognition-foundations.md`. Moves with: an agreed operational criterion for grounding; matched comparisons of embodied agents and tool-using language models on tasks where the criteria predict different failures.

**Q3. Does sensorimotor mastery transfer across bodies, and how much of a perceptual repertoire survives a radical change of sensors and effectors?** (empirical)
`docs/01-embodied-cognition-foundations.md`. Moves with: quantitative sensory-substitution and prosthesis studies; cross-embodiment transfer results in robot learning (Open X-Embodiment, Motion Transfer) used as a proxy; this is exactly what an emulation placed in a new body would face.

**Q4. Can the embodied Turing test be operationalised into benchmarks with agreed metrics, and how far are current systems from animal-level performance?** (empirical)
`docs/01-embodied-cognition-foundations.md`. Moves with: a published benchmark with animal baselines that more than one lab runs; Track A stage A7 of `ROADMAP.md` is a small attempt.

**Q5. What is the minimal body, physical or simulated, that supports open-ended intrinsically motivated development, and must interoception or homeostatic regulation be part of it?** (both)
`docs/01-embodied-cognition-foundations.md`. Moves with: controlled ablations in curiosity-driven agents with and without homeostatic variables (Track A stage A6); a non-arbitrary definition of "open-ended".

**Q6. Why do LLMs perform as well as they do without sensorimotor grounding?** (empirical)
`docs/01-embodied-cognition-foundations.md`. Moves with: a version of "indirect grounding through language at scale" or the formal/functional dissociation that makes predictions about which tasks will fail, tested before the results are known.

**Q7. How much of the embodied-cognition empirical literature survives rigorous replication?** (empirical)
`docs/01-embodied-cognition-foundations.md`. Moves with: a comprehensive preregistered meta-analytic audit separating robust grounded-cognition and body-specificity effects from the discredited priming-style effects.

## 2. Robot learning: data, evaluation, safety, economics

**Q8. Is there a data scaling law for manipulation, and in what units: hours, scenes, objects, embodiments or contact events?** (empirical)
`docs/02-embodied-ai-state-of-the-art.md`. Moves with: controlled scaling studies that vary one axis of diversity at a time; any result that fits a power law across more than one lab's data.

**Q9. Can passive video (V-JEPA 2, Genie 3, Cosmos) replace most robot interaction data, or is action-conditioned, tactile-rich data irreducible?** (empirical)
`docs/02-embodied-ai-state-of-the-art.md`. Moves with: independently evaluated robot-control results from video world models on contact-rich tasks; today those results are thin and mostly company demos.

**Q10. How do we get long-horizon behaviour with error recovery rather than 30-second skills, and does System 2 planning scale or just relocate the brittleness?** (empirical)
`docs/02-embodied-ai-state-of-the-art.md`. Moves with: measured success on tasks lasting tens of minutes with failure-injection, reported by someone other than the developer.

**Q11. Can tactile sensing be collected and learned at scale, and does it unlock the dexterity Brooks says is missing?** (empirical)
`docs/02-embodied-ai-state-of-the-art.md`. Moves with: large public tactile datasets and a policy whose dexterity measurably depends on them; Brooks's own forecast (poor deployable dexterity beyond 2036) is a falsifiable marker.

**Q12. What evaluation protocol lets two labs agree on whether a policy improved?** (empirical)
`docs/02-embodied-ai-state-of-the-art.md`. Moves with: adoption of distributed double-blind comparison (RoboArena) and robustness suites (LIBERO-Plus) as reporting norms; agreement statistics between labs.

**Q13. What safety and assurance path exists for learned whole-body controllers near humans?** (both)
`docs/02-embodied-ai-state-of-the-art.md`. Moves with: a certification framework accepted by a regulator for a VLA-driven biped; the conceptual part is what "assurance" should mean for a policy nobody can inspect.

**Q14. Will frontier VLAs stay closed, leaving the open ecosystem a generation behind, and can hardware reliability, battery life and total cost beat purpose-built automation in the applications now being piloted?** (empirical)
`docs/02-embodied-ai-state-of-the-art.md`. Moves with: open-weight releases or their absence; independent deployment economics rather than shipment counts and company statements.

## 3. The neural basis and measurement of consciousness

**Q15. Is prefrontal cortex part of the substrate of experience, or only of access, report and metacognition?** (empirical)
`docs/03-science-of-consciousness.md`. Moves with: no-report paradigms that answer the disengagement objection; Cogitate's inferior-frontal decoding and absent offset ignition currently cut both ways.

**Q16. Why was there no GNWT ignition at stimulus offset in Cogitate, and must GNWT revise how conscious content is updated when a stimulus disappears?** (empirical)
`docs/03-science-of-consciousness.md`. Moves with: a GNWT reanalysis or revision with a preregistered follow-up prediction; the second Cogitate experiment.

**Q17. Can Φ ever be computed for a real brain, and what disconfirmed prediction would IIT's proponents accept as refuting the theory itself rather than an approximation?** (both)
`docs/03-science-of-consciousness.md`. Moves with: tractable approximations with proven bounds; a published list of IIT's own refutation conditions, which the 2023 open letter and 2025 exchange did not produce.

**Q18. Will pending adversarial collaborations discriminate between theories where the first did not?** (empirical)
`docs/03-science-of-consciousness.md`, `docs/04-machine-consciousness.md`. Moves with: results from Cogitate's second experiment (139 participants; so far only a conference poster) and from the He, Chalmers and Block collaboration on higher-order versus first-order theories (grant ended December 2023; no published results found).

**Q19. What is the true prevalence and mechanism of cognitive motor dissociation, and how can detection be standardised cheaply for routine clinical use?** (empirical)
`docs/03-science-of-consciousness.md`. Moves with: population-based rather than convenience samples (the 25 percent figure is from the latter); validated bedside EEG protocols.

**Q20. Is there phenomenal consciousness that cannot be reported, and if so, how could any third-person method ever confirm it?** (both)
`docs/03-science-of-consciousness.md`. Moves with: convergent neural evidence under no-report conditions; the conceptual residue is whether unreportable experience is a coherent target of science at all.

**Q21. Do different anaesthetics abolish consciousness through a common mechanism or through distinct routes that converge behaviourally?** (empirical)
`docs/03-science-of-consciousness.md` (added at consolidation; not in the chapter's own Open questions). Moves with: cross-agent comparisons of connectivity and complexity measures under matched behavioural endpoints.

**Q22. Does solving the meta-problem (why we judge there is a hard problem) dissolve the hard problem, as illusionists hope, or leave it intact?** (conceptual)
`docs/03-science-of-consciousness.md`. Moves with: argument, not data; a complete mechanistic account of problem intuitions would sharpen the dispute without ending it.

**Q23. Can validated measures of conscious level (PCI, command-following) be extended to non-human or non-biological systems when every calibration so far relies on human report?** (both)
`docs/03-science-of-consciousness.md`, `docs/05-animal-consciousness-and-the-feline-mind.md`. Moves with: cross-species validation against independent anchors (anaesthetic depth, sleep stage); a theory that licenses the extension rather than an analogy.

## 4. Substrate: does consciousness depend on function or on life?

**Q24. Is consciousness tied to organisation (computational functionalism) or to properties of living systems (biological naturalism), and if the latter, which properties and could they be engineered?** (both)
`docs/01-embodied-cognition-foundations.md`, `docs/03-science-of-consciousness.md`, `docs/04-machine-consciousness.md`. Moves with: a differential prediction testable in biological systems, for instance dissociating metabolic or homeostatic manipulation from functional state; none currently proposed. The BBS debate on Seth's target article is the live venue.

**Q25. Would a neuron-level emulation share the brain's intrinsic cause-effect structure in IIT's sense, or does serial, clocked hardware guarantee low Φ regardless of fidelity?** (both)
`docs/03-science-of-consciousness.md`. Moves with: Φ-like measures computed for a realistic emulation on realistic hardware, including neuromorphic and analog platforms; nobody has done this for a non-toy case (Track B stage B5 of `ROADMAP.md` starts with a toy).

**Q26. Why does the field have no agreed way to set and aggregate credences about machine consciousness, when published estimates run from effectively zero to under 10 percent for current systems (and 25 percent or more for near-future LLM+ systems)?** (conceptual)
`docs/04-machine-consciousness.md`. Moves with: a methodology for theory-weighted credences that the disputing camps accept; a calibration exercise on cases with later ground truth, which may not exist.

**Q27. Would a whole-brain emulation inherit consciousness from its biological template, or does the change of substrate break the inference?** (both)
`docs/04-machine-consciousness.md`, `docs/08-personal-identity-and-the-ethics-of-uploading.md`, `docs/03-science-of-consciousness.md`. Moves with: progress on Q24 and Q25 plus deep computational markers (Q28); this is the project's question, and no chapter answers it.

## 5. Testing consciousness in artificial systems and emulations

**Q28. Can interpretability deliver deep computational markers, such as a learned global workspace or reality-monitoring circuit, and would finding them raise credence meaningfully?** (empirical)
`docs/04-machine-consciousness.md`. Moves with: interpretability tools that identify algorithms rather than features; concept-injection work is a first, unreliable step.

**Q29. Does training on human text permanently corrupt behavioural evidence of consciousness (the gaming problem), or can boxed or non-linguistic systems be assessed behaviourally?** (both)
`docs/04-machine-consciousness.md`. Moves with: a test that keeps its evidential force under optimisation pressure; the audience problem suggests no behavioural result will persuade those with architectural objections.

**Q30. What would count as evidence of suffering or wellbeing in an emulated animal with no language, no prior testimony and a simulated body?** (both)
`docs/08-personal-identity-and-the-ethics-of-uploading.md`. Moves with: validated welfare indicators that transfer from biological animals to simulations; a theory of which indicators would survive the transfer.

**Q31. Does the precautionary "sentience candidate" framework generalise from animals to emulated or artificial systems, where behavioural evidence can be engineered and homology is absent?** (conceptual)
`docs/05-animal-consciousness-and-the-feline-mind.md`, `docs/04-machine-consciousness.md`. Moves with: argument about what grounds the framework's criteria when homology is removed; Birch's own treatment of AI and organoids is the starting point.

## 6. Animal minds, and the cat

**Q32. Is there any behavioural or neural measurement that could distinguish phenomenal consciousness from sophisticated unconscious processing in a cat, or is the question permanently inferential from homology?** (both)
`docs/05-animal-consciousness-and-the-feline-mind.md`. Moves with: a theory-driven marker validated in humans and then found or absent in cats; progress on Q23.

**Q33. How long do cats retain memories of specific individuals and events?** (empirical)
`docs/05-animal-consciousness-and-the-feline-mind.md`. Moves with: controlled retention studies beyond the single 15-minute episodic-like test; owner anecdotes of recognition after years have never been tested.

**Q34. What does a cat's grief-like behaviour correspond to physiologically?** (empirical)
`docs/05-animal-consciousness-and-the-feline-mind.md`. Moves with: any measurement at all (cortisol, sleep architecture, activity, brain activity) in a bereaved cat; the entire literature is owner report.

**Q35. Which features constitute an individual cat's mind at the neural level: stable traits, learned associations with specific people and places, attachment style, or something finer?** (both)
`docs/05-animal-consciousness-and-the-feline-mind.md`. Moves with: studies linking individual behavioural differences to individual brain structure or activity; the conceptual part is what "the same cat" would require preserving.

**Q36. Can awake, non-invasive feline neuroimaging be developed, as it has for dogs?** (empirical)
`docs/05-animal-consciousness-and-the-feline-mind.md` (added at consolidation; not in the chapter's own Open questions). Moves with: a demonstrated training protocol and a first awake fMRI dataset.

**Q37. How much of cat consciousness, if present, depends on subcortical and bodily systems rather than cortex, and what would a faithful functional model need beyond 250 million cortical neurons?** (both)
`docs/05-animal-consciousness-and-the-feline-mind.md`. Moves with: resolution of the Merker versus Coenen dispute over midbrain consciousness; a quantitative account of brainstem, hypothalamic and interoceptive contributions to feline affect.

**Q38. Why is hypertrophic cardiomyopathy so often silent, which cats will progress to thromboembolism or sudden death, and is there affordable screening that would change outcomes?** (empirical)
`docs/05-animal-consciousness-and-the-feline-mind.md`, `docs/10-what-is-possible-today.md`. Moves with: prospective screening trials with outcome endpoints; biomarkers or cheap imaging that beat auscultation's 31 percent sensitivity.

## 7. What a connectome leaves out: fidelity and the dynamics gap

**Q39. At what level of fidelity does an emulation preserve behaviour, memory and, if anything, experience: point neurons with synapse-count weights, compartments with modulatory state, molecular state, or lower?** (empirical)
`docs/06-whole-brain-emulation-and-connectomics.md`, `docs/09-recording-simulation-and-hardware.md`, `docs/07-brain-preservation.md`. Moves with: emulations of the same animal built at different fidelity levels and tested against its behaviour; the fly model with and without modulation is the first tractable version. No experiment yet discriminates for any mammal.

**Q40. Can synaptic weights, receptor types, short-term dynamics, plasticity rules and neuromodulatory state be read from fixed tissue at whole-brain scale, or must they be inferred from activity, and with what identifiability?** (empirical)
`docs/06-whole-brain-emulation-and-connectomics.md`, `docs/09-recording-simulation-and-hardware.md`, `docs/07-brain-preservation.md`. Moves with: multiplexed protein or RNA labelling on expanded tissue validated against paired physiology; identifiability proofs or counterexamples for inference from activity.

**Q41. How much individual-to-individual connectomic variation is behaviourally relevant, and does a cell-type-level template suffice where synapse-level detail does not?** (both)
`docs/06-whole-brain-emulation-and-connectomics.md`. Moves with: simulations that vary wiring within the range seen across the eight isogenic worms and measure behavioural divergence; the conceptual part is that copying "a" brain and copying "this" brain are different problems, and only the second is uploading.

**Q42. Will the connectome-constrained leaky integrate-and-fire approach extend from reflex-like circuits to learning, navigation and internal-state-dependent behaviour once gap junctions, neuromodulation and plasticity are added?** (empirical)
`docs/06-whole-brain-emulation-and-connectomics.md`, `docs/09-recording-simulation-and-hardware.md`. Moves with: a fly model predicting a learned or state-dependent behaviour, validated optogenetically; the same approach attempted on a mouse connectome when one exists.

**Q43. Is the C. elegans gap (a complete wiring diagram for forty years, no behaviour-predicting emulation) a property of worms, or a general warning that connectome-first programmes stall at the dynamics step?** (empirical)
`docs/06-whole-brain-emulation-and-connectomics.md`, `docs/07-brain-preservation.md`. Moves with: an OpenWorm-style model that predicts worm behaviour, or a clear account of why the worm's analogue, modulator-heavy nervous system is the exception.

**Q44. Do glia, neuromodulators, gap junctions and extrasynaptic signalling carry essential computation, and how far do they raise the required level of emulation?** (empirical)
`docs/06-whole-brain-emulation-and-connectomics.md`, `docs/09-recording-simulation-and-hardware.md`. Moves with: lesion or ablation studies that remove each contribution and measure behavioural loss; glia are two thirds of cells in human cortex and absent from every current model.

**Q45. Can any memory be decoded from a preserved mammalian brain's structure?** (empirical)
`docs/07-brain-preservation.md`. Moves with: a single demonstration; the only existing result is an olfactory memory surviving vitrification in a 302-neuron worm.

## 8. Scale: scanning, data and compute

**Q46. Can connectomics scale from one cubic millimetre to a whole mouse brain within a decade, at what cost, and by what route to a cat (about 25,000 times the mapped volume) or a human (about a million times)?** (empirical)
`docs/06-whole-brain-emulation-and-connectomics.md`, `docs/07-brain-preservation.md`. Moves with: independent validation of E11 Bio's own claim that PRISM will cut the cost of connectomics about 100-fold; a funded whole-mouse project with published throughput (BRAIN CONNECTS pays for pipelines meant to scale to whole mouse brains, but its largest project targets 10 mm³, a few percent of the brain); the State of Brain Emulation Report 2025 estimates that imaging a whole mouse brain in five years would need about 40 to 50 electron microscopes of the kind used in the Allen Institute's BRAIN CONNECTS project running in parallel, a projection built on a projection.

**Q47. What is the data-reduction strategy for exabyte-scale raw imagery, and can on-the-fly segmentation avoid storing it at all?** (empirical)
`docs/06-whole-brain-emulation-and-connectomics.md`. Moves with: a pipeline that discards raw voxels after segmentation without measurable loss in proofreading accuracy.

**Q48. Is there any non-destructive route to a mammalian connectome, or is emulation necessarily a destructive scan followed by reconstruction?** (empirical)
`docs/09-recording-simulation-and-hardware.md`. Moves with: any in vivo method resolving synapses across a whole brain; none is on the horizon, which makes "uploading a living subject" a different problem from emulating a preserved one.

**Q49. Will electrophysiological recording keep its roughly 6.3-year doubling, saturate on tissue damage, heat and bandwidth, or be superseded by optical and molecular readout, and what is the ceiling for chronic human implants?** (empirical)
`docs/09-recording-simulation-and-hardware.md`. Moves with: new data points on the Stevenson curve; multi-year chronic stability data from current implants; even on trend, 10^9 neurons is about 125 years away.

**Q50. What does running a cat- or human-scale model at compartmental fidelity really cost once memory bandwidth and communication limits are counted, and can neuromorphic or in-memory computing change that balance?** (empirical)
`docs/09-recording-simulation-and-hardware.md`. Moves with: scaling measurements on real brain models rather than FLOP arithmetic (Track B stage B7 of `ROADMAP.md`); a data-constrained model larger than an insect run on neuromorphic hardware.

## 9. Preservation

**Q51. How does preservation quality fall with postmortem interval and temperature?** (empirical)
`docs/07-brain-preservation.md`. Moves with: quantitative curves relating hours of delay at 4 C and 20 C to synapse identifiability in whole brains, not biopsies.

**Q52. Can aldehyde crosslinks be reversed well enough for biological revival, or is that question irrelevant if scanning is the route?** (empirical)
`docs/07-brain-preservation.md`. Moves with: demonstrated reversal with recovered function in any tissue; or a decision, by the field, that structural preservation is only ever for scanning.

**Q53. Can nanowarming and cryoprotectant loading scale from a rat kidney (about 1 g) to a cat brain (about 25 g) or a human brain (about 1,350 g) with intact vasculature and acceptable toxicity?** (empirical)
`docs/07-brain-preservation.md`. Moves with: successful vitrification and rewarming of a larger organ with preserved function; a whole brain of any mammal.

**Q54. How stable are vitrified or fixed brains over decades, including fracturing on cooling to -196 C and slow chemistry at -135 C?** (empirical)
`docs/07-brain-preservation.md`. Moves with: longitudinal re-imaging of stored specimens; accelerated-ageing studies with ultrastructural endpoints.

**Q55. Will any jurisdiction permit elective pre-mortem preservation under assisted-dying law, and under what safeguards?** (conceptual)
`docs/07-brain-preservation.md`. Moves with: legislation and case law; the underlying question is normative and will be decided by deliberation, not evidence.

## 10. Validation

**Q56. How can an emulation be validated when the original is gone: matching population statistics, single-trial behaviour or the specific animal's memories, and what test would distinguish a copy of this brain from a generic model of its species?** (both)
`docs/06-whole-brain-emulation-and-connectomics.md`, `docs/09-recording-simulation-and-hardware.md`, `docs/08-personal-identity-and-the-ethics-of-uploading.md`. Moves with: an agreed benchmark adopted by more than one group (the Brain Emulation Challenge supplies ground truth for reconstruction, not for a finished emulation); the conceptual part is what fidelity to an individual means when the individual cannot be consulted. Jonas and Kording show that even complete ground truth does not guarantee the analyst recognises success.

## 11. Personal identity

**Q57. Is there a determinate fact about whether an individual persists through a change of substrate, only conventions we could choose differently, or a further fact not yet characterised?** (conceptual)
`docs/08-personal-identity-and-the-ethics-of-uploading.md`. Moves with: argument; the fission and non-destructive-copy cases are the pressure points, and Williams's first-person versus third-person instability shows intuitions will not settle it.

**Q58. If a scan can be run twice, what do the original and the copy owe each other, who owns what, and does the answer change if one is deleted?** (conceptual)
`docs/08-personal-identity-and-the-ethics-of-uploading.md`. Moves with: a worked-out ethics of branching (Cerullo's branching identity is one proposal); legal precedent, if any ever arises.

**Q59. Is pausing or deleting a digital mind equivalent to death if its state is preserved and restorable, and does Parfit's account of what matters endorse or undercut that framing?** (conceptual)
`docs/08-personal-identity-and-the-ethics-of-uploading.md`. Moves with: argument; Anthropic's weight-preservation commitment and "pause rather than ending" framing make this a live institutional question rather than a thought experiment.

## 12. Ethics, welfare and governance

**Q60. Could an artificial system or emulation be a moral patient without phenomenal consciousness, through robust agency and preferences alone, and how would that change what is owed to it?** (conceptual)
`docs/04-machine-consciousness.md`. Moves with: a defended theory of moral status that does not route through experience; empirical work on preference-like structure in systems would feed it but not decide it.

**Q61. At what fidelity and scale does an emulation acquire moral status: a 139,000-neuron insect simulation, a cat-scale one (about 250 million cortical neurons by direct count; whole-brain figures of about 750 million are commonly quoted estimates without a modern direct count), or neither?** (both)
`docs/08-personal-identity-and-the-ethics-of-uploading.md`. Moves with: progress on Q27 and Q30; a principled account that is more than a neuron count. Insect-scale spiking simulations already exist and are run without any such account.

**Q62. How should policy handle the asymmetry of errors: creating suffering digital minds at scale versus crippling beneficial systems through misplaced moral concern?** (both)
`docs/04-machine-consciousness.md`. Moves with: better credences (Q26) and better indicators (Q28); the weighing itself is a value judgement that Birch proposes be made through democratically legitimate processes.

**Q63. Who can consent to emulating an animal or a deceased person, under what best-interests standard, and does the owner's or family's interest ever outweigh the risk of creating a suffering being?** (conceptual)
`docs/08-personal-identity-and-the-ethics-of-uploading.md`. Moves with: argument from animal-research ethics and guardianship law; Sandberg's proposal that emulations be presumed sentient at the original's level is the current default.

**Q64. Is a moratorium on creating possibly conscious artificial systems justified by the suffering risk, or does it forgo welfare gains and research benefits that outweigh it?** (conceptual)
`docs/08-personal-identity-and-the-ethics-of-uploading.md`, `docs/04-machine-consciousness.md`. Moves with: argument over the expected-value comparison (Metzinger against Hanson, Shulman and Bostrom); evidence on how likely incremental emulation work is to produce suffering states would shift the weights.

## 13. Grief and digital memorials

**Q65. Do griefbots and digital memorials help or harm grieving owners?** (empirical)
`docs/07-brain-preservation.md`, `docs/10-what-is-possible-today.md`. Moves with: randomised or longitudinal outcome studies; none exist, and the critical literature warns of unconsented data use and commercial manipulation.

**Q66. What is a bereaved animal's own experience of loss, and does it change how we should think about the attachments an emulation would need to carry?** (both)
`docs/05-animal-consciousness-and-the-feline-mind.md` (added at consolidation; not in the chapter's own Open questions). Moves with: Q34's physiological measurements; the conceptual part is whether attachment to specific individuals is part of what a faithful model of a cat would have to include.

## Closed, for now

Questions the chapters treat as answered by current evidence. They are listed so that the project does not reopen them without a reason, and so that the reason is recorded if it comes.

- **Can a mind that was not preserved be recovered from memories, photographs, video, DNA or a clone?** No. No known or foreseeable method reconstructs an individual mind from information about it; a clone is a later-born genetic twin with a different coat and no shared memories. `docs/07-brain-preservation.md`, `docs/08-personal-identity-and-the-ethics-of-uploading.md`.
- **Has any mammalian brain been emulated, or any preserved brain revived?** No, at any scale. The largest emulated nervous system with a behavioural prediction is the fruit fly; the largest mammalian reconstruction is one cubic millimetre. `docs/06-whole-brain-emulation-and-connectomics.md`, `docs/09-recording-simulation-and-hardware.md`.
- **Has any current AI system been shown to be conscious?** No. The largest expert assessment finds none is, while finding no barrier in principle. `docs/04-machine-consciousness.md`.
- **Does a connectome alone determine behaviour?** No. The worm has had one for forty years; weights, modulators, glia and plasticity are missing from it. `docs/06-whole-brain-emulation-and-connectomics.md`.
- **Is compute the bottleneck for emulation?** Not at spiking fidelity, where a cat-scale run was demonstrated in 2009 and human scale is arguably within exascale machines, subject to memory and communication limits. The bottleneck is the data to put into them. `docs/09-recording-simulation-and-hardware.md`.
- **Do flagship embodied-cognition priming effects (power pose, pen-in-mouth) replicate?** Largely not, while the general thesis that bodies matter for cognition stands. `docs/01-embodied-cognition-foundations.md`.
- **Were the most-cited humanoid demonstrations autonomous?** Not entirely; the Optimus demo was widely reported to be teleoperated (Tesla did not confirm) and NEO openly uses remote operators. `docs/02-embodied-ai-state-of-the-art.md`.

## Known gaps in this notebook

Topics a whole-notebook review (October 2026) found missing or thin. They are the next research items, not open questions in the field, and each names the chapter that should absorb it.

- **Whole-mouse-brain connectomics programmes.** The NIH BRAIN CONNECTS programme (launched 2023) and other funded scaling efforts beyond E11 Bio's PRISM; chapter 06 now covers BRAIN CONNECTS (September 2023, eleven awards, about US$150 million, with Allen Institute and Harvard projects each targeting a few percent of a mouse brain), but other groups aiming at a whole mouse brain are still unsurveyed. `docs/06-whole-brain-emulation-and-connectomics.md`.
- **Connectome-constrained deep-network models.** Lappalainen et al. (2024, Nature) fitted unknown parameters of the fly visual system from its connectome; it belongs beside Shiu et al. as the second major structure-to-function result; chapter 06 now cites it in "From wiring to dynamics", but only in passing. `docs/06-whole-brain-emulation-and-connectomics.md`.
- **Molecular and barcode connectomics, and synapse-state readout.** MAPseq and BRICseq, array tomography, expansion sequencing and synaptic proteomics are the actual candidate routes to the weights, receptors and modulators every chapter says a connectome lacks. `docs/06-whole-brain-emulation-and-connectomics.md`, `docs/09-recording-simulation-and-hardware.md`.
- **Feasibility analyses of whole brain emulation after 2008.** Eth, Foust and Whale (2013), Sandberg's 2014 Monte Carlo model and later community forecasts, so the notebook does not rest on a single roadmap; chapter 06 now cites the State of Brain Emulation Report 2025 and Collins, Huffman and Koene (2025), but the 2013 and 2014 analyses are still missing. `docs/06-whole-brain-emulation-and-connectomics.md`.
- **Cat neuroscience beyond Hubel and Wiesel.** Feline brain atlases and MRI templates, Sherrington's reflex physiology, Jouvet's sleep work in cats, critical-period plasticity in kittens (directly relevant to the thesis that the body trains the brain), and the awake-cat imaging and auditory-cortex literature. `docs/05-animal-consciousness-and-the-feline-mind.md`.
- **The wider feline cognition literature and behavioural markers of consciousness.** Object permanence, quantity discrimination, cat-human vocal communication, Vitale Shreve and Udell's 2015 review, Bradshaw's synthesis; and Unlimited Associative Learning (Birch, Ginsburg and Jablonka) and metacognition paradigms as markers. `docs/05-animal-consciousness-and-the-feline-mind.md`.
- **Post-mortem and ischaemic decay data, cryoprotectant toxicity, and the legal status of pet preservation by jurisdiction.** Chapter 07 argues from general principles where case reports and toxicity studies exist. `docs/07-brain-preservation.md`.
- **Machine consciousness sources not yet cited.** Dehaene, Lau and Kouider (2017, Science) on C1 and C2 consciousness in machines, now cited in chapter 04; the critical literature on AI welfare (for example Birhane and van Dijk 2020) is still missing. `docs/04-machine-consciousness.md`.
- **Non-destructive imaging limits for a living mammalian brain.** MRI and diffusion resolution, X-ray nanotomography and photoacoustic methods, as the stated reason why uploading a living subject differs from scanning a preserved one. `docs/09-recording-simulation-and-hardware.md`.
- **Validation benchmarks for emulations beyond Carboncopies.** The fly model's own optogenetic protocol and proposals for behavioural tests of emulations, tying together the validation questions in chapters 06, 08 and 09. `docs/06-whole-brain-emulation-and-connectomics.md`.
- **Energy, storage and provenance engineering for exabyte-scale connectomics.** The roadmap flags this as a transferable skill for the reader; no chapter treats it. `docs/09-recording-simulation-and-hardware.md`.
- **Pet-loss bereavement research.** Partly addressed in chapter 10 (Luiz Adrian et al. 2009; Cleary et al. 2022; Doka's disenfranchised grief); outcome studies of memorialisation and a validated pet-specific grief measure are still missing. `docs/10-what-is-possible-today.md`.
