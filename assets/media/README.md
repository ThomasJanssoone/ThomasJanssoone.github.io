# Project media

Figures used by `index.html`.

## From the Quintessence research talk

| File                     | Section              | Slide |
| ------------------------ | -------------------- | ----- |
| `brunswik-lens.png`      | The question         | 4     |
| `mirokai.png`            | Enchanted Tools      | 13    |
| `metahuman-dataset.jpg`  | Enchanted Tools      | 12    |
| `deployment-bias.png`    | Enchanted Tools      | 13    |
| `potus-corpus.mp4/.png`  | PhD                  | 5     |
| `smart-pipeline.png`     | PhD                  | 7     |
| `shap-individual.png`    | Deep dive            | 24    |
| `shap-all.png`           | Deep dive            | 25    |
| `semeia-explanation.png` | Semeia               | 8     |
| `rapport-architecture.png` | Inria COML         | 9     |
| `esensia-pipeline.svg`   | e-sensia             | 14    |

## From published papers

| File                   | Paper                                                        | Rights                       |
| ---------------------- | ------------------------------------------------------------ | ---------------------------- |
| `action-units.png`     | Janssoone et al., *The POTUS Corpus*, LREC 2020               | CC BY-NC, attributed in caption |
| `cloning-protocol.png` | Janssoone et al., *The POTUS Corpus*, LREC 2020               | CC BY-NC, attributed in caption |
| `octopocus3d.png`      | Delamare, Janssoone, Coutrix & Nigay, *Designing 3D Gesture Guidance*, AVI 2016 | © ACM, author's version; posted under ACM author rights on the author's own site |

Notes:
- `.figure img` sets `height: auto` — do not remove it. The `width`/`height`
  attributes are there for layout stability and will stretch the image without it.
- Nothing is displayed above its native resolution; `.fig-narrow` (620px),
  `.fig-mid` (666px) and `.fig-small` (480px) cap the smaller sources.
- Chart figures are rendered on white, so `.figure img` has a white background.
- `smart-pipeline.png` and `semeia-explanation.png` are in French (a thesis
  figure and a deployed clinical interface respectively).
- `esensia-pipeline.svg` is redrawn, not extracted: slide 14 is built from
  PowerPoint shapes rather than an image. Node labels and the edge list come
  from the slide's own geometry; the layout is new. It carries its own dark
  background, so its `.figure img` background is overridden inline.
- Not used, by decision: the BOTANIC-1 model card and the agentic BSA pipeline
  (slides 15-16), as unreleased Living Models material.
