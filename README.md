# Distributed system & Database & Cloud Native 

* Paper文件中包含了分布式领域下的经典论文，包含了经典问题，比如：FLP不可能性，重要机制replication，leases等，一致性问题算法比如2PC，3PC，Paxos的相关论文，Google下的Mapreduce、GFS、Spanner、F1等，以及一些分布式算法等，也是学习分布式理论以及现代存储系统的第一关;
* [常用分布式算法总结](https://mp.weixin.qq.com/s/uFIn90szggYU49MVQvWPiA) 。
* Golang
  * [Go语言设计与实现](https://draveness.me/golang/) 这本书给出了非常系统和全面的Go语言设计的来龙去脉，适合有一定golang开发经验的小伙伴进行补充阅读，对于基础数据结构和运行时的解释是本书的一个亮点；
  * [Golang Design History](https://github.com/golang-design/history#runtime-core) 这里做出了更为详细的从Go设计之初到较新的版本设计演变的痛点，给出不同版本在设计上存在的问题，以及如何每一步是如何解决问题的做法。但是这个github的作者给出的都是issue较为生硬的讨论内容，还有一部分是作者本人的技术总结和感受，所以推荐作为更进一步的了解和上一本书的继续补充。
* Rust
  * [Rust learn by example](http://rustcc.github.io/rust-by-example/) 没有什么比跟着敲一遍入门更快了，Just Do it；
  * [Rust 高级教程](https://learnku.com/docs/nomicon/2018/brief-introduction/4702) Rust死灵书的中文翻译，高级的特性你值得拥有；
  * [Rust 异步编程](https://rust-lang.github.io/async-book/01_getting_started/01_chapter.html) ；
  * [Rust 宏](https://danielkeep.github.io/tlborm/book/index.html) ；
  * [Rust编程范式](https://coolshell.cn/articles/20845.html) 这里给出了常用的Rust编程的方法论，建议在了解上面的文档后，反复阅读本文；
  * [Rust 练习](https://university.pingcap.com/talent-plan/rust-programming/) 建议完成这里给出的练习。
* ModernC++
  * [C++ Concurrency in Action](https://github.com/huyubing/books-pdf/blob/master/C%2B%2B%20Concurrency%20in%20Action.pdf) 这里给出了现代c++中，给出的常用新特性用法，以及如何设计并发数据结构，建议和上面的Rust相互对应进行学习，有很多异曲同工甚至一摸一样的设计思路。这里是[中文版](https://github.com/xiaoweiChen/CPP-Concurrency-In-Action-2ed-2019)。

* Others
  * [NUMA](http://cenalulu.github.io/linux/numa/) 架构在多核时代已经俨然成为主流，但是目前的数据结构设计，算法设计，软件设计都没有较好利用；
  * [SIMD](https://zhuanlan.zhihu.com/p/55327037) 单指令多数据流，可以实现空间上并行性的技术，提高并行度；
  * [SkipList](https://nan01ab.github.io/2019/08/FAST-and-S3.html) 是比较优秀的数据结构设计，但是读写并没有很好利用多核带来的优势，所以业界有一些很好的尝试；
  * [Prefech 预读取](http://home.eng.iastate.edu/~zzhang/cpre581/lectures/Lecture17-1p.pdf) 这实际上是利用数据的局部性来用空间换时间的一种办法，在很多软件上都是成熟的案例