# LUKE_first
LUKE任务,前边数据集部分源代码用了torch的dataloader，我用华为的GeneratorDataset处理后数据格式从Tensor变字符串了。问了老师这个问题。老师说前面定义数据集类时候数据已经是Tensor类型就不用再GeneratorDataset了。然后后面训练时训练非常慢。3个epoch就用了半小时。多几个epoch内核就崩溃了。LUKE类定义是我让gpt改的。
