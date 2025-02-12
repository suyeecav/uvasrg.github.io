+++
date = "05 Apr 2021"
draft = false
title = "CrySP Talk: When Models Learn Too Much"
author = "David Evans"
categories = ["talks"]
tags = ["adversarial machine learning", "privacy-preserving machine learning", "differential privacy", "videos"]
+++

I gave a talk on [_When Models Learn Too Much_](https://crysp.uwaterloo.ca/speakers/20210329-Evans) at the University of Waterloo (virtually) in the CrySP
Speaker Series on Privacy (29 March 2021):

<center>
<iframe width="900" height="315" src="https://www.youtube-nocookie.com/embed/LM_-N76_KIw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>

<center>
<b>Abstract</b>
</center>

Statistical machine learning uses training data to produce models that
capture patterns in that data. When models are trained on private
data, such as medical records or personal emails, there is a risk that
those models not only learn the hoped-for patterns, but will also
learn and expose sensitive information about their training
data. Several different types of inference attacks on machine learning
models have been found, and methods have been proposed to mitigate the
risks of exposing sensitive aspects of training data. Differential
privacy provides formal guarantees bounding certain types of inference
risk, but, at least with state-of-the-art methods, providing
substantive differential privacy guarantees requires adding so much
noise to the training process for complex models that the resulting
models are useless. Experimental evidence, however, suggests that
inference attacks have limited power, and in many cases a very small
amount of privacy noise seems to be enough to defuse inference
attacks. In this talk, I will give an overview of a variety of
different inference risks for machine learning models, talk about
strategies for evaluating model inference risks, and report on some
experiments by our research group to better understand the power of
inference attacks in more realistic settings, and explore some broader
the connections between privacy, fairness, and adversarial robustness.
