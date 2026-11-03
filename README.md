# Introduction to Geospatial AI

[![Materials: CC BY 4.0](https://img.shields.io/badge/materials-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Code: MIT](https://img.shields.io/badge/code-MIT-blue.svg)](LICENSE-CODE)

Open teaching materials for **Introduction to Geospatial Artificial Intelligence**, a 20-credit Master's course in the MSc Geospatial Data Science and AI at the School of Geographical and Earth Sciences, University of Glasgow (first taught 2026–27).

The course introduces the core concepts, methods and tools of GeoAI: spatially explicit deep learning, graph-based models, representation learning and geospatial foundation models. It is taught through student-led reading discussions, interactive lectures and hands-on Google Colab labs, and it puts equal weight on spatial thinking, reproducible code and the ethics of GeoAI.

Course leader: Meiliu Wu ([@meiliuwu](https://github.com/meiliuwu))

## Schedule

Weeks 1–7 each pair a 2-hour lecture with a 2-hour lab on the same topic. Week 8 is for project proposal presentations, and Weeks 9–10 are project labs.

| Week | Topic | Pre-reading | Lecture | Lab |
| --- | --- | --- | --- | --- |
| 1 | Model architectures for GeoAI | [Readings](readings/week01-model-architectures.md) | [Lecture](lectures/week01-model-architectures/) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/meiliuwu/intro-geoai/blob/main/labs/week01-model-architectures/week01_lab_same_data_four_architectures.ipynb) |
| 2 | Remote sensing and Earth observation | [Readings](readings/week02-remote-sensing.md) | [Lecture](lectures/week02-remote-sensing/) | [Lab (in preparation)](labs/week02-remote-sensing/) |
| 3 | Environmental monitoring | [Readings](readings/week03-environmental-monitoring.md) | [Lecture](lectures/week03-environmental-monitoring/) | [Lab (in preparation)](labs/week03-environmental-monitoring/) |
| 4 | Big geodata mining | [Readings](readings/week04-big-geodata-mining.md) | [Lecture](lectures/week04-big-geodata-mining/) | [Lab (in preparation)](labs/week04-big-geodata-mining/) |
| 5 | Urban analytics | [Readings](readings/week05-urban-analytics.md) | [Lecture](lectures/week05-urban-analytics/) | [Lab (in preparation)](labs/week05-urban-analytics/) |
| 6 | AI and cartography | [Readings](readings/week06-ai-and-cartography.md) | [Lecture](lectures/week06-ai-and-cartography/) | [Lab (in preparation)](labs/week06-ai-and-cartography/) |
| 7 | Ethics of geospatial AI | [Readings](readings/week07-ethics.md) | [Lecture](lectures/week07-ethics/) | [Lab (in preparation)](labs/week07-ethics/) |
| 8 | Project proposal presentations | | [Assessment](assessment/) | |
| 9–10 | Project labs | | [Assessment](assessment/) | |

The seven topics run in four arcs: a shared **toolkit** (Week 1), the **Earth from above** (Weeks 2–3), **society on the ground** (Weeks 4–5), and **communicating and governing** GeoAI (Weeks 6–7). See [course information](course-info/) for the aims, learning outcomes and teaching approach.

## What is in this repository

```
intro-geoai/
├── course-info/      aims, learning outcomes, timetable and teaching formats
├── readings/         pre-lecture papers for each week, with links and annotation prompts
├── lectures/         lecture plans and slides, one folder per week
├── labs/             Google Colab notebooks, one folder per week
├── assessment/       essay themes, proposal presentation and project report guidance
└── resources/        open-source tools, datasets, further reading and printable class materials
```

## For students

1. **Before each lecture**, read and annotate the papers listed under [readings](readings/) and bring one question.
2. **In the lab**, click the *Open in Colab* badge. Then choose **File → Save a copy in Drive** so your changes are kept. No installation is needed; the labs run in a web browser with a Google account.
3. **Keep your own GitHub repository** for lab work from Week 1 onwards (**File → Save a copy in GitHub** in Colab). Your project in Weeks 8–10 is built the same way.

## For other educators

You are welcome to reuse and adapt these materials under the licences below. Issues and pull requests with corrections or ideas are welcome.

## Licence

- **Teaching materials** (text, slides, figures, printable materials) are licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). See [LICENSE.md](LICENSE.md).
- **Code** (notebooks and code cells) is licensed under the [MIT Licence](LICENSE-CODE).
- **Third-party works** are linked, not copied: the papers in the reading lists remain under their publishers' terms, and datasets and libraries keep their own licences (listed in [resources](resources/)).
