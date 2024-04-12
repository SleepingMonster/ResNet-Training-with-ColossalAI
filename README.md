# ResNet Training with ColossalAI

The code is mainly adapted from the example in ColossalAI [here](https://github.com/hpcaitech/ColossalAI/blob/main/examples/images/resnet/train.py).

- model: ResNet18

- dataset: CIFAR-10 dataset

- parallel settings: this code is run in google colab, so no parallel is set.

- how to run the code:

  - set up the environment: `pip install -r requirements.txt`
  - run the jupyter notebook: run the `Resnet-ColossalAI.ipynb`.

- experiment results:

  | Model    | Dataset  | Epoch | Training Loss | Test Accuracy |
  | -------- | -------- | ----- | ------------- | ------------- |
  | ResNet18 | CIFAR-10 | 40    | 0.212         | 83.42%        |

  