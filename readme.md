# Batch Normalization

## Introduction

Batch Normalization is one of the many techniques that are used to optimize **Neural Networks**. It simply normalizes the values in every layer then scales and shifts them to create a new *distribution* at each layer intstead of zero mean and unit variance. We use `gamma` and `beta` to scale and shift the values. This scaling and shifting makes sure that data is not the same in every layer and it also helps in **regularizing** the network since both gamma and beta add's some random *noise* to the data.

In the original paper the authors mentioned to use the batch norm layer after linear transformation `WX + B` and before the activation. However it gave great results when batch norm layer is used after the activation.

> I implemented batch norm layer after the activation int the notebook.

> You can read the [Original Paper](https://arxiv.org/abs/1806.02375) for more understanding

