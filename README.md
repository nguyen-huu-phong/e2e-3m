# Rethinking Recurrent Neural Networks and other Improvements for Image Classification
For a long history of Machine Learning which dates back to several decades, Recurrent Neural Networks (RNNs) have been mainly used for sequential data and time series or generally 1D information. Even in some rare researches on 2D images, the networks merely learn and generate data sequentially rather than for recognition of images. In this research, we propose to integrate RNN as an additional layer in designing image recognition’s models. Moreover, we develop End-to-End Ensemble Multi-models that are able to learn experts’ predictions from several models. Besides, we extend training strategy and softmax pruning which overall leads our designs to perform comparably to top models on several datasets. The source code of the methods provided in this article is available in https://github.com/leonlha/e2e-3m and http://nguyenhuuphong.me.

## Results
Cifar-10: 98.36%</br>
Fashion-MNIST: 95.92%</br>
iNaturalist'19: 73.47%</br>
iCassava'19: 93.68%

## Prerequisites
We tested our codes for the following current version but later versions may work too</br>
For codes to run on Linux dedicated server:</br>
- Ubuntu 18.04.4 LTS</br>
- CUDA 9</br>
- TensorFlow 1.12.0</br>
- Keras 2.2.4</br>

For codes to run on Colab virtual server</br>

## Installation

## Citation
```citation
@misc{phong2020rethinking,
    title={Rethinking Recurrent Neural Networks and other Improvements for Image Classification},
    author={Nguyen Huu Phong and Bernardete Ribeiro},
    year={2020},
    eprint={2007.15161},
    archivePrefix={arXiv},
    primaryClass={cs.CV}
}
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
