# ImSarcasist-v1

<!--https://github.com/Ordnmash/portfolio-website/blob/62690039fc21b24d5af17b659d3f5814d382e064/ImSarcasist.png-->
<p align="center">
  <img src="https://github.com/Ordnmash/portfolio-website/blob/62690039fc21b24d5af17b659d3f5814d382e064/ImSarcasist.png" width="800" height="400" alt="ImSarcasist image">
</p>

ImSarcasist is a Language modeling NN, built to learn sarcasic humor across the dataset. It uses `LSTMs` architecture for version 1. <br>
With LSTMs it's able to keep memory and context across longer sentences which allows the model to learn further sentences. <br>
<hr>
The size of this model is `3-layers` with `250k parameters` and it results in loss roughly `train_loss = 1.412604` and `val_loss = 1.446190`.<br>
And it samples sarcasms like:
- What do you call a woman accounted? A prostitute.
- A well what meal. Chicken Jobs Drymple.
<br>
yet it really struggles with grammar and exact word spelling, because it tries to generate words like as it's a character language modeling `CLM`.
