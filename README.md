# NLP_POS_Tagging

**AUTHORS**

{ giorgio.adragna, chiara.bellatreccia, francesco.cavaleri2, marcello.mancino }@studio.unibo.it

**OVERVIEW**

Modern day reaserch has managed to obtain astonishing results for POS tagging, basically solving it: state-of-the-art models manage to achieve an impressive result of 97% accuracy (Akbik et al., 2018). However, these solutions are highly dependent on substantial computational power and really large datasets, and this is often impractical. We investigate how far we can get within a constrained setting: a small dataset and a group of very simple models. Under these circumstances, we tried to squeeze the best out of our models in terms of runtime performance and robustness. Other than the obvious generalization issues coming from such a small domain, the main challenge of POS tagging is the fact that it is intrinsically unbalanced, and it is only natural that the vast majority of the (much limited) capacity of the model is employed for the more frequent tags, resulting in a poor performance for the minority classes. Given these premises, results were satisfactory, managing to consistently obtain a macro F1 score greater than 0.8. We also discovered that, probably because our baseline reaches perfect accuracy on training data, augmenting its capacity with one additional layer does not necessarily yield better results.
