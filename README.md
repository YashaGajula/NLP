# NLP
Transformative QA: Analyzing BERT, ALBERT, RoBERTa and BERT-RoBERTa Ensembles.
This research presents a comprehensive evaluation of question answering models trained on the Stanford Question Answering Dataset (SQuAD), leveraging the transformative
power of Bidirectional Encoder Representations from Trans-
formers (BERT), A Lite BERT (ALBERT), and an innovative
ensemble approach combining BERT and RoBERTa. We metic-
ulously trained and evaluated each model, achieving remarkable
F1 scores. Initially, we explored the BERT model, renowned for
its deep contextual representations. Subsequently, we employed
ALBERT, chosen for its efficiency and compact model size
while maintaining performance comparable to BERT. Finally,
we implemented a novel ensemble model that amalgamates
BERT and RoBERTa, aiming to harness the strengths of both
models and further enhance question answering capabilities.
This paper elucidates the detailed methodology of our training
process, model architectures, data preprocessing techniques, and
evaluation metrics employed. Our findings contribute significant
insights into the development of high-performing question an-
swering systems and highlight the potential of ensemble models
in attaining state-of-the-art results. This work not only sets a
standard for future research efforts in question answering model
creation, but it also advances the field of Natural Language
Processing (NLP).    
![image](https://github.com/YashaGajula/NLP/assets/170789442/1edfef11-b668-44f0-a0cd-36462e3ef4c9)
![image](https://github.com/YashaGajula/NLP/assets/170789442/fb3cd474-b023-4eb0-8c58-7cff1c071e26)
![image](https://github.com/YashaGajula/NLP/assets/170789442/bbd33ffe-f10d-4c24-943a-7e376ff7ffc4)
#RESULTS
All four models (BERT, ALBERT, RoBERTa, and
BERT+RoBERTa) have achieved impressive performance on
the SQuAD dataset for question answering. As depicted in the
graph, Figure. 2, Figure. 3, the F1 scores ranging from 82.60
(BERT) to 83.40 (BERT+RoBERTa ensemble) and Exact
Match scores from 74.53 (BERT) to 75.20 (BERT+RoBERTa
ensemble) are quite high and close to the state-of-the-art
performance on the SQuAD dataset.The BERT+RoBERTa
ensemble model has outperformed the individual BERT,
ALBERT, and RoBERTa models, albeit marginally. This
suggests that combining the strengths of these transformer-
based language models can lead to improved performance
on question answering tasks.The ALBERT model, which is
a lighter and more efficient variant of BERT, has performed
slightly better than the original BERT model. This is an
interesting observation as it demonstrates that more efficient
models like ALBERT can achieve comparable or even better
results than their larger counterparts, potentially making them
more suitable for resource-constrained environments.These
transformer-based language models are developing to the
point that they can perform well on question answering
tasks such as SQuAD, as seen by the comparatively minor
performance discrepancies amongst the four models.Though
the difference is not significant, RoBERTa, an optimized
variant of BERT, has outperformed both BERT and ALBERT.
This could imply that while the optimizations in RoBERTa
are beneficial, the core architecture of these models is the
primary driver of their performance on question answering
tasks.
