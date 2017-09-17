### 常见问答

1. __如何应用关联数据能力指标？__  在LD4PE项目中，指标有两个主要的用途。它提供了关联数据领域的一个概览，老师和学习者可以使用此概览来设计大学课程，培训工作组或者自己制定学习计划。 它还提供了一组在元数据中使用的URI，根据主题或涵盖的能力来[标注培训资料](http://explore.dublincore.net/explore-learning-resources-by-competency/)。

2. __为什么这些能力不进行编号以便容易参考？__  能力指标会随着时间不断地进化。原则上，主题，能力或者基准可以随时添加到指标中，这样可能会改变任一顺序编号系统的序号。因此，我们可能偶尔会发行较为稳定的版本。在这种情况下, 需要修改[用来创建Markdown文档的Python脚本](https://github.com/dcmi/ldci/tree/master/docs/D2695955_to_md.py)，以 x (集群), x.x (主题), x.x.x (能力), x.x.x.x (基准)的形式计算条目的数量。  有编号的版本对指标的翻译者也会有帮助 (参见[中文翻译](http://explore.dublincore.net/wp-content/uploads/sites/2/2015/09/LD4PECompetencyIndex-chinese.pdf)。如果你对此问题非常感兴趣，请在Github问题追踪系统中[发起一个问题](https://github.com/dcmi/ldci/issues)。

3. __DCMI命名空间政策是否涵盖了能力的URI？__ [DCMI命名空间政策](http://dublincore.org/documents/dcmi-namespace/)列举了一些命名空间，这些命名空间的组织承诺保持命名空间的持久性和语义的稳定性。目前，所有的命名空间和PURL子域都在[purl.org](http://purl.org)解析服务下进行管理。LD4PE项目一开始，[成就标准网络](http://asn.desire2learn.com)就创建了关联数据能力指标中的“主题”和“能力”的URI，并进行管理。例如，主题“RDF识别”被URI [http://asn.desire2learn.com/resources/S2696001](http://asn.desire2learn.com/resources/S2696001)标识。 DCMI为了扩展命名空间政策覆盖这些URI，它需要更好的了解ASN关于持久性等的政策，需要在它的控制下创建dublincore.org 或PURL URI。从根本上说，我们应该问问自己，识别的持久性和语义的稳定性对指标有多重要？答案取决于在实践中使用能力指标的程度。我们可以从区分主题(和主题集群)开始, 主题不经常变化，在元数据中可以用来作为宽泛的主题标目。 但是能力（和基准）会随着技术的发展迅速被创建或者取代。在LD4PE项目中，能力URI用来[标注可以通过能力进行检索的培训资料](http://explore.dublincore.net/explore-learning-resources-by-competency/). 这些资料中的博客文章等资料将会被取代或不可用。作为这些资料的标签的“能力”真的需要比所描述的资源本身具有更轻的持久性吗？如果你对这个问题非常感兴趣， 请在Github问题追踪系统中[发起一个问题](https://github.com/dcmi/ldci/issues)。

