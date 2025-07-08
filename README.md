# -Transfer-Learning-with-Self-Supervised-Pre-training-and-U-Net-for-Neonatal-Brain-MRI-Segmentation
Datasetlink:-https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation
Key Highlights
 Self-Supervised Learning (SSL) for pretraining on unlabeled neonatal brain MRI scans.

 Transfer Learning to fine-tune a U-Net model on a small labeled dataset.

 Segmentation Task targeting pixel-wise delineation of brain tissue or anomalies.

 Modular, research-ready code structure.

 Objective
Train a U-Net segmentation model that generalizes well even when labeled data is limited, by leveraging robust representations learned via SSL.

 Methodology
SSL Pretraining:

Pretrained on a large corpus of unlabeled neonatal brain MRIs
Self-supervised tasks include:
Image reconstruction
Contrastive learning
Context prediction
Transfer Learning:
SSL-weights are transferred to initialize a U-Net
U-Net is then fine-tuned using the small labeled segmentation dataset

Segmentation:
Model trained to output pixel-level masks
Evaluated using metrics like IoU, Dice coefficient, pixel accuracy

