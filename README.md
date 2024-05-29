# Multiscale Weisfeiler-Leman Directed Graph Neural Networks for Prerequisite-Link Prediction
<font size=4>Authors: Yupei Zhang IEEE Member, Xiran Qu, Shuhui Liu, and Xuequn Shang</font>
## Overview
>  Prerequisite-link prediction (PLP) aims to discover the condition relations of a specific event or a concerned variable, which is a fundamental problem in a large number of fields, such as education data mining. Current studies on PLP usually developed graph neural networks (GNNs) to learn the representations of pairs of nodes. However, these models fail to distinguish non-isomorphic graphs and integrate multiscale structures, leading to the insufficient expressive capability of GNNs. To this end, we in this paper proposed *k*-dimensional Weisferiler-Leman directed GNNs, dubbed *k*-WediGNNs, to recognize non-isomorphic graphs via the Weisferiler-Leman algorithm. Furthermore, we integrated the multiscale structures of directed graphs into *k*-WediGNNs, dubbed multiscale *k*-WediGNNs, from the bidirected views of in-degree and out-degree. With the Siamese network, the proposed models are extended to address the problem of PLP. Besides, their expressive powers are analyzed through promising proofs. The experiments were conducted on four publicly available datasets for concept prerequisite relation prediction. The results show that the proposed models achieve better performance than the state-of-the-art methods, where the multiscale *k*-WediGNN reaches the best performance among all compared models.
## Multiscale *k*-WediGNN
![k-WediGNN](k-wedi.png)
## The Used Datasets
Experiments were performed on four knowledge component (KC) datasets, encompassing diverse subject areas from both online and offline courses. These datasets include:
- DSA
- ML
- LectureBank
- University Courses
## Experiment
To showcase the superiority, we compared our methods with the traditional binary classification models developed in CPRP,including Support Vector Machine (SVM), Naive Bayes (NB),, and as well as the state-of-the-art approaches, including:
- Graph Autoencoder (GAE) and Variational Graph Autoen-coder (VGAE) [28].
- Reference Distance (RefD) [30].
- Prerequisite Prediction (PREREQ) [26].
- Concept Prerequisite Relation Learning (CPRL) [31].
- Contextual-knowledge-aware approach (Conlearn) [5].
  
To investigate the improved discrimination, we canceled some components of multiscale k-WediGNNs as the references:
- GNN
- Multiscale GNN
- k-WediGNN
- k-WediGNN+Out-degree
- k-WediGNN+In-degree
## Visualizations of sample representations




 
