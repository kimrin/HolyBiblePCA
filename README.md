# Bible PCA Space

An exploratory visualization of the 66 books of the Bible as a geometric space.

This project assigns a small set of heuristic, interpretive features to each book (e.g. narrative density, poetic tone, emotional polarity, perceived divine proximity), and maps them into a low-dimensional space using PCA.

The result is an interactive 3D “Bible space” where theological intuition, literary texture, and structure begin to appear as spatial relationships.

👉 Live visualization:
https://kimrin.github.io/HolyBiblePCA/

---

## Motivation

This is not a doctrinal project, but a cartographic one.

The goal is to explore questions like:

- What happens if we treat biblical books as points in a semantic space?
- Do literary and theological intuitions form visible clusters?
- Can subjective reading impressions produce coherent geometry?

The scoring is intentionally interpretive rather than authoritative.

---

## Features

Each book is assigned rough, hand-tuned scores along multiple axes, such as:

- Narrative density
- Poetic / rhetorical intensity
- Normative / instructional tone
- Apocalyptic intensity
- Judgment ↔ Mercy polarity
- Individual ↔ Communal focus
- Lament ↔ Praise polarity
- Perceived divine proximity
- Missional outwardness
- Christological centrality

These features are standardized and reduced using PCA.

---

## Visualization

The main output is an interactive Plotly 3D scatter plot:

- 3 principal components (PCA)
- Color = perceived divine proximity
- Shape = Old Testament / New Testament
- Hover = book name and metadata

The visualization is exported as a static HTML file and hosted via GitHub Pages.

---

## Transparency

This repository intentionally includes:

- The scoring logic
- The notebook used for generation
- The exported visualization

The model is subjective and meant to invite reinterpretation, remixing, and critique.

Forks and alternate scoring systems are very welcome.

---

## How to run locally

```bash
uv sync
# notebook usage (optional)
uv sync --extra notebook
```

Or open the notebook and run all cells.

---

## Notes

- This is an interpretive visualization experiment, not a theological claim.
- The geometry reflects the chosen features and scoring philosophy.
- Different traditions would likely produce different spaces.

---

## Future directions

Possible extensions:

- Alternate feature sets (tradition-aware spaces)
- UMAP / non-linear embeddings
- Multiple “color universes” (e.g. Christological density, emotional polarity)
- Temporal animations (Genesis → Revelation trajectories)

---

## License

MIT (or choose your preferred license)

---

## Acknowledgements

Inspired by the idea that maps can reveal patterns that prose cannot.

If this visualization sparks new readings or questions, it has already done its job.

---

“Not a system, but a space.”