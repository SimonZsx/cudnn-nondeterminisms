# cudnn-nondeterminisms
  
[reduce_sum tensorflow floating point addition is not associative](https://jkschin.com/2017/06/30/non-determinism.html)

two sigma workaround 
https://www.twosigma.com/insights/article/a-workaround-for-non-determinism-in-tensorflow/


CUDNN  
https://stackoverflow.com/questions/50744565/how-to-handle-non-determinism-when-training-on-a-gpu

Tensorflow used some of the CUDNN fwd convolution algorithms 
https://github.com/tensorflow/tensorflow/blob/master/tensorflow/stream_executor/cuda/cuda_dnn.cc#L250

Non-determinism in LSTM 
https://github.com/pytorch/pytorch/issues/18110
