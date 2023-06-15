# Text-Weak-Supervision

Description

Weak supervision has many potential areas of application within our customer community. The 2023 SEED project on Low Label Learning implemented a very light-weight version of weak supervision for the CIFAR-10 (image) dataset, where weak labels were generated with the CLIP image-to-text model. Since the weak labels generated were highly accurate on this benchmark dataset, we just used them to train in a normal way. 

A more realistic scenario is that we have very poor labeling knowledge and we have to rely on very weak rules for the generation of weak labels (e.g. this text says “good” so it must be positive sentiment or “this entity is numbers so it might be a phone number”). These will need to adapt as part of the learning process to essentially learn patterns that enable ML. The literature review for the LLL project identified packages such as Snorkel and Squeak for weak supervision on text data. 

The purpose of this ticket is to better understand how “proper” weak supervision is done in practice, with a focus on text data and develop a demonstrable capability to do weak supervision for NLP tasks. Primarily named entity recognition and classification.
