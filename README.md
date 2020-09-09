# Model-Based Deep Learning for One-Bit Compressive Sensing

This repository contains the codes used in the following paper: <br><br>

Shahin Khobahi and Mojtaba Soltanalian, "[Model-Based Deep Learning for One-Bit Compressive Sensing](https://ieeexplore.ieee.org/document/9187438)," in IEEE Transactions on Signal Processing, doi: 10.1109/TSP.2020.3022319. 

<br><br>
For any further questions regarding the code contact at shahin [dot] khobahi [at] gmail.com

## Abstract
In this work, we consider the problem of one-bit deep compressive sensing from both a system design and a signal recovery perspective. In particular, we develop hybrid model-based deep learning architectures based on the deep unfolding methodology. We further interpret the overall data-acquisition and signal recovery modules as an auto-encoder structure allowing for learning task-specific sensing matrix, quantization thresholds, as well as the latent-parameters of iterative first-order optimization algorithms specifically designed for the problem of one-bit sparse signal recovery. The proposed model-based deep architectures have the ability to adaptively learn the proper quantization thresholds, paving the way for amplitude recovery in one-bit compressive sensing. We further show that the proposed methodology implicitly learns task-specific sensing matrices with very low coherence, which is highly desirable in a compressive sensing setting. Due to the model-based nature of the proposed deep architecture, it enjoys from the interpretability and versatility of model-based techniques as well as benefiting from the expressive power of data-driven methods. Specifically, owing to its model-based nature, it has far fewer parameters and requires far less samples for training as compared to black-box machine learning models. Our results demonstrate a significant improvement compared to state-of-the-art algorithms.
