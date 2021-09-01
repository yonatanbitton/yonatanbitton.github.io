---
abstract: Recent works have shown that supervised models often exploit data
  artifacts to achieve good test scores while their performance severely
  degrades on samples outside their training distribution. Contrast sets
  (Gardneret al., 2020) quantify this phenomenon by perturbing test samples in a
  minimal way such that the output label is modified. While most contrast sets
  were created manually, requiring intensive annotation effort, we present a
  novel method which leverages rich semantic input representation to
  automatically generate contrast sets for the visual question answering task.
  Our method computes the answer of perturbed questions, thus vastly reducing
  annotation cost and enabling thorough evaluation of models' performance on
  various semantic aspects (e.g., spatial or relational reasoning). We
  demonstrate the effectiveness of our approach on the GQA dataset and its
  semantic scene graph image representation. We find that, despite GQA's
  compositionality and carefully balanced label distribution, two
  high-performing models drop 13-17% in accuracy compared to the original test
  set. Finally, we show that our automatic perturbation can be applied to the
  training set to mitigate the degradation in performance, opening the door to
  more robust models.
slides: naacl_contrast_sets
url_pdf: ""
publication_types:
  - "1"
authors:
  - admin
  - Yonatan Bitton
  - Gabriel Stanovsky
  - Roy Schwartz
  - Michael Elhadad
author_notes: []
publication: In Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics (NAACL 2021)
summary: We present a novel method which leverages rich semantic input
  representation to automatically generate contrast sets for the visual question
  answering task. Our method computes the answer of perturbed questions, thus
  vastly reducing annotation cost and enabling thorough evaluation of models'
  performance on various semantic aspects (e.g., spatial or relational
  reasoning)
url_dataset: ""
url_project: ""
publication_short: In *NAACL 2021*
url_source: ""
url_video: ""
title: Automatic Generation of Contrast Sets from Scene Graphs
doi: ""
featured: true
tags: []
projects:
  - naacl_contrast_sets
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: fig1_naal_long.png
date: 2021-03-17T16:17:07.654Z
url_slides: ""
publishDate: 2021-03-17T16:17:07.654Z
url_poster: "publication/contrast_sets/contrast_sets_poster.pdf"
url_code: "https://github.com/yonatanbitton/automatic_generation_of_contrast_sets_from_scene_graphs"
---
