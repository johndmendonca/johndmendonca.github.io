---
title: "QualityAdapt: an Automatic Dialogue Quality Estimation Framework"
collection: publications
permalink: /publication/2022-10-01-qualityadapt-dialogue-quality-estimation
excerpt: ""
date: 2022-10-01
venue: "SIGDIAL 2022"
paperurl: 'https://aclanthology.org/2022.sigdial-1.9/'
citation: ''
---

Despite considerable advances in open-domain neural dialogue systems, their evaluation remains a bottleneck. Several automated metrics have been proposed to evaluate these systems, however, they mostly focus on a single notion of quality, or, when they do combine several sub-metrics, they are computationally expensive. This paper attempts to solve the latter: QualityAdapt leverages the Adapter framework for the task of Dialogue Quality Estimation. Using well defined semi-supervised tasks, we train adapters for different subqualities and score generated responses with AdapterFusion. This compositionality provides an easy to adapt metric to the task at hand that incorporates multiple subqualities. It also reduces computational costs as individual predictions of all subqualities are obtained in a single forward pass. This approach achieves comparable results to state-of-the-art metrics on several datasets, whilst keeping the previously mentioned advantages.
