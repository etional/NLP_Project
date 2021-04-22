# NLP_Project
Setup Steps:
1 . clone the branch .
2. Install the dependenciese using mentioned in the requirement.txt .command : pip install -r requirement.txt
3. To install sentence transformer from UKLAB , command: pip install -U sentence-transformers



****** ALL THE OUTPUTS are in OutputFiles directory 


Models Implemented :

1.Naive Bayes :
  We implemented a Naive Bayes Model
  To Run : python model_architectures/Naive_Bayes_Toxic_Comments.py 


2:BiLSTM - based Model
  For this model we used SBERT vector embeddings as input . We tried with both "Input -> BiLSTM -> flatten -> dense"  and "Input -> BiLSTM -> BiLSTM-> flatten ->     dense.
  How to run.
  1) Prepare the vector embedding by running , command : python data_preprocessing/sentence_bert_embedding.py
  2) Run the run_BiLSTM.py , command : python model_architectures/run_BiLSTM.py
 
