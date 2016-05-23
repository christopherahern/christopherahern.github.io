---
layout: post
title: Check dis out
---

Source code for a draft of a new paper with [Meredith Tamminga](https://www.meredithtamminga.com) and [Aaron Ecay](https://aaronecay.com)
is [available on github](https://github.com/christopherahern/GAM-DH). We use generalized additive models to simultaneously
estimate the effect of priming and style-shifting on the use of DH-stopping variants: 

* Check *this* out! 
* Check *dis* out!
 
The basic intuition is that there are at least two potential sources of repetition when we observe multiple variants of the
same kind. On the one hand we have priming, which is the cognitive tendency to repeat recently used variants. If you just said *this*, 
then you're more likely to say *this* again. On the other hand we have style-shifting, which is the social use of variants
to signal information according to the context of the discussion. If the conversation is formal, you're more likely to  use *this* 
if it's informal you're more like to use *dis*.  

While we might expect priming to be fairly uniform across speakers and contexts, each of those individual contexts is unique. Still,
we'd like to be able to simultaneously estimate how the previously used variant and the context influence the next variant.
Generalized additive models are a great way of doing this because they allow us to model the effect of priming while also 
modeling the effect of style shifting as a smooth function of time. Since we have
no prior expectation about how a sociolinguistic interview might go, GAMs allow for the right kind of flexibility. 

Here's the abstract:

> Intraspeaker variation is typically characterized by repetitiveness in variant choice, but there are multiple possible sources of such repetitiveness. We distinguish two types of clustering: sequential dependence, which we associate with priming, and baseline deflection, which we associate with style-shifting. We argue that because both priming and style-shifting are likely to be at play in producing observed quantitative patterns, it is desirable to adopt quantitative models that can simultaneously estimate sequential dependence and baseline deflection as distinct sources of temporal clustering. We propose the use of Generalized Additive Models (GAMs) for this purpose. We test the use of GAMs on a case study of DH-stopping in Philadelphia English sociolinguistic interviews and find that the resulting parameter estimates are reasonable given basic expectations about how style and priming should be distributed across individuals. We advocate for the adoption of this and similar new tools to advance the integration of psycholinguistic, sociolinguistic, and corpus linguistic insights in the study of intraspeaker variation. 
  
