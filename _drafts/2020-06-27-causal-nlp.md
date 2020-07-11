---
layout: post
title: Causality in NLP
date: 2020-06-27 11:12:00-0400
description: Explore the notion of causality in NLP.
permalink: /causal-nlp-1/
---

This post aims to connect some recent progress in NLP and the long studied field of causality research.


As Weber et al. points out, a purely correlation-based approach is insufficient, and instead propose an approach to script induction based on the causal effect between events, formally defined via interventions.

For a pair of events $$ e_1 $$ and $$ e_2 $$, how do we know that $$ e_2 $$ should follow $$ e_1 $$ in a commonsense scenario (script)? A common approach is to measure the conditional probability $$ p(e_2 \vert e_1) $$ from the occurances of such events. However, as commonly encountered in NLP, relatedness doesn't imply causality [cite here]. Suprious associations could be picked up resulting in brittleness. This is a well studied phenomenon in causality research called _confounding_. 

“potentially exploitable for the purposes of manipulation and control" [cite here]. I.e., if $$ A $$ causes $$ B $$, manipulating $$ A $$ should results in changes in $$ B $$.