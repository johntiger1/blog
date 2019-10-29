---
title: "Whats in a Name Review"
date: 2019-10-29T13:21:25-04:00
draft: False
tags: 
- review
- peer-review
- NAACL
- future-directions
---

Paper review:
(What’s in a Name? Reducing Bias in Bios Without Access to Protected Attributes) [https://arxiv.org/abs/1904.05233]

Overall, I have a negative opinion of this paper. It introduces a novel way of bias mitigation, but provides little theoretical justification for why such an approach is useful, and also does not compare their work with any previous work. More over, I am extremely skeptical of the entire point of their paper, which is that we do not have access to protected attributes and so should find a way of providing fairness without looking at protected attributes. While it is reasonable that we might not have access to protected attributes, they propose providing proxy fairness through a person's name. In this sense, they are just treating name as a protected attribute! This defeats the entire point of the paper. In other words, if they show that name is actually encoding so much societal bias, then in fact it IS a protected attribute and should be removed from the dataset. This is a problem of imputed bias; we can simply impute the sensitive attributes from a strongly correlated feature such as name. Indeed, they do show that just running k-means on the names alone clusters for race, gender etc. 

Overall, this seems like a course project that could have been completed in CSC2541. Surprisingly, it won best thematic paper at NAACL(!)

As an opposite viewpoint, it is comforting that such types of papers can make it into ACL, and I am inspired to write something similarly short, simple and sweet. 

Doing some additional research on the first authour, we see that they are a legend and should serve as a role model for acolyte researchers everywhere: http://www.cs.uml.edu/~aromanov/files/alexey_romanov_cv_2019_v4.pdf 
