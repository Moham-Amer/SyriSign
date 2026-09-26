# SyriSign

Arabic text to Syrian Arabic Sign Language (SyArSL) translation — Informatics Engineering graduation project, Arab International University.

## About

Sign language is the primary means of communication for the Deaf and Hard-of-Hearing community — but in Syria, most information (news, education, everyday content) exists only as spoken or written Arabic, leaving that community without access. Before this project, there was no publicly available dataset for Syrian Arabic Sign Language.

SyriSign introduces a parallel corpus of 1,500 video samples spanning 150 unique lexical signs, built specifically for text-to-SyArSL translation. The dataset is intended for public release as an initial benchmark for the field.

## Approach

We evaluated the dataset on three deep learning architectures:
- **MotionCLIP** — semantic motion generation
- **T2M-GPT**  — text-conditioned motion synthesis
- **SignCLIP** — bilingual embedding alignment

## Results

Across all three, generative approaches showed real promise for representing signs — but the dataset's size constrained how well the models generalized. That's an expected, honest limitation for a first-of-its-kind, low-resource dataset, and part of the motivation for releasing it publicly as a benchmark others can build on.


## Recognition
- Preprint: [arxiv.org/abs/2603.29219](https://arxiv.org/abs/2603.29219)
- Top 6 finalist, IEEE Jordan Section Contest 2026

## Authors
Mohammad Amer Khalil, Raghad Nahas, Ahmad Nassar, Khloud Al Jallad — Arab International University
