
需要改进：
1.定位原因：查看接口、日志
2.如何发现类似bug
3.复制代码，注意usercode的不同
4.同一接口，进入同一模块的所有入口
5.提高测试覆盖率：组合测试、场景测试、重复测试、边界测试、业务测试
6.模块调用，低耦合，高聚合
7.前端降序考虑是否过滤空数据
8.构造合适的数据，提高测试数据质量
9.UI测试，前端做数据处理的，多注意特殊数据，0，无穷大，单位等
10.柱状图，考虑数据量特别小何大时的易用性
11.数据的算法测试：左右连接、SQL汇总的字段顺序与实际数据库的字段顺序是否一致、分组、单位换算、时间范围
12.根据不同的配置文件，修改数据测试
13.排序，降序的时候考虑下是否过滤空数据
