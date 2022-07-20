# The birds need attention too

source code for our paper on "The birds need attention too: Analysing usage of Self Attention in identifying bird calls in soundscapes" by Chandra Kanth Nagesh and Abhishek Purushothama

<img width="855" alt="arch" src="https://user-images.githubusercontent.com/12717969/179869909-8a3244f2-3ce6-45f1-9701-76b419c547e3.png">

## Abstract
Birds are vital parts of ecosystems across the world and are an excellent measure of the quality of life on earth. Many bird species are endangered while others are already extinct. Ecological efforts in understanding and monitoring bird populations are important to conserve their habitat and species, but this mostly relies on manual methods in rough terrains. Recent advances in Machine Learning and Deep Learning have made automatic bird recognition in diverse environments possible. Birdcall recognition till now has been performed using convolutional neural networks. In this work, we try and understand how self-attention can aid in this endeavor. With that we build an pre-trained Attention-based Spectrogram Transformer baseline for BirdCLEF 2022 and compare the results against the pre-trained Convolution-based baseline. Our results show that the transformer models outperformed the convolutional model and we further validate our results by building baselines and analyzing the results for the previous year BirdCLEF 2021 challenge.

## Conclusion
Our experiments have shown that the Audio Spectrogram Transformer baseline outperforms the convolutional baseline. The AST which had been trained on audio sounds represented as spectograms, showed better performance than conventional visual style pre-trained EfficientNet. The goal of this was for recommendation of backbone for the BirdCLEF tasks. Using AST instead of convolutional backbones, may provide better performance in the task going forward. Even if it is not unequivocal, AST has to be is a for the task.

## Results
Out of our six planned and we trained only 5 models except PANN-Bird-21, one of them unsuccessfully, namely PANN-Bird-22.

For our PANN-Bird models we re-used the original code from the PANNs paper available publicly.. Our attempts at training PANN-Bird-22 failed as our model did not converge even with attempts to tune with some of the hyperparameters. However, due to this reason we do not attempt to train PANN-Bird-21, and provide a strong alternative to convolution pre-trained models which is the EfficientNet pre-trained backbone to provide contrast to the AST Backbone. Hence, making sure that we provide the right comparison and contrast to our experiments.

<img width="437" alt="image" src="https://user-images.githubusercontent.com/12717969/179870344-5f8a9c91-4d4f-4fc9-a8ab-1799f1364e4c.png">
<img width="478" alt="image" src="https://user-images.githubusercontent.com/12717969/179870449-a0a4f1f8-af08-42a7-83ae-75e19d371546.png">

## Citation
