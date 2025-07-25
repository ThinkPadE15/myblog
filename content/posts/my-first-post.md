+++
title = "Tracing History Through Numbers"
description = "Using KL Divergence to Decode Ancient Scripts"
date = '2025-07-25T17:28:13+05:30'
draft = false
+++
**Read this thread to understand the context of the researcher:** [Here](https://x.com/khoomeik/status/1882058141145403817)  
**And these as well for more context:** [Here](https://x.com/TheButterThief/status/1882625712705909091) and [Here](https://x.com/yajnadevam/status/1882119943539556464)  

**Indus Script Corpus:** [Here](https://indusscript.net/)

---

Understanding ancient scripts is like opening a time capsule into history. The Indus Valley Script (IVS), one of the world’s oldest writing systems, remains undeciphered, leaving a significant gap in our knowledge of early Indian civilization.

Recently, a cryptographer named Yagnadevam claimed to decipher the ancient text as a cryptogram and proposed that the IVS might be linked to Sanskrit, one of the oldest known languages.

To explore this, they turned to a mathematical tool called KL divergence, which measures differences between patterns, such as sound frequencies in texts.

But can KL divergence prove that IVS is related to Sanskrit?

---

## What is KL Divergence?

KL divergence is a statistical measure that compares two distributions, it tells us how different two sets of data are. For example, if one city prefers biryani and another prefers chocolate, KL divergence can quantify that difference.

**Mathematically:**
![Mathematically](/images/pic1.webp)


KL divergence here compares the frequency of sounds or symbols in one text with another, It focuses on sound patterns but ignores grammar, syntax, and meaning—key aspects of language. For example, researchers might compare how often certain sounds appear in the Ṛgveda (an ancient Sanskrit text) and IVS. If the frequencies are similar, it could suggest a connection, but more linguistic evidence beyond phonetics is needed, such as analyzing grammatical structures, syntax, and semantics

## Historical Application to the Indus Valley Script (IVS)
### The Problem
The Indus Valley script consists of mysterious symbols. There is no agreed-upon translation. Some researchers theorize it may be an early or transitional form of Sanskrit.

### How KL Divergence Is Used
Researchers calculate the frequency of symbols in IVS and compare it to Sanskrit texts like the Ṛgveda.

They also compare it to unrelated languages like English to see how different they are.

![KL](/images/pic2.webp)

The diagonal values (e.g., Ṛgveda to Ṛgveda) are zero because any text compared to itself has no divergence.

IVT has a KL divergence of ~0.7 with the Ṛgveda, indicating some similarity but not close enough to be identical.

Classical Sanskrit texts (Ṛgveda, Manusmṛti, etc.) show extremely low KL divergence between each other (~0.05 or less), meaning they are closely related.

IVT's divergence with unrelated English texts (e.g., "Moby Dick") is ~3.5, far higher than its divergence with Sanskrit.

IVT is not Sanskrit, as its divergence from classical Sanskrit texts is far higher than their mutual divergence. This is based on the Phonetics alone

However, IVT models Sanskrit better than unrelated texts like the "Lorem Ipsum" model English, which shows it has some phonetic resemblance.

![Heatmap](/images/pic3.webp)

### Heatmap Analysis

Red means IVT underuses a sound compared to Ṛgveda, blue means overuses, and whiteish means it has ~ the same frequency.

Frequency ratios of sounds (akṣaras) in IVT compared to the Ṛgveda (left heatmap) and another Sanskrit text (Śatapathabrāhmaṇa, right heatmap).

Darker or brighter colors represent higher deviations in phoneme frequencies.

Left Heatmap (IVT vs Ṛgveda):

Significant differences in certain phonemes (e.g., "ā," "ai," and "au") indicate that IVT doesn’t fully align with Ṛgveda's phonetic patterns.

Right Heatmap (Śatapathabrāhmaṇa vs Ṛgveda):

Much smaller variations, as expected, since these are both classical Sanskrit texts.

### Findings

IVT’s phonetic structure differs significantly from the Ṛgveda and other classical Sanskrit texts, further suggesting it is not Sanskrit.

However, its phoneme patterns suggest some familiarity with Sanskrit's phonetic traditions, supporting the idea that it may represent an early or transitional form.


### Strengths of KL Divergence in Historical Analysis

Objectivity: It gives a quantitative way to compare languages, reducing bias.

Phonetic Insight: Highlights patterns in sound usage, which can reveal linguistic relationships.

Applicability: Works even with limited data, like the sparse symbols in IVS.
### Limitations of KL Divergence
Directionality: KL divergence depends on which language is the reference, potentially biasing results.

Phonetics Only: It looks at sound frequencies but ignores syntax, grammar, and meaning—critical for language identification.

Historical Evolution: Sanskrit evolved over the centuries. If IVS reflects an earlier or transitional stage, its differences could simply reflect this evolution.

Oversimplification: Language relationships are complex, and reducing them to symbol frequencies may miss deeper connections.

### What Does This All Mean?
Does KL divergence prove IVS is related to Sanskrit? The answer isn’t clear-cut.

If IVS Is Linked to Sanskrit
IVS may represent an early or transitional stage of Sanskrit, explaining phonetic differences.

A deeper analysis, including grammar and semantics, could strengthen this theory.

If IVS Is Not Linked to Sanskrit
The differences in phonetics might reflect a completely different language family.

Other tools, like syntax analysis or archaeological evidence, are needed to uncover IVS’s origins.

KL divergence is a powerful tool that offers insights into phonetic similarities between texts, but it has limitations. While it suggests some overlap between IVS and Sanskrit, it cannot conclusively prove a connection.

The importance of deciphering the Indus Valley script goes beyond linguistics, it could reshape our understanding of ancient history. What other tools or methods might help bridge this gap between symbols and meaning?

Image Credits and Acknowledgment
The images included in this post are sourced from @khoomeik, and full credit goes to their original creator, Rohan Pandey . These visuals have been used for illustrative purposes to support the ideas discussed in this article. If you are the rightful owner of any of these images and have concerns about their use, please feel free to contact me, and I will address the matter promptly, including removing the images if necessary.

Jai Hind