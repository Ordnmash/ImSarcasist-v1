# ImSarcasist-v1

ImSarcasist is a Language modeling NN, built to learn sarcasic humor across the dataset. It uses `LSTMs` architecture for version 1. <br>
With LSTMs it's able to keep memory and context across longer sentences which allows the model to learn further sentences. <br>
<b>
The size of this model is `3-layers` with `250k parameters` and it results in loss roughly `train_loss = 1.419459` and `val_loss = 1.452660`.<br>
And it samples sarcasms like:
- What do you call a woman accounted? A prostitute.
- A well what meal. Chicken Jobs Drymple.
<br>
yet it really struggles with grammar and exact word spelling, because it tries to generate words like as it's a character language modeling `CLM`.
