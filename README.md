## Table of Contents

---

### Session 1 Hands-on Labs

* [data_parallel_pytorch_code_changes](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/data_parallel_pytorch_code_changes)
points basic code changes when you bring a PyTorch script to use SageMaker distributed training library data parallelism.

* [data_parallel_tensorflow_code_changes](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/data_parallel_tensorflow_code_changes)
points basic code changes when you bring a Tensorflow script to use SageMaker distributed training library data parallelism.

* [huggingface_data_parallelism_checkpointing](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/huggingface_data_parallelism_checkpointing)
shows how to leverage SageMaker checkpointing to save transformer checkpoints during SageMaker distribued training (data parallelism) and resume training from checkpoints.

* [huggingface_data_parallelism_incremental_training](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/huggingface_data_parallelism_incremental_training)
shows how to do SageMaker distributed training (data parallelism) with HuggingFace framework and how to do incremental training from a saved model artifact.

---

### Session 2 Hands-on Labs

* [byos_pytorch](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/byos_pytorch)
takes PyTorch framework as an example to show how to bring your own script to train and deploy a model on SageMaker.

* [byoc_pytorch](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/byoc_pytorch)
shows how to extend AWS pre-built deep learning container (PyTorch as an example) to build your own container and bring it to SageMaker for model training.

* [xgboost_builtin_distributed](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/xgboost_builtin_distributed)
shows doing distributed training with SageMaker built-in XgBoost algorithm, and using SageMaker automatic model tuning to tune model hyperparameters.

* [xgboost_script_mode_distributed](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/xgboost_script_mode_distributed)
shows how to leverage pre-built XgBoost framework container to train a XgBoost model in a distributed training fashion.

* [xgboost_pyspark](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/xgboost_pyspark)
shows using SageMaker pre-built Spark container to train a XgBoost model. Note: notebook is tested on SageMaker classic notebook instance.

### Session 3 Hands-on Labs

* [feature_store](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/feature_store)
Example use case with Offline Feature Store SDK and create dataset

* [spark_distributed_data_processing](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/spark_distributed_data_processing)
Example use case with Distributed Data Processing using Apache Spark and SageMaker Processing

* [sagemaker_pipelines](https://github.com/SherryXDing/yahoo-sagemaker-training/tree/main/sagemaker_pipelines)
Example use case with SageMaker Pipelines which includes Processing, Training, Evaluation, Condition and Model Registry Steps 
 