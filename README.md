# detection-of-fabric

## Prepare
### Environments
>> 1. Python3.6
>> 2. pytorch >=1.1
>> 3. cuda >=9.0
>> 4. gcc >=4.9
>> 5. nccl 2


### Installation
>> <br> Please run setup.py for installation and dataset preparation. 

## Run
use the following command to test a dataset.
```shell
python tools/test.py ${CONFIG_FILE} ${CHECKPOINT_FILE} [--out ${RESULT_FILE}] [--eval ${EVAL_METRICS}] [--show]
```
use the following command to train a dataset.
```shell
python tools/train.py ${CONFIG_FILE}
```
