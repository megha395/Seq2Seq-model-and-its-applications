# Math-word-problem-and-Geometric-problems
This repository contains the implementations of the Seq2Seq model, a Transformer model and a Geometric word problem solver model. 
The setup was tested with python 3.6, tensorflow 2.x version. Anaconda python distribution is recommended.

Datasets:
The Sigma Dolphin dataset was used for the baseline model Seq2Seq with teacher forcing only. Whereas, the Seq2Seq model with attention mechanism and the transformer model uses MaWPs dataset and Dolphin 18K dataset. Links for these datasets are provided in the references.

Models:
  1. The baseline model is Seq2Seq with only teacher forcing. There is no attention mechanism used in this model. It is available in the file: Baseline_Seq2Seq_for_MWPs.ipynb
  2. The Seq2Seq model with both attention mechanism and teacher forcing is available in the file: Seq2Seq_with_attention_for_MWPs.ipynb
  3. The transformer model is available in: Transformer_model_for_MWPS.ipynb
  4. Geo solver model solves geometric word problem. It consists of a Seq2Seq model integrated with a memory network and a shape detector. It is available in: Geo_solver_model.ipynb

References:
https://www.microsoft.com/en-us/research/project/sigmadolphin-2/
GitHub - RahulSharmaNITT/MathWordProblem: Question Generator for math word problem.
https://github.com/tensorflow/nmt

