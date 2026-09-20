# You Are More Than You 🌿

> *Quick, curious audio stories about the wild, living world inside you.*  
> **Live Site:** [youaremorethanyou.com](https://youaremorethanyou.com) · **Ecosystem:** [fallow.garden](https://fallow.garden)

---

## About the Project

**You Are More Than You** is a micro-dispatch audio series exploring the gut-brain axis, microbial biodiversity, and internal ecology. Moving away from the mechanistic view of the body as an engine to "fuel," the project reframes human biology as a living habitat of 38 trillion organisms whose daily rhythms directly shape our mood, cravings, and resilience.

The series serves as the audio companion to interactive web utilities hosted across [fallow.garden](https://fallow.garden).

---

## Episodes & Companion Apps

| Ep | Title | Focus | Companion App |
|:---|:------|:------|:--------------|
| **01** | **You Are a Habitat** | The gut-brain axis, vagus nerve signaling, and microbial chemistry (serotonin, GABA, cravings). | [Multitudes](https://fallow.garden/multitudes) |
| **02** | **Your Body Is a Meadow** | The American Gut Project, dietary diversity, and the "30 plants a week" rule. | [Inner Meadow](https://fallow.garden/inner-meadow) |
| **03** | **Your Body Is an Ancient Forest** | Reseeding after trauma (antibiotics/C. diff), probiotic myths, and the science of FMT. | [Re-Poopulate](https://fallow.garden/re-poopulate) |

---

## The Co-Hosts

Audio tracks are generated via custom-prompted NotebookLM models with two distinct personas:
* **Sir David Detail:** Reverent, hushed wildlife documentary narrator marveling at the microscopic flora and fauna of the colon.
* **Ms. Julia Practical:** Warm, boisterous, food-obsessed chef who translates microbial science into everyday kitchen reality.

---

## Project Structure

```text
.
├── index.html          # Semantic HTML5 player page with custom CSS & audio JS
├── robots.txt          # Crawler directives (permits site indexing, shields /audio/)
├── README.md           # Project documentation
└── audio/              # Native AAC (.m4a) audio files exported from NotebookLM
    ├── ep01-gut-brain.m4a
    ├── ep02-inner-meadow.m4a
    └── ep03-repoopulate.m4a
