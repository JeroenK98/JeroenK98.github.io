---
title: Projects
layout: default
nav_order: 3
---

# Projects

## No Class, No Style? Stylometry of Dutch hip-hop
{: .no_toc }

<span class="label label-blue">Stylometry</span> <span class="label">Python</span> <span class="label label-green">CHR 2027</span>

Nine Dutch rappers, 1995 to 2026. I separate *stylistic development* (change relative to an artist's own earlier work) from *stylistic individuation* (growing distance from contemporaries), using TF-IDF character n-grams on three-year windows, leave-one-out self-distance, peer-distance and bootstrap checks. Development is widespread; individuation is not: only two artists, Typhoon and Sef, drift away from their own past and from the field at the same time.

[Paper](#) · [Code](#)

## Multi-label topic detection in hotel reviews
{: .no_toc }

<span class="label label-blue">NLP</span> <span class="label">Python</span> <span class="label label-purple">Course project</span>

A multilingual classifier that assigns up to 20 topic labels to Booking.com review snippets, built for an NLP shared task in the MA Digital Text Analysis. The final system fine-tunes XLM-RoBERTa-base with class-weighted loss, per-label decision thresholds, and synthetic Dutch and Italian training data generated for the two unseen test languages. It reaches a validation macro F1 of 0.710 ± 0.005 over three seeds, against 0.425 for a TF-IDF baseline. Threshold tuning gave the largest gain (+0.09 to +0.13); targeted augmentation of rare labels gave none. Thresholds were tuned on the same small validation split, so this is likely an overestimate of test performance.

[Model on Hugging Face](https://huggingface.co/JeroenK98/xlmr-hotel-topic-detection) · [Code](#) · [System description paper]({{ '/assets/papers/Kole_System_Description_Paper.pdf' | relative_url }})

## ObjectenZoeker
{: .no_toc }

<span class="label label-blue">R Shiny</span> <span class="label">Historical data</span>

An R Shiny app for exploring which objects occur together in historical probate inventories, using Cramér's V and adjusted standardised residuals.

[Code](#)

## Room-level clustering of probate inventories
{: .no_toc }

<span class="label label-blue">Python</span> <span class="label">Dissertation</span>

A pipeline (multiple correspondence analysis followed by Ward clustering) that groups rooms by the objects they contain, to test whether rooms with different notarial labels, such as *voorkamer* and *salon*, were functionally the same. It gives a bottom-up check on how domestic space was actually used in 1835, 1880 and 1912.

## A digital edition (autumn 2026)
{: .no_toc }

<span class="label label-blue">Digital editing</span> <span class="label label-yellow">In progress</span>

For the course *Text as Data*. More soon.
