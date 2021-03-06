# Summary

* [前言](README.md)
* [第1章 认识Elasticsearch](chapter-1/README.md)
   * [认识Apache Lucene](chapter-1/11_README.md)
       * [熟悉Lucene](chapter-1/111_README.md)
       * [总体架构](chapter-1/112_README.md)
       * [分析你的文本](chapter-1/113_README.md)
       * [Lucene查询语言](chapter-1/114_README.md)
   * [认识 ElasticSearch](chapter-1/12_README.md)
       * [基本概念](chapter-1/121_README.md)
       * [ElasticSearch背后的核心理念](chapter-1/122_README.md)
       * [ElasticSearch的工作原理](chapter-1/123_README.md)
   * [本章小结](chapter-1/13_README.md)
* [第2章 强大的用户查询语言DSL](chapter-2/README.md)
   * [Lucene默认打分算法](chapter-2/21_README.md)
   * [查询重写机制](chapter-2/22_README.md)
   * [查询结果的重打分](chapter-2/23_README.md)
   * [批处理](chapter-2/24_README.md)
   * [查询结果的排序](chapter-2/25_README.md)
   * [Update API](chapter-2/26_README.md)
   * [使用filters优化查询](chapter-2/27_README.md)
   * [filters和scope在ElasticSearch Faceting模块的应用](chapter-2/28_README.md)
   * [本章小结](chapter-2/29_README.md)
* [第3章 索引底层控制](chapter-3/README.md)
   * [改变Lucene的打分模型](chapter-3/31_README.md)
   * [相似度模型的配置](chapter-3/32_README.md)
   * [使用Codec机制](chapter-3/33_README.md)
   * [近实时搜索，段数据刷新，数据可见性更新和事务日志](chapter-3/34_README.md)
   * [深入了解文本处理流程](chapter-3/35_README.md)
   * [段合并的底层控制](chapter-3/36_README.md)
   * [本章小结](chapter-3/37_README.md)
* [第4章 探究分布式索引架构](chapter-4/README.md)
   * [选择恰当的分片数量和分片副本数量](chapter-4/41_README.md)
   * [路由功能浅谈](chapter-4/42_README.md)
   * [调整集群的分片分配](chapter-4/44_README.md)
   * [改变分片的默认分配方式](chapter-4/43_README.md)
   * [查询的execution preference](chapter-4/45_README.md)
   * [学以致用](chapter-4/46_README.md)
   * [本章小结](chapter-4/47_README.md)
* [第5章 管理Elasticsearch](chapter-5/README.md)
   * [选择正确的directory实现类——存储模块](chapter-5/51_README.md)
   * [Discovery模块的配置](chapter-5/52_README.md)
   * [索引段数据统计](chapter-5/53_README.md)
   * [理解ElasticSearch的缓存](chapter-5/54_README.md)
   * [本章小结](chapter-5/55_README.md)
* [第6章 应对系统突发状况](chapter-6/README.md)
   * [了解垃圾收集器](chapter-6/61_readme.md)
   * [什么是I/O过载——I/O限流](chapter-6/62_readme.md)
   * [运用数据预热加速查询](chapter-6/66_readme.md)
   * [耗CPU线程的处理](chapter-6/63_readme.md)
   * [真实业务场景](chapter-6/65_readme.md)
   * [本章小结](chapter-6/66_README.md)
* [第7章 优化用户体验](chapter-7/README.md)
* [第8章 ElasticSearch Java API](chapter-8/README.md)
* [第9章 开发ElasticSearch插件](chapter-9/README.md)

