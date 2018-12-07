# torchvision
## `torchvisio.dataset`
### `torchvision.dataset` 包含了一下数据集
## `MNIST`
## `COCO`

### 所有的数据集都是 `torch.utils.data.Dataset` 的子集，即它们具有 \_\_getitem()\_\_ 和 ]_\_len()\_\_ 实现方法。因此，它们都可以传递给 `torch.utils.data.DataLoader` 。


# MNIST
## ``` dataset.MNIST(root, train=True, transform=None, target_transform=None, download=False) ```
## 参数说明
### `root` :数据集，存储在根目录中的数据
### `train` :True=训练集， False=测试集