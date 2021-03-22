## MUStARD *Extended* Multimodal Sarcasm Detection Dataset

This repository contains the dataset and code for our ACL 2020 paper: 
[Sentiment and Emotion help Sarcasm? A Multi-task Learning Framework for Multi-Modal Sarcasm, Sentiment and Emotion Analysis](https://www.aclweb.org/anthology/2020.acl-main.401/)

### Dataset
The original **MUStARD** dataset released in [Towards Multimodal Sarcasm Detection (An Obviously Perfect Paper)](https://www.aclweb.org/anthology/P19-1455/). The [MUStARD dataset](https://github.com/soujanyaporia/MUStARD) is a multimodal video corpus for research in automated sarcasm discovery. The dataset is compiled from popular TV shows including Friends, The Golden Girls, The Big Bang Theory, and Sarcasmaholics Anonymous. MUStARD consists of audiovisual utterances annotated with sarcasm labels. Each utterance is accompanied by its context, which provides additional information on the scenario where the utterance occurs.


### Dataset with Sentiment and Emotion (Implicit and Explicit)
We manually annotate this multi-modal **MUStARD** sarcasm dataset with *sentiment* and *emotion* classes, both implicit and explicit. You can download extended MUStARD datasets from [here](https://drive.google.com/drive/folders/1dJZyCSm80UZFHwbBRRg89njTDOwPkWa8?usp=sharing). 

### Model Description
* For multi-tasking, we propose two attention mechanisms, viz. Inter-segment Inter-modal Attention and Intra-segment Inter-modal Attention. 
* The main motivation of Inter-segment Inter-modal Attention is to learn the relationship between the different segments of the sentence across the modalities. 
* In contrast, Intra-segment Inter-modal Attention focuses within the same segment of the sentence across the modalities.




