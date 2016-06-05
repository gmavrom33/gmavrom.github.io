---
layout: post
title: “A discussion on Global Sensitivity Analysis tools“
permalink: global-sensitivity-analysis
---

One of the computational technique groups that I am using as part of my PhD thesis is Global Sensitivity Analysis (SA). 

Saltelli et al. (2008) define Sensitivity Analysis as the study that identifies “how uncertainty in the output of the model (numerical or otherwise) can be apportioned to different sources of uncertainty in the model input”.

In my PhD, I am using these techniques to identify the most important input parameters that drive the variation of my models’ output. More details as to how I use Sensitivity Analysis can be found [here](http://mavromatidis.me/my-phd/).

Therefore, pretty early on in my PhD I was facing the task of selecting a tool that would allow me to perform this analysis. Some of the criteria that I had in order to select the best tool for me were the existence of multiple SA methods in the tool, ease of use and ease to integrate the tool with my current workflow. I was and still am mostly a Matlab user.

With this post, I would like to present the range of tools that I found and tested, provide a brief description and then, finally, justify the tool that I chose for my work.

1) SIMLAB

When one becomes interested in SA, it is inevitable that they will come across the name of Andrea Saltelli.

It was developed

It is a very comprehensive

It has the advantage that it offers an GUI that allows somebody with no coding experience perform sampling of uncertain parameters and then SA in an easier way.

However, I preferred 

2) [UQLab](http://www.uqlab.com) (Matlab)

As I mentioned earlier, Matlab is my current choice as a scripting language. Therefore, I was very pleased to find out about the tool UQLab.

UQLab, based in Matlab, has been developed by the group of [Uncertainty Quantification and Risk Analysis][] at ETH Zürich. Similarly to SIMLAB it also offers 

The advantage it has compared to all the other tools that I found is that it offers modules that allow the development of meta-models

3) [SALib](https://github.com/SALib/SALib) (Python)

SALib is 

4) 