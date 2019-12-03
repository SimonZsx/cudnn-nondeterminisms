# cudnn-nondeterminisms


### NVIDIA Deep Learning Non-determinism

[github](https://github.com/NVIDIA/tensorflow-determinism)

[video](https://www.youtube.com/watch?v=TB07_mUMt0U)

[slides](https://developer.download.nvidia.com/video/gputechconf/gtc/2019/presentation/s9911-determinism-in-deep-learning.pdf)



### CUDNN Algorithms 

[Workaround] https://github.com/tensorflow/tensorflow/issues/12871

Tensorflow used some of the CUDNN fwd convolution algorithms 
https://github.com/tensorflow/tensorflow/blob/master/tensorflow/stream_executor/cuda/cuda_dnn.cc#L250

Page 21 

http://hpc.pku.edu.cn/docs/20170830182053891231.pdf

CUDNN autotune
https://blog.csdn.net/jiangbo1017/article/details/79351775


CUDNN_CONVOLUTION_BWD_FILTER_ALGO_0 (non-deterministic)

CUDNN_CONVOLUTION_BWD_FILTER_ALGO_1

CUDNN_CONVOLUTION_BWD_FILTER_ALGO_FFT

CUDNN_CONVOLUTION_BWD_FILTER_ALGO_3 (non-deterministic)

CUDNN_CONVOLUTION_BWD_FILTER_ALGO_WINOGRAD (not implemented)

CUDNN_CONVOLUTION_BWD_FILTER_ALGO_WINOGRAD_NONFUSED

CUDNN_CONVOLUTION_BWD_FILTER_ALGO_FFT_TILING


### Deconvolution Layer 

https://datascience.stackexchange.com/questions/6107/what-are-deconvolutional-layers

### Tensorflow training non-determinism

[reduce_sum tensorflow floating point addition is not associative](https://jkschin.com/2017/06/30/non-determinism.html)

[two sigma workaround](https://www.twosigma.com/insights/article/a-workaround-for-non-determinism-in-tensorflow/)

[MNIST](https://gist.github.com/anonymous/d277be86320a0a3d47c2f141881c9a1a)





CUDNN  
https://stackoverflow.com/questions/50744565/how-to-handle-non-determinism-when-training-on-a-gpu



Non-determinism in LSTM 
https://github.com/pytorch/pytorch/issues/18110

Research on reproducibility in Reinforcement Deep Learning
https://prabhatnagarajan.com/publications/2018/nagarajanrml2018.pdf



TensorRT Nondeterminism / Timing Determinism
https://github.com/NVIDIA/TensorRT/issues/44


CPU Threading
https://stackoverflow.com/questions/54047654/tensorflow-different-results-with-the-same-random-seed



MXNet autotune ???
https://github.com/apache/incubator-mxnet/issues/16173





