# cudnn-nondeterminisms


NVIDIA Deep Learning Non-determinism
[github](https://github.com/NVIDIA/tensorflow-determinism)
[video](https://www.youtube.com/watch?v=TB07_mUMt0U)
[slides](https://developer.download.nvidia.com/video/gputechconf/gtc/2019/presentation/s9911-determinism-in-deep-learning.pdf)


Tensorflow training non-determinism
[reduce_sum tensorflow floating point addition is not associative](https://jkschin.com/2017/06/30/non-determinism.html)

[two sigma workaround](https://www.twosigma.com/insights/article/a-workaround-for-non-determinism-in-tensorflow/)


CUDNN  
https://stackoverflow.com/questions/50744565/how-to-handle-non-determinism-when-training-on-a-gpu

Tensorflow used some of the CUDNN fwd convolution algorithms 
https://github.com/tensorflow/tensorflow/blob/master/tensorflow/stream_executor/cuda/cuda_dnn.cc#L250

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





