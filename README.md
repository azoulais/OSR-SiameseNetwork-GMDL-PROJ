# OSR-using-SiameseNetwork-GMDL-PROJ
Unlike traditional classification problems, where a model is trained and tested on the same set of classes, OSR(Open Set Recognition) refers to a scenario where, in addition to the known classes the classifier was trained on, additional new classes might be present during test-time. In fact, this is closely related to the problem of out-of-distribution (OOD) detection.
<br />
As part of the course “Graphical Models and Deep Learning” we were given the task of tackling the OSR problem and indeed after some research I hve found out that many of the known algorithms for the OSR problem try to embed the data in some way and then work on these embeddings. A reasonable requirement for such embedding, in my opinion, could be that in the embedding space samples with the same label would be "close" to each other and samples of different classes will be "far". This basic logic led me to use a paradigm called “Contrastive Learning”.Thus my model implies Contrastive Learning using a Siamese network architecure and it can be found in the attached .ipynb file.

