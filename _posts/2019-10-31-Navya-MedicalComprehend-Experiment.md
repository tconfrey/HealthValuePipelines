---
layout: post
title:  "Document Classification"
description: "Proof of concept experiment"
author: "Tony"
---

### Navya
[**Navya**](http://navyanetwork.com) provides a second opinion service currently targeted at breast cancer patients. Their Health Value Pipeline starts with an empathetic counselor walking a newly diagnosed patient thru the upload of her records either through photographed images or EHR integration. Trained clinicians then review the information interacting with the patient as necessary to clarify information and produce a concise summary of the diagnosis and recommended course of treatment, along with suggestions for relevant literature. That summary is presented to a panel of expert oncologists via a mobile app. A consensus opinion on the initial assessment and plan is formed and communicated back to the patient.


### Document Classification
An exercise was undertaken to evaluate the potential of a pipeline component that would extract text from PDF documents, process that text through available NLP engines, including [Amazons Comprehend Medical](https://aws.amazon.com/comprehend/medical/) to extract relevant terms and then evaluate whether those terms could accurately identify the document type and major themes. A subsequent project phase is looking at automating the mapping of extracted terms to both an internal and an industry standard data model.
