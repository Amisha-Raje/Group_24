# EMOTION CAUSE EXTRACTION USING GRAPHS TO CAPTURE THE FLOW OF THE CONVERSATION

This project focuses on annotating clauses within dialogues to identify emotions and their underlying causes using graph-based neural networks.​

## Features
Clause Segmentation: Breaks down dialogues into individual clauses.

Emotion & Cause Annotation: Labels clauses based on keyword matching and semantic similarity.

Graph Construction: Represents dialogues as graphs, capturing relationships between clauses.

Graph Neural Network Training: Utilizes a Graph Convolutional Network (GCN) to learn patterns for accurate annotation.​

## Dataset
The project utilizes the DailyDialog dataset, a manually labeled multi-turn dialogue dataset rich in emotional content. For emotion-cause annotations, we refer to the RECCON dataset, which provides annotations of cause spans corresponding to emotion utterances in conversations.

All training and evaluation were conducted in Google Colab, leveraging GPU acceleration for efficient computation.
