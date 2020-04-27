## 实体链指

### 1. DuEL_Dataset
- <strong>数据集简介：</strong>

    DuEL_Dataset是百度发布的中文短文本实体链指数据集。与以前的中文实体链指数据集相比，DuEL_Dataset的优势是（1）数据集规模大：DuEL_Dataset包含了10w左右的短文本。（2）数据质量高：DuEL_Dataset数据集由百度众包标注生成，知识库实体重复率约5%，实体尚未概念准确率95.27%，数据集标注准确率95.32%。

- <strong>数据集详情：</strong>

    |  名称 | 规模 | 创建日期 | 作者 | 单位 | 论文 | 下载 | 评测 |
    | :---: | :---:| :---: | :---: | :---: | :---: | :---: | :---: |
    | DuEL_Dataset |10w | 2020年 |百度 | 百度 | -| [链接](https://biendata.com/competition/ccks_2020_el/data/)| [CCKS 2020: 面向中文短文本的实体链指任务](https://biendata.com/competition/ccks_2020_el/） |

- <strong>基于该数据集发表的相关论文：</strong>
    - 论文待明确


### 2. KBP 2017 EDL
- <strong>数据集简介：</strong>

### 3. chinese_entity_linking
- <strong>数据集简介：</strong>

    数据集的文本由1037条人工标注的短文本语料组成。其中大约70%来自新闻语料，包括新闻标题和内容，比如“英超-桑切斯4分钟内梅开二度阿森纳3-2五轮不败”；大约20%来自人工构建的基于歧义实体的语料，比如“红楼梦的演员有哪些”；大约10%来自问答语料中的简单问句，比如说“岳阳有哪些旅游景点”。

    数据标注的格式如下。每个样本的标注格式包括3个部分：语料，mention和实体，用制表符‘\t’分隔；其中mention为语料中指代实体的子段，多个用“|||”分隔；实体部分为各mention对应的实体，多个用“|||”分隔，数量应与mention一致。比如，“李娜拿过澳网冠军吗\t李娜|||澳网\t李娜（中国女子网球名将）|||澳大利亚网球公开赛”。

    目前，我们的实体识别与链接技术在该数据集上能达到很好的效果。其中实体识别部分的准确率为91.0%，召回率为89.4%，F1分数为90.2%；实体链接部分的准确率为94.5%（实体识别后单独计算的实体链接准确率）；针对实体识别与链接任务的准确率为86.1%，召回率为84.5%，F1分数为85.3%。

- <strong>数据集详情：</strong>

    |  名称 | 规模 | 创建日期 | 作者 | 单位 | 论文 | 下载 | 
    | :---: | :---:| :---: | :---: | :---: | :---: | :---: | 
    | chinese_entity_linking | 1037条人工标注的短文本语料 | 2017年 | Bo Xu, Yong Xu, Jiaqing Liang, etc. | Shanghai Key Laboratory of Data Science, School of Computer Science, Fudan University, Shanghai, China | [链接](http://www.xumenger.com/download/20180820/CN-DBpedia-System.pdf) | [链接](https://github.com/clhisawolfman/chinese_entity_linking)| 

- <strong>基于该数据集发表的相关论文：</strong>
    - Bo Xu, Yong Xu, Jiaqing Liang, Chenhao Xie, Bin Liang, Wanyun Cui, and Yanghua Xiao. CN-DBpedia: A Never-Ending Chinese Knowledge Extraction System. In International Conference on Industrial, Engineering and Other Applications of Applied Intelligent Systems, pp. 428-438. Springer, Cham, 2017.


### 4. NLPCC 2015
- <strong>数据集简介：</strong>

    该任务来自NLPCC 2015评测任务，该任务的目标是对短queries中的实体进行识别并链接到对应的中文知识库中。本数据集包括一个中文知识库，该知识库来自各类中文百科的信息框，包括中文维基百科和百度百科。该数据集还包括每个实体页面的第一段作为该实体的摘要。这个知识库不可避免地含有部分噪音数据，但是相对容易访问，并且确实为每个实体提供了一个相对结构化的描述信息。有关该任务和数据集详细描述请见NLPCC 2015 Shared Task：http://tcci.ccf.org.cn/conference/2015/pages/page05_evadata.html



[回到首页](/README.md)
