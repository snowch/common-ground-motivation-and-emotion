# Common Ground: Motivation and emotion

An original introductory course using fictional repair-café stories and the authorized [Common Ground player](https://github.com/snowch/common-ground-social-psychology).

Live: https://snowch.github.io/common-ground-motivation-and-emotion/


Ten chapters, ninety learner-paced pages, forty original concept figures, twenty decisions, written transfer, retrieval and a final case. Each page, feedback choice and recall answer has its own Kokoro af_heart recording. Paragraph pauses and elapsed/remaining playback time support listening. Browser offline saving includes every chapter and its narration; external research requires a connection.

## Build

```sh
python3 build.py
python3 -m http.server 8877 --directory dist
```

Open `http://localhost:8877` to preview the course.

`python3 scripts/check_content.py` validates alignment. `python3 build.py` builds the course. `python3 build.py --portable --output out/portable` builds self-contained decks. `python3 scripts/export_pdfs.py` exports companions. `python3 scripts/build_hosted.py` and `python3 scripts/check_hosted.py` prepare and validate GitHub Pages. The workflow publishes on main.

## Evidence and limitations

The curriculum, examples and diagrams were newly authored. Linked textbooks, scholarly research and professional guidance support the stated distinctions; the fictional cases are not research data. Core limitations remain visible and additional research is expandable. This AI-assisted introduction has no independent academic review or learner pilot. It is not diagnosis, treatment, an assessment instrument or professional training. Research access and source-specific licensing remain with the publishers.

Canonical content is in `course.json`, `course-evidence.json`, `glossary.json`, `visual-models.json`, `learning-check.json` and `production/af-heart/scenes.json`. See `docs/learning-design.md` for objectives and assessment mapping, and `production/README.md` for speech provenance and quality checks.

Design guidance: [Instructional Design](https://github.com/joelrkohlman/instructional-design/blob/main/SKILL.md) and [Frontend Design](https://github.com/anthropics/skills/blob/main/skills/frontend-design/SKILL.md). Narration uses the pinned [record-demo workflow](https://github.com/snowch/claude-skills/tree/c9a7c521568632aa216932f4c965df386498602a/plugins/demo-video/skills/record-demo), Kokoro v1.0, af_heart, speed 1.0. Automated speech screening is not human listening approval. Fonts and other licensed assets include notices.
