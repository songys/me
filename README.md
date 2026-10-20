# Youngsook Song

Researcher at **Lablup**, working at the intersection of language and AI.
Ph.D. in Korean Linguistics, **Kyung Hee University** (August 2023).

My interests include computational linguistics, linguistic typology, commonsense
reasoning, phonetics, language model evaluation, and open Korean language resources.
I teach, write, and organize communities around language and technology.

[Website](https://songys.github.io/me/) ·
[Full academic profile](https://sites.google.com/view/youngsooksong/%ED%99%88) ·
[Google Scholar](https://scholar.google.com/citations?user=kp_a52kAAAAJ) ·
[GitHub](https://github.com/songys) ·
[Email](mailto:klanguage1004@gmail.com)

## Inference Korea

Inference Korea is a study community focused on inference engineering: how to run
AI models efficiently and reliably. We currently have **72 Discord members**
(October 2026).

We study *Inference Engineering* by Patrick Kiely and related research papers.
Members take turns presenting chapters and papers, covering GPU architecture,
inference engines, quantization, caching, model parallelism, benchmarking, and
deployment.

**After the reading and discussion phase, we plan to continue with hands-on
sessions** to apply what we have learned about inference engines and model serving.

- **Reading schedule:** 10 sessions, October 24 to December 26, 2026.
- **Meeting time:** Saturdays at 8:00 PM KST (tentative).
- **Timetable:** [View the study schedule](https://docs.google.com/spreadsheets/d/1T4LO2PETrdOSkE-LH4GfFXKvfwrwcla_3mnEYTLAJks/edit?usp=sharing).

## Research, teaching, and community

- Research on vision-language model evaluation, Korean language resources,
  multilingual datasets, and large-scale model training operations.
- AI and the Humanities, Dankook University, spring 2026.
- Books and translation work on Korean text analysis, statistical learning,
  and Python software architecture.
- Langcon organizer: [Langcon 2026](https://songys.github.io/2026Langcon).

The website presents selected work from the
[original academic profile](https://sites.google.com/view/youngsooksong/%ED%99%88).
The full publication and activity record remains available there.

## Website

The site is a static HTML/CSS page in `dist/`. No dependencies or build step are
required. GitHub Actions publishes `dist/` to GitHub Pages whenever `main` is
updated. The deployment workflow is `.github/workflows/pages.yml`.

To preview locally:

```sh
python3 -m http.server 8080 --directory dist
```

Open `http://localhost:8080`.
