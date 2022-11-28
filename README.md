# Neural Style Transfer
This project implements neural transfer using VGG19 model. Here the content image is stylised using style image.

Figure 1:
<img src="https://www.tensorflow.org/static/tutorials/generative/style_transfer_files/output__UWQmeEaiKkP_0.png" width="800"/>

The generated image (Figure 2):
<img src="https://www.tensorflow.org/static/tutorials/generative/style_transfer_files/output_q3Cc3bLtoOWy_0.png" width="300">

The cost function for this problem has cost from both content ans style image. The relative contribution of both is decided by hyperparameters.
The core of the algorithm is the style cost function which has gram matrix at its core.

<img src="http://ziqingguan.net/wp-content/uploads/2020/06/NST_GM-1-1536x508.png" width="600">
