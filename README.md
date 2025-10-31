# DeepKnowledgeTracing
This project implements a minimal Deep Knowledge Tracing (DKT) model using NumPy to simulate and track student skill mastery. The goal is to provide a clear, end-to-end example of a DKT-like model, including:
- Synthetic Data Generation: Creating simulated student interaction data based on defined skills, item difficulties, learner abilities, slip/guess probabilities, and learning gains.
- Q-Matrix: Defining the relationship between items and skills.
- Sequence Building: Transforming raw interaction data into sequences suitable for training a recurrent neural network (RNN).
- NumPy RNN Model: Implementing a simple RNN model from scratch with stable training techniques like lower learning rates and gradient clipping.
- Training and Evaluation: Training the DKT model on simulated data and evaluating its performance using metrics like Binary Cross-Entropy (BCE) loss and Area Under the ROC Curve (AUC).
- Skill Mastery Prediction: Using the trained model to predict per-skill mastery levels for a focal learner.
- Mock Test Recommendation: Recommending a personalized mock test based on the focal learner's predicted skill weaknesses.
This project serves as a baseline for understanding the core concepts of DKT and can be extended for more complex scenarios.
