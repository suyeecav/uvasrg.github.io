+++
date = "28 Sep 2021"
draft = false
title = "UVA News Article"
author = "David Evans"
categories = ["talks"]
tags = ["adversarial machine learning", "privacy", "Bargav Jayaraman", "Xiao Zhang", "Jack Prescott", "Anshuman Suri", "Katherine Knipmeyer", "inference privacy", "privacy", "privacy-preserving machine learning"]
+++

UVA News has an article by Audra Book on our research on security and
privacy of machine learning (with some very nice quotes from several
students in the group, and me saying something positive about the
NSA!): [_Computer science professor David Evans and his team conduct
experiments to understand security and privacy risks associated with
machine
learning_](https://engineering.virginia.edu/news/2021/09/computer-science-professor-david-evans-and-his-team-conduct-experiments-understand),
8 September 2021.

<div class="articletext">

David Evans, professor of computer science in the University of Virginia School of Engineering and Applied Science, is leading research to understand how machine learning models can be compromised.

Machine learning applies algorithms to train models from massive amounts of data that can make predictions—often better than humans can, at least at well-contained tasks. But the power of machine learning also comes with security threats.

Attackers can glean information about the data that was used to train models, even when the training data itself is well protected. For example, in the case of models trained on medical records, it may be possible to learn sensitive information about records used to train the model merely by testing the model.

Attackers can also craft inputs that confuse models, even tricking models into producing a preferred outcome for an input that looks normal to humans. Another kind of attack, known as a “poisoning attack” occurs when an adversary can control a small fraction of the training data used to train a model and can select data that will corrupt the model in a focused way. For example, a spam detection model might be poisoned to misclassify the adversary’s messages as non-spam.

Adversarial machine learning researchers, like Evans’ team, are concerned with developing machine learning algorithms that are robust against these types of attacks. The key to doing this is first uncovering how models are vulnerable to adversaries—people who want to exploit computing systems to do things their designers did not intend.

Although “adversary” might bring malintent to mind, the label is strictly a classification in the field of adversarial machine learning.

“If the National Security Agency uses a threat model to uncover terrorists’ messages to protect the public, they are still the adversary in that they are breaking what the system was intended to do,” Evans said. “As researchers, we first try to design an attack and then test how successful that attack is in compromising a machine learning model, and use this to develop and evaluate defenses.”

“One way to do experiments is to have a bunch of models trained on different data sets and see if you can design an attack that can distinguish them and predict with high accuracy which dataset which model was trained on,” he said. “We are trying to understand what an attacker can learn from a model.”

Evans’ team is also concerned with assessing the damage that could result when adversaries exploit vulnerabilities.

“We can strategically think about the things that an adversary might actually be able to do with the information they glean from the model,” Evans said.

Discoveries made through the experiments answer open-ended questions in the field of adversarial machine learning about what defenses might actually be effective.

This May, Evans and two computer science students, 2021 bachelor’s degree recipient Jack Prescott and Ph.D. student Xiao Zhang, broadened global understanding of that possibility in a paper they presented at The International Conference on Learning Representations, a leading worldwide conference on machine learning research.

In <a href="https://uvasrg.github.io/improved-estimation-of-concentration-iclr-2021/">Improved Estimation of Concentration</a>, Evans, Prescott and Zhang showed that there are situations where you may be able to create an algorithm that is resistant to adversarial attacks. Specifically, they demonstrated that previous results showing it is impossible to build robust models against adversarial inputs may be overcome.

“We focused on a commonly used attack scenario in the adversarial machine learning field right now and we were able to produce an algorithm that we believe could be used as a building block to build better defenses,” Zhang said.

“There was previous research that pointed to the idea that developing a strong defense like this would not even be possible,” Prescott said. “Our research took a second look, and we applied our ideas to real-world data sets that showed promising results.”

Their work builds on findings in a 2019 paper published in NeurIPS, a top machine learning conference, by Zhang and Evans and their UVA Engineering collaborators: Saeed Mahloujifar, who completed a computer science Ph.D. at UVA and is now at Princeton University, and Mohammad Mahmoody, associate professor of computer science.

<a href="https://papers.nips.cc/paper/2019/file/46f76a4bda9a9579eab38a8f6eabcda1-Paper.pdf" target="_blank">Empirically Measuring Concentration</a> examined a theoretical conclusion that it would be impossible to protect a model from being tricked into producing wrong results on crafted inputs close to normal inputs. The UVA researchers focused on the assumptions that had been applied to the data. They relaxed those assumptions to develop a general methodology that could potentially be applied to machine learning image datasets.

Under the new assumptions for image data sets, the original theoretical conclusion of impossibility did not hold, indicating defenses might be possible. That breakthrough laid the foundation for further advances to see how low the limits could be, which is what Prescott, Zhang and Evans did.

The trio’s improvement upon the previous results indicate that it is still a good idea to pursue stronger defenses. Their work also exemplifies how advances in theoretical fields, made one discovery at a time, create building blocks that are harbingers of practical defenses.

Evans’ group is also focused on contributing to scientific understanding of privacy risks with machine learning. He recently shared <a href="https://uvasrg.github.io/iclr-dpml-2021-inference-risks-for-machine-learning/">insights</a> on behalf of his UVA research team that includes third-year computer science student Katherine Knipmeyer and computer science Ph.D. students Bargav Jayaraman and Anshuman Suri.

Their work identifies ways that attackers might be able to uncover a particular record that is part of a data set used to train a model. Attackers can even find out statistical facts about the underlying distribution of data that is used to train a model – for example, the percentage of males and females in face recognition data.

Knipmeyer became interested in the research as a first-year student when she attended professor Evans’ lecture for UVA undergraduates interested in science. “I just found his presentation so interesting, and I reached out to get involved,” she said.

“It was definitely one of the driving forces, and an important factor, in deciding to become a computer science major,” Knipmeyer said. “Instead of learning things that are established and known about the field, we are on the edge of it and exploring questions that are not defined or known yet.”

The research area was a new direction for Jayaraman and Suri as well.

“My research prior to joining UVA was in secure computation and I intended to study security risks with machine learning. In working with professor Evans, I discovered how open-ended the questions are surrounding privacy risks,” Jayaraman said. “Even when computations themselves are secure, attackers are still able to glean sensitive data. I wanted to apply what can be learned about privacy risks to improve machine learning algorithms.”

Suri was prompted to move into the new focus as a Ph.D. student by a first-hand encounter with the privacy risks he now researches.

“I was working with machine learning models in a different area of research when our team started to realize there were some underlying properties we could infer from the models,” said Suri. He transitioned his research and joined Evans’ research group. The pivot led to additional benefits for Suri.

“Professor Evans always helps you step back and look at the bigger picture. He asks the important questions about why you designed an experiment a certain way,” Suri said. “Observing his analytical process, through the questions he asks, has helped me think critically about the most effective ways to conduct my research.”

“That has been the most valuable thing, and I feel like there is a lot that I can learn from him.”
</div>
