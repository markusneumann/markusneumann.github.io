---
title: "Synthesis of Open-ended Survey Responses Using Generative Language Models"
collection: research
permalink: /research/moodsynthesis
excerpt: 'Network simulation exploring the effect of small world effects in the evolutionary development of altruism.'
---

With _Burt Monroe_. Presented at Text as Data 2019. [[Paper]](https://markusneumann.github.io/files/TADA_2019.pdf)

**Abstract**:<br>
We describe and evaluate methods for the synthesis of natural language responses to open-ended survey questions. As with numerical and categorical data, objectives might include imputation of missing responses, imputation of responses from counterfactual or small subgroup respondents, imputation of responses for time periods not surveyed, data augmentation, generation of synthetic data-sets that protect respondent privacy while maintaining sufficiently similar statistical and linguistic properties, or inference about the mechanisms of opinion formation and survey response. Our specific target data - our output language sequences - are responses to questions in the Penn State Mood of the Nation Poll. Drawing from existing theories of survey response, we model this process as transduction from an input - representing the question asked, individual attributes, and a media environment to which the respondent pays selective attention - to an output textual response. This makes the task similar, in NLP terms, to problems like machine translation or summarization. We investigate the utility of two specific encoder-decoder transduction models - the first a sequence to sequence model with an attention mechanism and the second a transformer - for this purpose.
