# **BERT4Rec - Treatment Recommendation System**

## **Overview**
**This is a static code that shows the code of **"bert4rec"** using a treatment dataset.**
This project implements a BERT4Rec model to predict the next treatment in a sequence of medical treatments. It leverages Transformer-based architectures to learn patterns from historical treatment sequences and suggest the most probable next step in a patient’s care plan.

## **Features:**
* Implements BERT4Rec, a Transformer-based model for sequential recommendation.
* Uses Multi-Head Attention for learning contextual relationships between treatments.
* Supports variable-length sequences using padding to ensure consistency.
* Provides next treatment prediction as the output.
* Uses TensorFlow and Keras for deep learning implementation.
* Includes data preprocessing steps like sequence padding and encoding.

## **Dataset:**
* This model requires a dataset where each patient’s treatments are represented as sequences. The dataset should include:
* Treatment sequences: A list of treatments received by a patient over time.
* Target labels: The next treatment to be predicted based on past treatments
