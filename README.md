# JMH Fibonacci Algorithm Benchmark
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](/LICENSE)

A Java Microbenchmark Harness (JMH) demo within several algorithm/ solution of Fibonacci N position calculation benchmark.

The benchmarking algorithms are consist of:

- Naive Recursive
- Tail Recursive
- Bottom-up (Iteration)
- Memoization
- Stream API





## How to Run

```console
mvn clean install
java -jar target/jmh-fibonacci.jar
```





## Setup & Result

### Setup

- CPU: Intel Core i5-7200U 2.50GHz
- RAM: DDR4 8GB
- OS: Windows 10 64-bit
- Java: Oracle JDK 8 build 1.8.0_171-b11
- Fibonacci N: 45

### Result

| Benchmark             |                  Score |
| --------------------- | ---------------------: |
| Bottom-up (Iteration) |         38.112 ns / op |
| Tail Recursive        |         54.201 ns / op |
| Memoization           |        180.374 ns / op |
| Stream API            |        600.472 ns / op |
| Naive Recursive       | 3758207400.000 ns / op |

### Screenshot

![Imgur](https://i.imgur.com/Lsm9W5h.png)



## Reference

- [OpenJDK - JMH](http://openjdk.java.net/projects/code-tools/jmh/)
- [Intro to JMH](http://java-performance.info/jmh/)
- [Microbenchmarking with Java](http://www.baeldung.com/java-microbenchmark-harness)
- [JMH - Java Microbenchmark Harness](http://tutorials.jenkov.com/java-performance/jmh.html)
- [Java Iterative Benchmark](https://github.com/smartinrub/java-iterative-benchmark)
- [Fibonacci Number](https://en.wikipedia.org/wiki/Fibonacci_number)



## License
Licensed under the MIT License. See [LICENSE](/LICENSE) file.