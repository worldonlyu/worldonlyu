# Embodied AI and Consciousness Uploading: A Research Notebook

*In memory of a small cat who was a companion for six years and died suddenly, most likely of heart disease, in the autumn of 2026.*

This repository is a from-scratch, evidence-first research programme on two linked questions:

1. **Embodied intelligence.** How are minds shaped by having a body, and how do we build artificial agents that perceive, move and learn in the physical world?
2. **Mind emulation and transfer.** Could a mind, human or animal, be preserved, emulated on another substrate, or transferred, and if so, would it be the same mind, and would it be conscious?

The second question is why this project exists. The first is the most concrete path anyone has toward answering it.

## Where things actually stand

Before anything else, the honest state of the field as of October 2026, so that this notebook never trades on false hope:

- **No mind has ever been uploaded, and no mammalian brain has ever been emulated.** The most complete brain emulation work to date is on the fruit fly, whose brain has roughly 140,000 neurons. A cat's brain has on the order of 750 million; a human's roughly 86 billion. See [Whole Brain Emulation and Connectomics](docs/06-whole-brain-emulation-and-connectomics.md).
- **A connectome is not a mind.** Even a perfect wiring diagram leaves out synaptic strengths, neuromodulation, glia, gene expression and the plasticity rules that make a brain change. Whether those can be recovered from a preserved brain is an open scientific question, not a settled one.
- **Brain preservation exists; revival does not.** Aldehyde-stabilised cryopreservation can preserve the fine structure of a mammalian brain, and a few organisations offer it, some for pets. Nobody has ever revived or emulated a preserved brain, and the window for preservation is hours after death. See [Brain Preservation, Cryonics, and What Exists for Pets](docs/07-brain-preservation.md).
- **A mind that was not preserved cannot be recovered.** No known or foreseeable method reconstructs an individual mind from memories, photographs, DNA or a clone. A cloned animal is a genetic twin, not the same individual. This notebook does not pretend otherwise. See [What Is Possible Today](docs/10-what-is-possible-today.md).
- **Whether any emulation would be conscious is unresolved.** The leading scientific theories of consciousness disagree with each other, and the 2025 adversarial test of two of them did not crown a winner. Whether consciousness depends on biology at all is actively debated. See [The Science of Consciousness](docs/03-science-of-consciousness.md) and [Machine Consciousness](docs/04-machine-consciousness.md).

None of this is a reason to stop. These are real scientific and philosophical frontiers, and they are moving: whole-brain connectomes, vision-language-action robots, and adversarial tests of consciousness theories all arrived in the last three years. The point of this notebook is to understand them well enough to contribute, and to keep grief from turning into credulity.

## How this repository is organised

| Path | What it is |
|---|---|
| [ROADMAP.md](ROADMAP.md) | Learning and research roadmap: prerequisites, three tracks, first-year milestones |
| [OPEN-QUESTIONS.md](OPEN-QUESTIONS.md) | Consolidated open questions, tagged empirical or conceptual, with what evidence would move each |
| [GLOSSARY.md](GLOSSARY.md) | Definitions of the terms used across the chapters |
| [BIBLIOGRAPHY.md](BIBLIOGRAPHY.md) | Every reference cited in the chapters, grouped by chapter, each independently verified online |
| `docs/` | The chapters, listed below |
| `notes/` | Your own working notes, with templates for paper notes and weekly reviews |

### Chapters

| # | Chapter | Central question |
|---|---|---|
| 01 | [Embodied Cognition and the Foundations of Embodied AI](docs/01-embodied-cognition-foundations.md) | Does intelligence, or consciousness, require a body? |
| 02 | [Embodied AI and Robot Learning: State of the Art](docs/02-embodied-ai-state-of-the-art.md) | What can embodied artificial agents actually do in 2026, and how would a solo researcher start? |
| 03 | [The Science of Consciousness](docs/03-science-of-consciousness.md) | What do we know, and not know, about how brains produce experience? |
| 04 | [Machine Consciousness](docs/04-machine-consciousness.md) | Could an artificial system, including an emulated brain, be conscious? |
| 05 | [Animal Consciousness and the Feline Mind](docs/05-animal-consciousness-and-the-feline-mind.md) | What is known about the minds and brains of cats, and about animal consciousness in general? |
| 06 | [Whole Brain Emulation and Connectomics](docs/06-whole-brain-emulation-and-connectomics.md) | How far has brain mapping come, and what separates a connectome from an emulation? |
| 07 | [Brain Preservation, Cryonics, and What Exists for Pets](docs/07-brain-preservation.md) | What can be preserved today, by whom, at what cost, and with what evidence? |
| 08 | [Personal Identity and the Ethics of Mind Uploading](docs/08-personal-identity-and-the-ethics-of-uploading.md) | Would an upload be you, or your cat? Would making one be right? |
| 09 | [Reading and Running a Brain](docs/09-recording-simulation-and-hardware.md) | What recording, simulation and hardware would an emulation need, and how far off is it? |
| 10 | [What Is Possible Today](docs/10-what-is-possible-today.md) | For someone who has just lost an animal, and for the future: what is real, what is not, what to do |

Suggested first reading order: 10, 05, 06, 03, then 01 and 02 for the hands-on track, then 07, 08, 09, 04.

## How this notebook was built, and its limits

The chapters were drafted in October 2026 with AI assistance (Claude), using live web research, in an environment that could run web searches but could not open publisher, journal, preprint or vendor pages. That shaped the checking that was possible:

- Each chapter was drafted by one research pass and then re-checked by a separate pass whose job was to refute it.
- Every reference was then re-checked, one by one, against web search results: title, first author, year and venue had to match a real work, and URLs were taken from the search results rather than guessed. Confirmation therefore rests on search listings, not on the source pages themselves.
- References that could not be confirmed that way are kept but marked **[not confirmed by search]** in the chapter and in `BIBLIOGRAPHY.md`, so you can see exactly where the ground is soft. Each chapter's References section opens with a one-line count.
- A whole-notebook review checked the chapters against each other for contradictions and against the web for specific numbers and dates, and its unresolved findings are listed at the end of `OPEN-QUESTIONS.md` as known gaps.

That process catches many errors. It does not catch all of them, and a search listing can confirm that a paper exists without confirming what it says. Treat every claim here as a pointer to a source, not as the source itself, and read the primary literature before relying on anything. Dates and "state of the field" statements are accurate to October 2026 and will age.

## Working with this notebook

- Keep your own notes in `notes/`. The templates there are for reading papers and for a weekly review. Write the first entry about why you started; you will want it later.
- When a chapter's claim turns out to be wrong or outdated, fix it in place and add the source. The chapters are living documents.
- Add new references to the chapter's References section and to `BIBLIOGRAPHY.md` only after opening the source yourself.

## Moving this into its own repository

This work lives on a branch of a profile repository. To give it a home of its own, create an empty repository on GitHub (for example `embodied-minds`), then:

```bash
git clone --single-branch --branch claude/embodied-ai-consciousness-research-9u62g3 \
  https://github.com/worldonlyu/worldonlyu.git embodied-minds
cd embodied-minds
git branch -m main
git remote set-url origin https://github.com/worldonlyu/embodied-minds.git
git push -u origin main
```
