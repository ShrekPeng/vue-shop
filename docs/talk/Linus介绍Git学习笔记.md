Linus介绍Git学习笔记

1.	CVS（分支是全局性的）,SVN🙅‍♂‍
2.	BitKeeper（商业产品/分布式）👍 
3.	SCM（源代码管理）,要支持分布式
4.	分布式设计模式，分布式代码控制系统，离线工作模式
5.	分支：在分支模式下，每个人都有自己的分支，对于分布式系统，分支是更内在的东西，解决了代码提交权限的问题。
6.	代码树能在不影响别人的情况下工作，小组成员之间是平等的，可以互相pull和merge。
7.	信任：长期合作者形成信任网络，是对应该pull谁的标准。
8.	分布的含义是：没有人是特殊的。
9.	从技术上让创建分支的成本很低，分支随意命名。
10.	 Git追踪的是你的内容，而不能追踪单独某些文件，Git会把所有文件看成一个完整的部分，追踪的是是文件的历史。
11.	 Git内部用的是内容可寻址的文件系统。
12.	merge要做的很快，希望人们尽快尽早merge。
13.	Git使用SHA-1检查一致性


