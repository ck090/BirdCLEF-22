## # Visual Saliency Transformer (VST)

source code for our paper on "The birds need attention too: Analysing usage of Self Attention in identifying bird calls in soundscapes" by Chandra Kanth Nagesh and Abhishek Purushothama

<img width="855" alt="arch" src="https://user-images.githubusercontent.com/12717969/179869909-8a3244f2-3ce6-45f1-9701-76b419c547e3.png">

## Abstract
Birds are vital parts of ecosystems across the world and are an excellent measure of the quality of life on earth. Many bird species are endangered while others are already extinct. Ecological efforts in understanding and monitoring bird populations are important to conserve their habitat and species, but this mostly relies on manual methods in rough terrains. Recent advances in Machine Learning and Deep Learning have made automatic bird recognition in diverse environments possible. Birdcall recognition till now has been performed using convolutional neural networks. In this work, we try and understand how self-attention can aid in this endeavor. With that we build an pre-trained Attention-based Spectrogram Transformer baseline for BirdCLEF 2022 and compare the results against the pre-trained Convolution-based baseline. Our results show that the transformer models outperformed the convolutional model and we further validate our results by building baselines and analyzing the results for the previous year BirdCLEF 2021 challenge.

## Conclusion
Our experiments have shown that the Audio Spectrogram Transformer baseline outperforms the convolutional baseline. The AST which had been trained on audio sounds represented as spectograms, showed better performance than conventional visual style pre-trained EfficientNet. The goal of this was for recommendation of backbone for the BirdCLEF tasks. Using AST instead of convolutional backbones, may provide better performance in the task going forward. Even if it is not unequivocal, AST has to be is a for the task.

## Citation
