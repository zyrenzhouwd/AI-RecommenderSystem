## Description：
这里的代码实践部分分为两个文件夹， FM和FFM。 代码的逻辑结构是这样：
1. FM: 这里面分为了掉包和造轮子分别实现了一下FM， 掉包版中又分别有简单上手(这里面通过一个分类一个回归的小例子）用了一下FM， 分类和回归任务实战， 这里面的分类任务使用的数据集是kaggle上的
点击率预测的数据集， 而回归任务还是电影评分的数据集， 具体的可以看文件夹的代码。 造轮子版实现了一个分类任务， 数据集依然是点击率预测的数据集。
2. FFM： 这里面参考了一篇文章， 简单从头开始实现了一下FFM， 这个可以具体了解一下思想， 尤其是考虑了域问题之后， 如果再进行特征交叉的时候计算权重。
