# E-Summ : Investigating Entropy for Extractive Document Summarization

This repository contains Python (v 3.7) scripts for implementation of E-Summ for extractive single document summarization.

**E-Summ** : _E-Summ_ follows an information theoretic approach for unsupervised, extractive single document summarization. The proposed _E-Summ_ algorithm is domain-,
collection-independent and is agnostic to the language of the document. Moreover, the method is explainable and fast enough to meet realtime requirements for on-the-fly summarization of web documents in languages other than English.

**Author:** Alka Khurana
**Acknowledgement:** Vasudha Bhatnagar

# Citation:  

```
@article{khurana2021investigating,
  title={Investigating entropy for extractive document summarization},
  author={Khurana, Alka and Bhatnagar, Vasudha},
  journal={Expert Systems with Applications},
  pages={115820},
  year={2021},
  publisher={Elsevier}
}
```
# Pipeline:
1. Clone the complete directory.
2. Put the documents in the Documents folder for which summary is to be generated.
3. In all the .py files, change the current directory to working directory of your system.
4. Run Preprocessing.py for pre-processing the input documents.
5. Run Find_Topics.py to find the number of latent topics in the document.
6. Run E-Summ.py  for generating the summary E-Summ summary of the document.


