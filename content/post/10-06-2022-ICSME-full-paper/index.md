---
title: An accepted paper in ICSME 2022
date: 2022-14-06
---

Congratulations to Thanh Le-Cong, Dr. Bach Le and Prof. Quyet-Thang Huynh for the acceptance of their ICSME 2022 (Rank A, Acceptance Rate = 23%) full research paper titled "FFL: Fine-grained Fault Localization for Student Programs via Syntactic and Semantic Reasoning"

<!--more-->

Fault localization has been used to provide feedback for incorrect student programs since locations of faults can be a valuable hint for students about what caused their programs to crash. Unfortunately, existing fault localization techniques for student programs are limited because they usually consider either the program’s syntax or semantics alone. This motivates the new design of fault localization techniques that use both semantic and syntactical information of the program.

In this paper, we introduce FFL (Fine grained Fault Localization), a novel technique using syntactic and semantic reasoning for localizing bugs in student programs. The novelty in FFL that allows it to capture both syntactic and semantic
of a program is three-fold: (1) A fine-grained graph-based representation of a program that is adaptive for statement-level fault localization; (2) an effective and efficient model to leverage the designed representation for fault-localization task and (3) a node-level training objective that allows deep learning model to learn from fine-grained syntactic patterns. We compare FFL’s effectiveness with state-of-the-art fault localization techniques for student programs (NBL, Tarantula, Ochiai and DStar) on two real-world datasets: Prutor and Codeflaws. Experimental results show that FFL successfully localizes bug for 84.6% out of 2136 programs on Prutor and 83.1% out of 780 programs on Codeflaws concerning the top-10 suspicious statements. FFL also remarkably outperforms the best baselines by 197%, 104%, 70%, 22% on Codeflaws dataset and 10%, 17%, 15% and 8% on Prutor dataset, in term of top-1, top-3, top-5, top-10, respectively.