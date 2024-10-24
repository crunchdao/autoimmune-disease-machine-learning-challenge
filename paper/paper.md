---
title: "Autoimmune Disease Machine Learning Challenge"
subtitle: "YOURSUBTITLE"
author: [Eric and Wendy Schmidt Center at the Broad Institute,Klarman Cell Observatory at the Broad Institute,Crunch Foundation,Foundry Institute]
date: "yyyy/mm/dd"
lang: "en"
colorlinks: true
titlepage: true
titlepage-text-color: "FFFFFF"
titlepage-rule-color: "360049"
titlepage-rule-height: 0
titlepage-background: "./figures/cover.pdf"
header-left: "\\hspace{1cm}"
header-right: "Page \\thepage"
footer-left: "Footer left"
footer-right: "Footer right"
abstract: "Autoimmune diseases occur when the immune system- our body's defense system- mistakenly attacks healthy cells. They affect 50M people in the United States, with rates rising globally. Inflammatory bowel disease (IBD) is one of the most common types of autoimmune disease."
---

# Introduction

Autoimmune diseases occur when the immune system- our body's defense system- mistakenly attacks healthy cells. They affect 50M people in the United States, with rates rising globally. Inflammatory bowel disease (IBD) is one of the most common types of autoimmune disease. IBD occurs when the barrier between our gut and the microbes living there breaks down, leading to the activation of the immune system in response to proteins that are erroneously recognized as foreign. The immune system's persistent activation results in chronic inflammation, with cycles of flares and remission, and increases the risk of developing cancer. Before modern treatments, mortality was often greater than 50\%. Today still, IBD is a multifaceted disease with causes that are difficult to disentangle, one that is hard to treat because of its complex symptoms, and one that severely impacts patients' lives. %This sentence makes it sound like IBD may be a solved problem. Add sth about the current challenges; e.g. how hard it is to find the right treatment for people, what it means for their quality of life, etc.

Common symptoms of IBD include abdominal pain, diarrhea, and weight loss. A gastroenterologist can notice these clinical symptoms, but the diagnosis of IBD relies on performing an endoscopy (extracting a section from a patient's gut) and analyzing images of the gut tissue in consultation with a highly-trained pathologist. These images are essential for patient treatment as they guide not just the diagnosis of IBD, but also the choice of drugs that are best suited for the patient, and may help predict whether the patient is likely to develop colorectal cancer. Notably, the risk of colorectal cancer can be up to two-fold higher in IBD patients, but this cancer is highly treatable if detected during early screening. 

Worldwide, pathologists have collected millions of gut tissue images across hospitals, making these images a treasure trove of data, and an enormous opportunity for machine learning to impact patient health. 

Complementing these images collected by pathologists, the revolution in genomics over the past twenty years has enabled us to measure the activity of genes directly within these gut tissues, uncovering  details a pathologist cannot identify from the images alone and providing an opportunity to unveil the pathways underlying the disease. Such spatial genomics measurements will enable the next generation of IBD treatments by revealing which cells are interacting to cause the disease. However, such measurements are very expensive and time-intensive to obtain. 

What if we could use machine learning to connect the tissue images routinely collected by pathologists with higher-resolution but expensive, and therefore rarer, spatial genomics measurements? The resulting high-resolution and large-scale view of IBD could improve patient diagnosis, better guide the choice of drug treatment, and help identify and treat colorectal cancer earlier. 

This is where you come in. We need computational approaches to connect pathology images and spatial genomics images. You will develop algorithms that use the images of a tissue collected by a pathologist to infer the high-resolution view of tissue visible in spatial genomics: the cells and genes driving disease. We will use your models  to identify genes that are markers of potential cancerous regions in the gut, and we will then perform experiments to test these predictions in patient samples.

# Conclusions

Enjoy!

# References
