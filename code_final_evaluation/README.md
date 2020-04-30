### This folder contains the files and code that is used to generate the final results for the project.
### We will guide you with task performed by each file.
#
#### train.py
First file called to parse the command line arguments like training mode or validation mode or testing mode.
#### train_extractive.py
Responsible for training the model across various threads in training/validation/testing mode.
#### distributed.py
Spawn thread for multithreading and collect results from the threads
#### logging.py
Manages logs
#### pyrouge.py
ROUGE calculation function
#### utils.py
Utility function for final ROUGE calculation
#### adam.py
Manages Adam optimizer function
#### data_loader.py
Responsible for handling data (loading + creating batchs) requested by the models
#### decoder.py
Manages the transfomer's decoder layer
#### encoder.py
Manages the transformer's encoder layer 
#### loss.py
Manages loss calculation during training
#### model_builder.py
Builds the model (Bert_base + Classifier, Bert_base + Transformer or Bert_large) and the optimizer (Adam optimizer)
#### neural.py
Building the Multiheaded attention portion of the transformer
#### Optimizer.py
Manages the gradient calculations and weight updates for the model
#### trainer_ext.py
Utility function for trainer function
#### reporter_ext.ext
Utility function for Logger







