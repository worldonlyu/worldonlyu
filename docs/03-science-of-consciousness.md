# The Science of Consciousness: Theories, Evidence, Measurement

> Consciousness science separates an empirical question, which brain processes are necessary and sufficient for experience and how to measure them, from a philosophical one, why any physical process is accompanied by experience at all. The empirical programme has two solid results: cortical complexity measures that track conscious level through anaesthesia, sleep and brain injury, and imaging methods showing that about a quarter of behaviourally unresponsive patients in one large cohort could follow commands covertly. It has not produced a winning theory. The first preregistered adversarial test of the two front-runners, Global Neuronal Workspace Theory and Integrated Information Theory, challenged key predictions of both, and a public dispute over whether IIT is science at all has divided the field. This chapter maps the theories, evidence and measurement tools, then states what each implies for an emulated brain. The theories disagree on exactly the point that matters most here: whether consciousness depends on what a system computes or on what it is made of.

## Why this matters for the project

Every theory of consciousness gives a different verdict on whole-brain emulation, and no experiment yet adjudicates between them. Computational-functionalist theories (Global Neuronal Workspace, higher-order theories, Attention Schema Theory, most predictive-processing accounts) hold that consciousness depends on what information is broadcast, represented or modelled, so a faithful functional emulation would be conscious. Butlin and colleagues made this operational: under an explicit functionalist assumption they derived "indicator properties" from these theories, found that no current AI system satisfies them, and saw no obvious barrier in principle [Butlin et al., 2023](https://arxiv.org/abs/2308.08708). Integrated Information Theory says the opposite for digital hardware: a brain simulated on a serial, clocked machine has an intrinsic cause-effect structure nothing like the brain's, so its Φ would be negligible and it would be a behaviourally perfect "zombie" [Albantakis et al., 2023](https://doi.org/10.1371/journal.pcbi.1011465); [Tononi et al., 2025](https://doi.org/10.1038/s41593-025-01880-y). Seth's beast-machine view adds that if selfhood is grounded in interoceptive regulation of a living body, an emulation with no homeostatic stakes may lack it. Illusionism dissolves the question without comfort: there is nothing phenomenal to transfer.

Three facts make this harder than it looks. First, the one completed adversarial test challenged both front-running theories, so no theory is empirically privileged [Cogitate Consortium, 2025](https://www.nature.com/articles/s41586-025-08888-1). Second, every validated measure of consciousness is calibrated on human brains against human report [Casali et al., 2013](https://doi.org/10.1126/scitranslmed.3006294); [Bodien et al., 2024](https://doi.org/10.1056/NEJMoa2400645), and says nothing directly about a simulation. The same gap applies to a non-human animal, which could never have reported; any conclusion about an emulated animal mind rests on an inductive leap from human calibration. Third, behavioural fidelity would not settle the matter: Attention Schema Theory and illusionism both predict that a system can sincerely insist it is conscious as the output of a self-model, whether or not anything phenomenal is present [Webb and Graziano, 2015](https://www.frontiersin.org/articles/10.3389/fpsyg.2015.00500/pdf); [Chalmers, 2018](https://researchportalplus.anu.edu.au/en/publications/the-meta-problem-of-consciousness/). So: treat the consciousness of any emulation as open, do not assume functionalism is established, and design for theory-neutral measurement wherever one exists.

## Key ideas

**Hard problem and meta-problem.** Chalmers' hard problem asks why physical processes give rise to subjective experience at all, as distinct from the "easy" problems of explaining discrimination, report and attention. His 2018 meta-problem asks why we judge that there is a hard problem. It is tractable by ordinary cognitive science and is shared ground between realists, who treat experience as real, and illusionists, who think only the intuition needs explaining [Chalmers, 2018](https://researchportalplus.anu.edu.au/en/publications/the-meta-problem-of-consciousness/).

**Neural correlates of consciousness (NCC), level, content and report.** The NCC is the minimal set of neural events jointly sufficient for a specific percept (content) or for being conscious at all (level). Clinical tools target level; most theory tests target content. The chronic confound is that activity related to reporting an experience can masquerade as activity related to having it. No-report paradigms try to strip that out [Tsuchiya et al., 2015](https://pubmed.ncbi.nlm.nih.gov/26585549/), but critics argue they may not isolate experience either.

**Global Neuronal Workspace Theory (GNWT) and ignition.** Dehaene, Changeux and Naccache's neural version of Baars' global workspace: a representation becomes conscious when it triggers a sudden, self-sustaining "ignition" of a long-range frontoparietal network that broadcasts it to many processors. Prefrontal cortex is central, and ignition is predicted at both stimulus onset and offset [Mashour et al., 2020](https://pmc.ncbi.nlm.nih.gov/articles/PMC8770991/).

**Integrated Information Theory (IIT), Φ and IIT 4.0.** Tononi's theory that consciousness is identical to a system's irreducible intrinsic cause-effect structure: Φ is its quantity, the structure's shape its quality. IIT pairs axioms about experience with postulates about the physical substrate; IIT 4.0 (2023) revised both, introduced a unique intrinsic-information measure and made causal relations explicit [Albantakis et al., 2023](https://doi.org/10.1371/journal.pcbi.1011465). Substrate matters: a digital simulation of a brain need not be conscious.

**Higher-order theories (HOT).** On the accounts of Rosenthal, Lau and Brown, a first-order sensory state is conscious only when targeted by a suitable higher-order representation, typically linked to prefrontal metacognitive circuits. Proponents stress that the requirement is far lighter than full metacognition [Brown et al., 2019](https://pure.skku.edu/en/publications/understanding-the-higher-order-approach-to-consciousness/). Two variants, HOROR and Perceptual Reality Monitoring (PRM), are under adversarial test.

**Recurrent Processing Theory (RPT) and the posterior hot zone.** Lamme's first-order theory holds that recurrent interactions within sensory cortex are necessary and sufficient for experience, even without global access or reportability, implying phenomenal "overflow" beyond what can be reported [Lamme, 2006](https://www.dare.uva.nl/id/fcb7629f-6d56-4a07-bf82-e7e71ecbc52b). IIT and RPT both place human conscious content in a posterior "hot zone" rather than prefrontal cortex: the "front versus back" dispute.

**Attention Schema Theory (AST).** Graziano's proposal that the brain builds a simplified model of its own attention, analogous to the body schema, and that this model's content leads the system to believe and report that it is aware. Webb and Graziano's 2015 paper is a mechanistic statement of a theory Graziano had proposed earlier; treating consciousness claims as model outputs makes it directly implementable [Webb and Graziano, 2015](https://www.frontiersin.org/articles/10.3389/fpsyg.2015.00500/pdf).

**Predictive processing and illusionism.** Seth treats perception as Bayesian "controlled hallucination" and grounds selfhood in interoceptive prediction that keeps a living body alive, the "beast machine"; he reframes the hard problem as a "real problem" of mapping mechanisms onto phenomenology and doubts that computation alone yields consciousness. Dennett's multiple drafts model and Frankish's 2016 illusionism go further: there is no phenomenal consciousness to explain, only the conviction that there is.

**Perturbational Complexity Index (PCI) and cognitive motor dissociation (CMD).** PCI stimulates cortex with TMS and compresses the EEG response with a Lempel-Ziv algorithm; high values indicate integrated yet differentiated dynamics [Casali et al., 2013](https://doi.org/10.1126/scitranslmed.3006294). CMD, or covert awareness, is the condition in which a behaviourally unresponsive patient follows commands detectably on fMRI or EEG [Owen et al., 2006](https://doi.org/10.1126/science.1130197). Both are calibrated against people who can report.

## State of the field (as of 2026-10-09)

### What is established

Three results are solid. First, conscious level changes under anaesthesia, sleep and brain injury, and these changes track cortical dynamics rather than behaviour. In the 2013 PCI report, vegetative-state patients scored about 0.19 to 0.31, minimally conscious patients 0.32 to 0.49 and locked-in patients 0.51 to 0.62 [Casali et al., 2013](https://doi.org/10.1126/scitranslmed.3006294).

Second, behaviour underestimates awareness. Owen's 2006 single case showed a patient who met vegetative-state criteria modulating brain activity on command, imagining tennis versus walking through her house [Owen et al., 2006](https://doi.org/10.1126/science.1130197). The 2024 multicentre NEJM study found that 60 of 241 (25%) behaviourally unresponsive patients performed command-following tasks detectable by fMRI or EEG, versus 43 of 112 (38%) who could respond overtly; CMD went with younger age, longer time since injury and traumatic aetiology [Bodien et al., 2024](https://doi.org/10.1056/NEJMoa2400645). The cohort was a convenience sample, so 25% is not a population estimate, but CMD is now a recognised clinical category bearing on prognosis and withdrawal of care.

Third, conscious perception goes with decodable, content-specific activity in posterior visual and ventral-temporal cortex, while much processing proceeds without awareness [Cogitate Consortium, 2025](https://www.nature.com/articles/s41586-025-08888-1); [Mashour et al., 2020](https://pmc.ncbi.nlm.nih.gov/articles/PMC8770991/).

### The theories

Seth and Bayne sort theories into four families (higher-order, global workspace, re-entry and predictive processing, integrated information) and note that it is often unclear whether they explain the same thing, which complicates testing them against one another [Seth and Bayne, 2022](https://sro.sussex.ac.uk/id/eprint/105030/1/SethBayne_NRN_accepted.pdf). A 2019 statement by Michel and 57 co-authors argued that the field had matured enough to deserve serious funding and clinical attention [Michel et al., 2019](https://pmc.ncbi.nlm.nih.gov/articles/PMC6568255).

| Theory | Core claim | Front or back? | Verdict on a digital emulation | Source |
|---|---|---|---|---|
| GNWT | Conscious when ignited and broadcast across a frontoparietal workspace | Front | Conscious if the architecture is reproduced | Mashour et al., 2020 |
| IIT | Conscious to the extent of irreducible intrinsic cause-effect power (Φ) | Back | Negligible Φ; a "perfect zombie" | Albantakis et al., 2023; Tononi et al., 2025 |
| HOT (HOROR, PRM) | Conscious when a first-order state is targeted by a higher-order representation | Front | Conscious if the higher-order structure is reproduced | Brown et al., 2019 |
| RPT | Local recurrent processing within sensory cortex suffices | Back | Conscious on the functionalist reading used by Butlin et al. | Lamme, 2006 |
| AST | The brain models its own attention and concludes it is aware | Not at issue | Conscious in the only sense the theory recognises | Webb and Graziano, 2015 |
| Predictive processing (Seth) | Perception as controlled hallucination; self as interoceptive regulation | Not at issue | Doubtful without a living, self-regulating body | Seth and Bayne, 2022 |
| Illusionism | No phenomenal consciousness; explain the conviction instead | Not applicable | Nothing phenomenal to transfer | Chalmers, 2018 |

### Testing them

The most important recent event is the Templeton-funded Cogitate adversarial collaboration. IIT and GNWT proponents preregistered divergent predictions, and theory-neutral data-collecting teams tested them on 256 participants with fMRI, MEG and intracranial EEG; proponents of both theories, including Dehaene, Koch, Tononi and Boly, are co-authors of the Nature paper, with Melloni, Mudrik and Pitts senior [Cogitate Consortium, 2025](https://www.nature.com/articles/s41586-025-08888-1).

| Finding | Result | Bearing, per the paper |
|---|---|---|
| Content-specific information in visual, ventrotemporal and inferior frontal cortex | Found | Positive result |
| Sustained occipital and lateral temporal activity tracking stimulus duration | Found | Positive result |
| Frontal-visual synchronisation carrying content | Found | Positive result |
| Sustained synchronisation within posterior cortex | Absent | Against IIT's preregistered prediction |
| "Ignition" at stimulus offset | Largely absent | Against GNWT's preregistered prediction |
| Representation of some conscious dimensions in prefrontal cortex | Weak | Against GNWT's emphasis on prefrontal cortex |

Both camps kept their theories; the paper's own verdict is that the results "substantially challenge key tenets of both" [Cogitate Consortium, 2025](https://www.nature.com/articles/s41586-025-08888-1). The full dataset has been released for independent re-analysis.

Three follow-ons were reported but could not be verified as of 2026-10-09: a second Cogitate experiment under analysis; a Templeton collaboration led by Biyu He at NYU, with Chalmers and Block, testing HOROR and PRM against RPT, so far with only preliminary, inconclusive results; and a 2026 preregistered protocol extending the GNWT-versus-IIT test to non-human primates and mice. Check the Templeton World Charity Foundation and Cogitate sites before quoting any of them.

### The IIT controversy

In September 2023 an open letter signed by 124 researchers called IIT "pseudoscience", arguing that Cogitate had not tested IIT's core claims, that those claims may be untestable in principle, and that press coverage had oversold the theory before peer review; its drafting group included Hakwan Lau, a leading higher-order theorist. In 2025 a group of signatories (Klincewicz et al.) elaborated the argument in Nature Neuroscience, accepting IIT-inspired complexity measures such as PCI as ordinary science while denying that they test IIT [Klincewicz et al., 2025](https://www.nature.com/articles/s41593-025-01881-x). Tononi and colleagues replied in the same issue that the charge exposes a crisis in the dominant computational-functionalist paradigm, which IIT's consciousness-first paradigm challenges [Tononi et al., 2025](https://doi.org/10.1038/s41593-025-01880-y); a companion comment by Gomez-Marin and Seth argued that a theory can be wrong without being pseudoscience.

### Bottom line, and a sourcing note

Level measurement in humans is reasonably mature; content decoding works in constrained settings; no theory has survived a direct preregistered test unscathed; and the theories split on function versus substrate, which is the crux for a copied brain.

Sourcing note. No publisher page cited here could be opened from the environment in which this chapter was drafted: web search was unavailable and every publisher host refused the connection. Bibliographic details rest on indexed records and the fact-checker's own knowledge; items that could not be confirmed (a 2016 PCI validation study, a 2022 field survey, the 2026 animal protocol) were dropped. This chapter does not yet meet the README's verification standard; open each source before relying on it.

## Debates and critiques

**Is IIT science?** The 2023 signatories and Klincewicz et al. hold that IIT's core claims, for example that a grid of inactive logic gates could be highly conscious, are untestable in principle [Klincewicz et al., 2025](https://www.nature.com/articles/s41593-025-01881-x). Tononi et al. and Gomez-Marin and Seth reply that ambitious, unorthodox and possibly wrong is not the same as pseudoscientific, and that the charge reflects a functionalist paradigm defending itself [Tononi et al., 2025](https://doi.org/10.1038/s41593-025-01880-y).

**Front versus back.** GNWT and HOT put the NCC in prefrontal and frontoparietal circuits; IIT and RPT in a posterior hot zone. Cogitate found content in both inferior frontal and posterior cortex, weaker prefrontal representation and no offset ignition, which each side reads differently [Cogitate Consortium, 2025](https://www.nature.com/articles/s41586-025-08888-1).

**What did Cogitate actually test?** Proponents of both theories argue that the preregistered predictions were operationalisations, not the theories' core, so disconfirming them refutes nothing. Critics argue this immunises theories from falsification; future adversarial collaborations need pre-agreed rules for what counts as a theory-level failure.

**Realism versus illusionism.** Chalmers and most neuroscientists treat phenomenal consciousness as a real explanandum; Dennett and Frankish treat it as an introspective illusion, with the meta-problem as the real task [Chalmers, 2018](https://researchportalplus.anu.edu.au/en/publications/the-meta-problem-of-consciousness/). Illusionists are accused of changing the subject; realists of positing something no third-person data could confirm.

**Computational functionalism versus substrate dependence.** GNWT, HOT, AST and the Butlin et al. framework assume the right computation suffices [Butlin et al., 2023](https://arxiv.org/abs/2308.08708); IIT holds that a digital simulation would have negligible Φ [Tononi et al., 2025](https://doi.org/10.1038/s41593-025-01880-y); Seth holds that life and interoceptive self-regulation may be required. No experiment resolves this.

**Over- versus under-attribution in disorders of consciousness.** Proponents read command-following on fMRI or EEG as proof of awareness [Owen et al., 2006](https://doi.org/10.1126/science.1130197); [Bodien et al., 2024](https://doi.org/10.1056/NEJMoa2400645); critics note false negatives (task demands, aphasia, fatigue), possible false positives (automatic responses to words such as "tennis"), convenience sampling and the lack of standardised clinical availability. The true prevalence and mechanism of CMD are unknown. Likewise PCI is validated only against people who can report [Casali et al., 2013](https://doi.org/10.1126/scitranslmed.3006294), so extending it to non-reporting patients, animals or machines is an inductive leap.

**Is HOT over-intellectualising consciousness?** Critics say infants and non-human animals lack the required higher-order capacities, which bears directly on whether a cat is conscious. Brown, Lau and LeDoux answer that the requirement is far lighter than metacognition [Brown et al., 2019](https://pure.skku.edu/en/publications/understanding-the-higher-order-approach-to-consciousness/).

## Open questions

- Is prefrontal cortex part of the substrate of experience, or only of access, report and metacognition? Cogitate's inferior-frontal decoding plus absent offset ignition cuts both ways.
- Why was there no GNWT ignition at stimulus offset, and must GNWT revise how conscious content is updated when a stimulus disappears?
- Can Φ ever be computed for a real brain, given that exact computation is intractable beyond roughly a dozen elements, and what disconfirmed prediction would IIT's proponents accept as refuting the theory rather than an approximation?
- Is there phenomenal consciousness that cannot be reported (RPT's overflow), and if so, how could any third-person method confirm it?
- Would a neuron-level emulation share the brain's intrinsic cause-effect structure in IIT's sense, or does serial, clocked hardware guarantee low Φ regardless of fidelity? No one has computed this for a realistic case.
- Can any validated measure of conscious level be extended to non-human or non-biological systems when every calibration so far relies on human report?

## Where to start

The URLs in items 1, 2 and 4 were not opened during drafting; check them first.

1. **Read (free, about 20 minutes).** Quanta Magazine, "What a Contest of Consciousness Theories Really Proved" (August 2023), https://www.quantamagazine.org/what-a-contest-of-consciousness-theories-really-proved-20230824/, a fair non-technical account of the Cogitate test and the pseudoscience dispute. Then the Nature paper itself [Cogitate Consortium, 2025](https://www.nature.com/articles/s41586-025-08888-1).
2. **Listen (free).** Brain Inspired podcast episode 211, "COGITATE: Testing Theories of Consciousness", https://braininspired.co/podcast/211/: the Cogitate leads explain the design, the preregistration and what went wrong for each theory.
3. **Read (free, then about 15 USD).** Seth and Bayne's map of the theory families [Seth and Bayne, 2022](https://sro.sussex.ac.uk/id/eprint/105030/1/SethBayne_NRN_accepted.pdf), then the 2025 Nature Neuroscience exchange [Klincewicz et al., 2025](https://www.nature.com/articles/s41593-025-01881-x); [Tononi et al., 2025](https://doi.org/10.1038/s41593-025-01880-y). For a book, Anil Seth's *Being You: A New Science of Consciousness* (Faber / Dutton, 2021) is the most accessible serious introduction; it argues a position.
4. **Try (free, hands-on).** The Cogitate open data release, https://cogitate-consortium.github.io/cogitate-data/, with fMRI, MEG and iEEG from 256 participants. Reproduce a content-decoding or duration-tracking analysis: the fastest way to see what a "neural correlate" means in practice and how fragile the inferences are.
5. **Work through (free).** IIT 4.0 [Albantakis et al., 2023](https://doi.org/10.1371/journal.pcbi.1011465), then implement the cause-effect-structure calculation for a three- or four-node toy system. It is the only major theory specified precisely enough to code, and doing so makes its appeal and its tractability problem concrete.

## References

1. Cogitate Consortium: Ferrante, O., Gorska-Klimowska, U., Henin, S., et al., with Boly, M., Dehaene, S., Koch, C., Tononi, G., Pitts, M., Mudrik, L., Melloni, L. (2025). *Adversarial testing of global neuronal workspace and integrated information theories of consciousness*. Nature 642: 133-142 (published online 30 April 2025). https://www.nature.com/articles/s41586-025-08888-1
2. Albantakis, L., Barbosa, L., Findlay, G., et al., Tononi, G. (2023). *Integrated information theory (IIT) 4.0: Formulating the properties of phenomenal existence in physical terms*. PLOS Computational Biology 19(10): e1011465; preprint arXiv 2212.14787. https://doi.org/10.1371/journal.pcbi.1011465
3. Seth, A. K., Bayne, T. (2022). *Theories of consciousness*. Nature Reviews Neuroscience 23(7): 439-452; open-access accepted manuscript. https://sro.sussex.ac.uk/id/eprint/105030/1/SethBayne_NRN_accepted.pdf
4. Michel, M., Beck, D., Block, N., et al. (58 authors) (2019). *Opportunities and challenges for a maturing science of consciousness*. Nature Human Behaviour 3(2): 104-107. https://pmc.ncbi.nlm.nih.gov/articles/PMC6568255
5. Mashour, G. A., Roelfsema, P., Changeux, J.-P., Dehaene, S. (2020). *Conscious Processing and the Global Neuronal Workspace Hypothesis*. Neuron 105(5): 776-798. https://pmc.ncbi.nlm.nih.gov/articles/PMC8770991/
6. Brown, R., Lau, H., LeDoux, J. E. (2019). *Understanding the Higher-Order Approach to Consciousness*. Trends in Cognitive Sciences 23(9): 754-768. https://pure.skku.edu/en/publications/understanding-the-higher-order-approach-to-consciousness/
7. Webb, T. W., Graziano, M. S. A. (2015). *The attention schema theory: a mechanistic account of subjective awareness*. Frontiers in Psychology 6: 500. https://www.frontiersin.org/articles/10.3389/fpsyg.2015.00500/pdf
8. Lamme, V. A. F. (2006). *Towards a true neural stance on consciousness*. Trends in Cognitive Sciences 10(11): 494-501. https://www.dare.uva.nl/id/fcb7629f-6d56-4a07-bf82-e7e71ecbc52b
9. Chalmers, D. J. (2018). *The Meta-Problem of Consciousness*. Journal of Consciousness Studies 25(9-10): 6-61. https://researchportalplus.anu.edu.au/en/publications/the-meta-problem-of-consciousness/
10. Tsuchiya, N., Wilke, M., Frässle, S., Lamme, V. A. F. (2015). *No-Report Paradigms: Extracting the True Neural Correlates of Consciousness*. Trends in Cognitive Sciences 19(12): 757-770. https://pubmed.ncbi.nlm.nih.gov/26585549/
11. Casali, A. G., Gosseries, O., Rosanova, M., et al., Tononi, G., Massimini, M. (2013). *A Theoretically Based Index of Consciousness Independent of Sensory Processing and Behavior*. Science Translational Medicine 5(198): 198ra105. https://doi.org/10.1126/scitranslmed.3006294
12. Owen, A. M., Coleman, M. R., Boly, M., Davis, M. H., Laureys, S., Pickard, J. D. (2006). *Detecting Awareness in the Vegetative State*. Science 313(5792): 1402. https://doi.org/10.1126/science.1130197
13. Bodien, Y. G., Allanson, J., Cardone, P., et al. (2024). *Cognitive Motor Dissociation in Disorders of Consciousness*. New England Journal of Medicine 391(7): 598-608. https://doi.org/10.1056/NEJMoa2400645
14. Klincewicz, M., Cheng, T., Schmitz, M., Sebastián, M. Á., Snyder, J. S. (2025). *What makes a theory of consciousness unscientific?*. Nature Neuroscience 28(4): 689-693. https://www.nature.com/articles/s41593-025-01881-x
15. Tononi, G., Albantakis, L., Barbosa, L., et al., Koch, C., Massimini, M., Tsuchiya, N., et al. (2025). *Consciousness or pseudo-consciousness? A clash of two paradigms*. Nature Neuroscience 28(4): 694-702. https://doi.org/10.1038/s41593-025-01880-y
16. Butlin, P., Long, R., Elmoznino, E., et al. (2023). *Consciousness in Artificial Intelligence: Insights from the Science of Consciousness*. arXiv 2308.08708 (v1 17 August 2023); a condensed peer-reviewed version appeared as "Identifying indicators of consciousness in AI systems", Trends in Cognitive Sciences, 2025 (volume and pages not confirmed). https://arxiv.org/abs/2308.08708
17. Gomez-Marin, A., Seth, A. K. (2025). Companion comment on the Klincewicz et al. and Tononi et al. exchange (title not confirmed). Nature Neuroscience 28: 703-706. URL not confirmed.
