---
layout: post
title: Causality for NLP
date: 2020-06-27 11:12:00-0400
description: Connecting the notion of causality to NLP.
---

This post aims to connect some recent progress in NLP and the long studied field of causality research.


As Weber et al. points out, a purely correlation-based approach is insufficient, and instead propose an approach to script induction based on the causal effect between events, formally defined via interventions.

For a pair of events $$ e_1 $$ and $$ e_2 $$, how do we know that $$ e_2 $$ should follow $$ e_1 $$ in a commonsense scenario (script)? A common approach is to measure the conditional probability $$ p(e_2 \vert e_1) $$ from the occurances of such events. However, as commonly encountered in NLP, relatedness doesn't imply causality [cite here]. This is a well studied phenomenon in causality research called _confounding_. 