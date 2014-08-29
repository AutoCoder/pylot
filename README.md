pylot
=====

This repository is from the latest release(1.26) of <http://www.pylot.org/>, the difference is this repository support python2.7. 

Usage Steps:

1.   创建testcase（参照文档配置起来很灵活）


2.   测试方案

     *  Agents: 指定并发用户数

     *  Rampup: 所有Agent启动所用时间，他会均匀的分布在所设时间段内

     *  Interval: 每个Agent发送请求的间歇时间（除非响应时间超过了间隙时间，这样会等待响应以后再发送下一次请求）

     *  Duration: testcase运行的时间

3.   启动模式:

     *  Run Modes   -l

     *  Blocking Mode  -b

     *  GUI Mode  -g

4.   查看结果

     *  Response Time (secs): 响应时间

     *  Throughput (req/sec): 吞吐量，也就是QPS

     *  stdev: 标准差

     *  99th%: 排序后，排在99/100位置的数值，其他类似
