# LLM-Guided-GA
![LLM_GA(3)](https://user-images.githubusercontent.com/81431282/233686394-0a5158af-6733-494d-812a-abe9bc607ab2.png)

Project made by Benjamin Weiser, Jerome Genzling, Nicolas Gastellu, Sylvester Zhang, Tao Liu and Alexander Alexander Al-Feghali, Department of Chemistry, McGill University, Montreal, Quebec; Canada

Part of McGill ChemAI submission to the first LLM Hackaton for Chemistry.

The goal of this work was to investigate the ability for a Language Learning Model (LLM) to work in parallel with genetic algorithms (GA) for molecular property optimization

This work explores the potential of LLMs to improve molecular fragmentation, mutation, variation, and reproduction processes and the ability of a LLM to gather information from a SMILES string and an associated score to produce new SMILES strings

We used GPT-3.5-Turbo as our Main LLM model for this work. To try our model, you can use our Jupyter Notebook LLM-Guided-GA.ipynb attached in this GitHub project. To make it work, you will need to insert your OpenAI Key at the top of the notbeook.

The LLM model used can be changed in the genLLM_ functions (more precisely in the OpenAi functions) accordingly to the OpenAI API documentation. 

You can learn more about this project in our related paper : LINK OF THE PAPER

ipynb file in files. Contains GA as well as LLM implementation.

Link to collab: https://colab.research.google.com/drive/1CRTSHzjja-GZ21v_0l-pWCHyZwgzspDj?usp=sharing
