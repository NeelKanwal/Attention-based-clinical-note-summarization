# BERTOLOGY-Based-Extractive-Summarization-for-Clinical-Notes
Link to preprint: https://arxiv.org/abs/2104.08942
Link to paper: https://dl.acm.org/doi/abs/10.1145/3477314.3507256

# Requirments
- simpletransformers
- jsonline
- seqval
- tensorboardx
- transformers
- Spacy
- regex
- Betviz

  
# Demo Version of MIMIC-III
https://physionet.org/content/mimiciii-demo/1.4/

# Abstract
In recent years, the trend of deploying digital systems in numerous industries has hiked. The health sector has observed an extensive adoption of digital systems and services that generate significant medical records. Electronic health records contain valuable information for prospective and retrospective analysis that is often not entirely exploited because of the complicated, dense information storage. The crude purpose of condensing health records is to select the information that holds the most characteristics of the original documents based on a reported disease. These summaries may boost diagnosis and save a doctor's time during a saturated workload situation like the COVID-19 pandemic. In this paper, we are applying a multi-head attention-based mechanism to perform extractive summarization of meaningful phrases on clinical notes. Our method finds major sentences for a summary by correlating tokens, segments, and positional embeddings of sentences in a clinical note. The model outputs attention scores that are statistically transformed to extract critical phrases for visualization on the heat-mapping tool and for human use.

<img width="448" alt="image" src="https://github.com/NeelKanwal/Attention-based-clinical-note-summarization/assets/52494244/dc878f0a-296a-4b33-bccc-0197b4e49276">


# Vizualization using Neat-Vision

<img width="200" alt="image" src="https://github.com/NeelKanwal/Attention-based-clinical-note-summarization/assets/52494244/d888d912-9e01-4afd-b0d6-c7ee95820ea1">



if you use this work, or improve this further; please cite this; 
```
@inproceedings{kanwal2022attention,
  title={Attention-based clinical note summarization},
  author={Kanwal, Neel and Rizzo, Giuseppe},
  booktitle={Proceedings of the 37th ACM/SIGAPP Symposium on Applied Computing},
  pages={813--820},
  year={2022}
}
```
