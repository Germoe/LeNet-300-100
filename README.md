# Description of Simple Feed-Forward Fully Conntect Network

This implementation is based on the paper [Lottery Ticket Hypothesis](https://arxiv.org/abs/1803.03635) by Jonathan Frankle and Michael Carbin. It doesn't implement the pruning but only the training of the Fully-Connected Network as described in Figure 2 under LeNet-300-100.

The parameters are set to the default and achieve a similar validation accuracy of ~98% after 50 epochs.

## Usage

Make sure to install the requirements.txt file.

```bash
pip install -r requirements.txt
```

To train the network run start the jupyter server and run the notebook.

```bash
jupyter notebook
```

If you're running this on your personal computer and do not have access to a GPU, it might take a while to train the network. You can reduce the number of epochs to speed up the training process. Otherwise, feel free to deploy the notebook on Google Colab with a T4 machine.


