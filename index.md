---
layout: page
title: FoMo lectures
---

# FoMo: Foundation models in Amsterdam

The FoMo lectures is a series of seminars highlighting the work being done in Amsterdam around _foundation models_: large, highly re-usable machine learning models trained on great amounts of data. These include large language models like GPT and generative vision models like DALLE·2, Stable Diffusion and Midjourney.

The talks are held alternately at the UvA and VU, and feature speakers from a variety of domains. They are intended for a technical audience.

The lectures are organized by [Cees Snoek](https://www.ceessnoek.info/) and [Peter Bloem](https://peterbloem.nl).

# Upcoming talks

<table><tr>
  <th>date</th><th>time</th><th>location</th><th>talks</th>
</tr><tr>
<td valign="top">June 27</td><td valign="top"> 12:00 </td><td valign="top"> VU, NU-3A67 </td><td markdown="1"> 
  
Tao Hu (UvA)
**Self-guided Diffusion Models**
Diffusion models have demonstrated remarkable progress in image generation quality, especially when guidance is used to control the generative process. However, guidance requires a large amount of image-annotation pairs for training and is thus dependent on their availability and correctness. In this paper, we eliminate the need for such annotation by instead exploiting the flexibility of self-supervision signals to design a framework for \textit{self-guided} diffusion models. By leveraging a feature extraction function and a self-annotation function, our method provides guidance signals at various image granularities: from the level of holistic images to object boxes and even segmentation masks. Our experiments on single-label and multi-label image datasets demonstrate that self-labeled guidance always outperforms diffusion models without guidance and may even surpass guidance based on ground-truth labels. When equipped with self-supervised box or mask proposals, our method further generates visually diverse yet semantically consistent images, without the need for any class, box, or segment label annotation. Self-guided diffusion is simple, flexible and expected to profit from deployment at scale.


  
Stefan Schouten (VU, CLTL)
**Reasoning about Ambiguous Definite Descriptions**
Natural language reasoning plays an increasingly important role in improving language models' ability to solve complex language understanding tasks. An interesting use case for reasoning is the resolution of context-dependent ambiguity.
In this talk, I will discuss ongoing work on the evaluation of LLMs w.r.t. their ability to use explicit reasoning for disambiguation. We propose to use ambiguous definite descriptions for this purpose and have created a benchmark dataset consisting of such phrases. 
</td>
</tr><tr>
<td valign="top">June 20</td><td valign="top"> 12:00 </td><td valign="top"> L3.36, Lab42 at UvA </td><td markdown="1"> 
[Selene Baez Santamaria](https://selbaez.github.io/) (VU, CLTL)
**A Practical Approach to GPTx Models: Insights on Task-Specific Performance**
Large language models have sparked extensive discussions in scientific communities and the general media over the past year. Particularly, OpenAI's decision to make their GPTx models available to the public has enabled millions of individuals (with sufficient economic resources and internet requirements) to utilize them. Within research, their API accessibility has made it possible to effortlessly explore these model's performance on a wide range of scientific tasks. In this talk, I will present my findings from three specific tasks: knowledge base completion, argument mining, and task-oriented dialogue incorporating subjective knowledge

  
[Francesco Manigrasso](https://www.polito.it/en/staff?p=francesco.manigrasso) (Department of Control and Computer Engineering, Politecnico di Torino)
**Knowledge Representation: Neurosymbolic Integration of Reasoning and Learning.**
Neuro-symbolic integration aims to leverage the power of symbolic knowledge representation along with the learning capabilities of deep neural networks. Specifically, Logic Tensor Networks (LTNs) enable the incorporation of background knowledge through logical axioms, grounding a first-order logic language as differentiable operations between real tensors. However, only a few studies have explored the potential benefits of this approach for enhancing object detection and zero-shot learning (ZSL) classification.
In this study, we focus on the subsumption of the isOfClass predicate, which plays a fundamental role in encoding most semantic image interpretation tasks. We introduce different architectures capable of merging LTNs with convolutional networks. FASTERLTN is an object detector composed of a convolutional backbone and a Logic Tensor Network, trained in an end-to-end manner. On the other hand, PROTOtypical Logic Tensor (PROTO-LTN) extends the current formulation of parametrized class prototypes in a high-dimensional embedding space.
We showed how these architectures can be effectively trained in object detection and zero-shot learning scenarios respectively.The proposed formulations open up new opportunities to integrate background knowledge in the form of logical axioms to compensate for the lack of labelled examples by introducing room for improving the capabilities of the learning model with a sufficient knowledge base.
</td>
</tr><tr>
<td valign="top">June 13</td><td valign="top"> 12:00 </td><td valign="top"> NU-3A06 at VU </td><td markdown="1"> 
Gabriel Bénédict (UvA) 
**RecFusion: A Binomial Diffusion Process for 1D Data for Recommendation**
Generative Information Retrieval (a.k.a. Generative Neural Search or chatGPT + attribution + no-hallucination) has experienced substantial growth across multiple research communities and has been highly visible in the popular press. Theoretical, empirical, and actual user-facing products have been released that retrieve documents (via generation) (Generative Document Retrieval) or directly generate answers given an input request (Grounded Answer Generation).
A subfield of Generative IR, Generative Recommendations, is still in its infancy. We propose RecFusion to use diffusion models to generate recommendations. We benchmark classical diffusion formulations (normal distribution for the forward and backward diffusion process, Unets and ELBO) against formulations fitted to the RecSys setting:  1D diffusion (user-by-user), binomial diffusion and multinomial loss (like in MultVAE). We also experiment with diffusion guidance to condition the generation of recommendation strips on movie genre (a.k.a. controllable recommendation).


Wouter van Atteveldt (VU)
**Are LLMs and Transfer Learning a game changer for Computational Social Science?**
A core part of computational social science is extracting structured data such as political topic or stances from unstructured data such as news, twitter, or tiktok feeds. Although Supervised Machine Learning has been part of our toolkit for at least two decades, it has traditionally suffered from data scarcity problems as the complex and shifting nature of social science concepts are unsuitable for large standardized data sets such as common in computer vision and NLP. BERT and other pre-trained models may well be a game changer here, as they can offer valid results even with relatively small data sets. We show empirically how BERT and BERT-NLI can be used for valid measurement of political communication concepts in a number of settings.

</td>
</tr><tr>
<td valign="top">June 6</td><td valign="top"> 12:00 </td><td valign="top"> L3.36, Lab42 at UvA</td> <td markdown="1">
Jan-Christoph Kalo (VU, L&R group)
**Knowledge Graph Construction with Large Language Models**
In recent years, researchers have started exploring the capabilities of Large Language Models (LLMs) to store relational knowledge. A controversial paper, Language Models as Knowledge Bases claimed in 2019 that LLMs might be able to replace knowledge graphs.
In this talk, we investigate the question if LLMs can replace KGs. We compare various methods for extracting factual knowledge from LLMs. Furthermore, we empirically evaluate what kind of knowledge is actually learned by LLMs.

Ivona Najdenkoska (UvA, AIM lab)
**Bridging Vision and Language for Multimodal Few-shot Learning**
Language models have made significant progress in recent years, particularly in scenarios with limited labeled data. These advancements in natural language processing have inspired similar efforts in the vision domain, resulting in models that demonstrate impressive few-shot and zero-shot image classification capabilities. However, the substantial domain gap between vision and language modalities presents a non-trivial challenge for combining them as multimodal few-shot learners. Visual data, characterized by pixel values, and language, reliant on symbolic representations, pose difficulties in aligning and integrating these modalities, while keeping their few-shot abilities. Existing methods attempt to communicate visual concepts as "prompts" to frozen language models, but they often rely on hand-engineered task induction to reduce the search space, which is not always optimal. This talk will present novel approaches for multimodal few-shot learning, that leverage the few-shot capabilities of large-scale pre-trained language models, while also emphasizing computational efficiency.
</td></tr>
</table>



