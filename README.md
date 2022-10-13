## Table of Contents

### Session 1 Examples

* [data_parallel_pytorch_code_changes](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/data_parallel_pytorch_code_changes)
This example points basic code changes when you bring a PyTorch script to use SageMaker distributed training library data parallelism.

* [data_parallel_tensorflow_code_changes](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/data_parallel_tensorflow_code_changes)
This example points basic code changes when you bring a Tensorflow script to use SageMaker distributed training library data parallelism.

* [huggingface_data_parallelism_checkpointing](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/huggingface_data_parallelism_checkpointing)
This example shows how to leverage SageMaker checkpointing to save transformer checkpoints during SageMaker distribued training (data parallelism) and resume training from checkpoints.

* [huggingface_data_parallelism_incremental_training](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/huggingface_data_parallelism_incremental_training)
This example shows how to do SageMaker distributed training (data parallelism) with HuggingFace framework and how to do incremental training from a saved model artifact.

-----

### Session 2 Examples

* [byos_pytorch](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/byos_pytorch)
This example takes PyTorch framework as an example to show how to bring your own script to train and deploy a model on SageMaker.

* [byoc_pytorch](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/byoc_pytorch)
This example shows how to extend AWS pre-built deep learning container (PyTorch as an example) to build your own container and bring it to SageMaker for model training.

* [xgboost_builtin_distributed](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/xgboost_builtin_distributed)
This example shows doing distributed training with SageMaker built-in XgBoost algorithm, and using SageMaker automatic model tuning to tune model hyperparameters.

* [xgboost_script_mode_distributed](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/xgboost_script_mode_distributed)
This example shows how to leverage pre-built XgBoost framework container to train a XgBoost model in a distributed training fashion.

* [xgboost_pyspark](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/xgboost_pyspark)
This example shows using SageMaker pre-built Spark container to train a XgBoost model. Note: notebook is tested on SageMaker classic notebook instance.