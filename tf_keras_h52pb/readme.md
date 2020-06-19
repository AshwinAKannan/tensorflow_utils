This tool/script was used when the model had to be converted to .pb format for TF1.14 + CPP deployment code

> the model was trained in Keras/TF2.0\n 
> TF-CPP build was version 1.14


# in TF2.0 env
1. load trained model
2. save model weights

# in TF1.14 env
1. initialize model architecture
2. load the weights saved above
3. save the model
4. run freeze_model.py command (command provided in jupyter-notebook)


NOTE: saving model weights is different from saving the model.

