# Refining-a-probabilistic-cross-impact-methodology-for-scenario-analysis
Matlab implementation of a cross-impact methodogy for generating Bayes-networks based on expert judgments. Majority of this code is based on Juho Roponen's implementation of the original methodology here: https://github.com/juropo/cross-impact  . The methodology is detailed in the file Haapasalo_Tuomas_2025.pdf

This new methodology is based on the original paper by Juho Roponen and Ahti Salo.

The code was developed only for this research paper and might not be trivially applicable to other contexts.

## Summary

Scenario analysis is an important tool for supporting managerial decision-making. Preparing for the unexpected is increasingly relevant, as demonstrated by the unforeseen recent developments such as the COVID-19 pandemic, the conflict in Ukraine, and the Gaza war. Examining alternative futures may reveal hidden vulnerabilities or strengths. Scenario thinking breaks narrow-mindedness and helps overcome cognitive biases by bringing surprising scenarios into consideration.

The field of scenario analysis methods is broad and diverse. By and large, there are qualitative and quantitative methods, as well as combinations thereof. Another major distinction can be made between methods that utilize probabilities and those that do not. At the core of these methods are the ways of scenario construction. Examples of systematic methods that account for mutual dependencies of uncertainty factors are cross-impact analysis methodologies, in general, choosing a suitable method depends on the intended use and context. In this thesis, we examine whether a probabilistic cross-impact analysis method can be enhanced by changing the interpretation of the cross-impact term with the odds-ratio.

The applicability of the new asymmetric cross-impact term was evaluated by examining the effects of its asymmetry on the functionality of the method. The original model was modified to support the new interpretation, whereafter the distributions produced by both methods were compared using statistical and visual tests. The most important observations included the apparent similarity of the joint probability distributions for the most probable scenarios and significant differences for the remaining scenarios. Computationally, neither method was faster than the other. The conclusion is that both interpretations are viable.
