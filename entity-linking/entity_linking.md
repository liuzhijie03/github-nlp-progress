## 实体链指

### 1. DuEL_Dataset
- <strong>数据集简介：</strong>

    DuEL_Dataset是百度发布的中文短文本实体链指数据集。与以前的中文实体链指数据集相比，DuEL_Dataset的优势是（1）数据集规模大：DuEL_Dataset包含10w左右的中文短文本和覆盖39w实体的知识库。（2）数据质量高：DuEL_Dataset数据集由百度众包标注生成，知识库实体重复率约5%，实体尚未概念准确率95.27%，数据集标注准确率95.32%。

- <strong>数据集详情：</strong>

    |  名称 | 规模 | 创建日期 | 作者 | 单位 | 论文 | 下载 | 评测 |
    | :---: | :---:| :---: | :---: | :---: | :---: | :---: | :---: |
    | DuEL_Dataset |10w短文本，39w实体 | 2019年 |百度 | 百度 | N/A | [链接](https://biendata.com/competition/ccks_2020_el/data/)| [CCKS 2019: 面向中文短文本的实体链指任务](https://biendata.com/competition/ccks_2019_el/)|

- <strong>基于该数据集发表的相关论文：</strong>
    - 论文待明确


### 2. KBP 2017 EDL
- <strong>数据集简介：</strong>

### 3. 知识工厂数据集
- <strong>数据集简介：</strong>

    该数据集由1037条人工标注的中文短文本语料组成。其中大约70%来自新闻语料，包括新闻标题和内容，比如“英超-桑切斯4分钟内梅开二度阿森纳3-2五轮不败”；大约20%来自人工构建的基于歧义实体的语料，比如“红楼梦的演员有哪些”；大约10%来自问答语料中的简单问句，比如说“岳阳有哪些旅游景点”。

    数据标注的格式如下。每个样本的标注格式包括3个部分：语料，mention和实体，用制表符‘\t’分隔；其中mention为语料中指代实体的子段，多个用“|||”分隔；实体部分为各mention对应的实体，多个用“|||”分隔，数量应与mention一致。比如，“李娜拿过澳网冠军吗\t李娜|||澳网\t李娜（中国女子网球名将）|||澳大利亚网球公开赛”。

- <strong>数据集详情：</strong>

    |  名称 | 规模 | 创建日期 | 作者 | 单位 | 论文 | 下载 | 
    | :---: | :---:| :---: | :---: | :---: | :---: | :---: | 
    | 知识工厂数据集 | 1037条人工标注的短文本语料 | 2017年 | Bo Xu, Yong Xu, Jiaqing Liang, etc. | 知识工厂 | [链接](http://www.xumenger.com/download/20180820/CN-DBpedia-System.pdf) | [链接](https://github.com/clhisawolfman/chinese_entity_linking)| 

- <strong>基于该数据集发表的相关论文：</strong>
    - Bo Xu, Yong Xu, Jiaqing Liang, Chenhao Xie, Bin Liang, Wanyun Cui, and Yanghua Xiao. CN-DBpedia: A Never-Ending Chinese Knowledge Extraction System. In International Conference on Industrial, Engineering and Other Applications of Applied Intelligent Systems, pp. 428-438. Springer, Cham, 2017.


### 4. NLPCC 2015
- <strong>数据集简介：</strong>

    该任务来自NLPCC 2015评测任务，该任务的目标是对短queries中的实体进行识别并链接到对应的中文知识库中。本数据集包括一个中文知识库，该知识库来自各类中文百科的信息框，包括中文维基百科和百度百科。该数据集还包括每个实体页面的第一段作为该实体的摘要。这个知识库不可避免地含有部分噪音数据，但是相对容易访问，并且确实为每个实体提供了一个相对结构化的描述信息。有关该任务和数据集详细描述请见NLPCC 2015 Shared Task：http://tcci.ccf.org.cn/conference/2015/pages/page05_evadata.html
    
- <strong>数据集详情：</strong>

    |  名称 | 规模 | 创建日期 | 作者 | 单位 | 论文 | 下载 | 
    | :---: | :---:| :---: | :---: | :---: | :---: | :---: | 
    

- <strong>基于该数据集发表的相关论文：</strong>
    - Feng Y., Han Z., Zhang K. (2015) Overview of the NLPCC 2015 Shared Task: Entity Recognition and Linking in Search Queries. In: Li J., Ji H., Zhao D., Feng Y. (eds) Natural Language Processing and Chinese Computing. Lecture Notes in Computer Science, vol 9362. Springer, Cham

[回到首页](/README.md)
