# Course Description
* Teach common network programming techniques by examples
* Focus on server-side TCP network programming on Linux
* Walk-through code in C++, Python and Go

# Prerequisites
* Have read _Unix Network Programming_ volume 1 (either 2nd ed. or 3rd ed.) by late W.&nbsp;Richard Stevens
* Know basics of TCP/IP, eg. IP addresses, ports,
* Know how to write an echo server with basic sockets APIs in any language

# Code
* http://github.com/chenshuo/muduo
* http://github.com/chenshuo/recipes
* http://github.com/chenshuo/muduo-protorpc
* http://github.com/chenshuo/muduo-examples-in-go

# Schedule

### 0. Overview
* Measure throughput of TCP over Gigabit Ethernet with netcat
* <a href="http://boolan.com/course/section/1000001028">Lecture section 1</a> |
<a href="http://boolan.com/course/section/1000001029">Lecture section 2</a> |
<a href="http://boolan.com/course/section/1000001030">Lecture section 3</a>


## Part I: Basic non-concurrent programs with blocking IO

### 1. TTCP
* Review basic Sockets API
* Measure throughput of TCP over Gigabit Ethernet with TTCP
* TCP self connection
* <a href="http://boolan.com/course/section/1000001031">Lecture section 4</a> |
<a href="http://boolan.com/course/section/1000001053">section 5</a> |
<a href="http://boolan.com/course/section/1000001054">section 6</a> |
<a href="http://boolan.com/course/section/1000001062">section 7</a> |
<a href="http://boolan.com/course/section/1000001063">section 8</a> |
<a href="http://boolan.com/course/section/1000001066">section 9</a>

### 2. Round-trip
* How NTP works
* Measure clock error between two hosts
* The only UDP example
* <a href="http://boolan.com/course/section/1000001071">Lecture section 10</a> |
<a href="http://boolan.com/course/section/1000001102">section 11</a> |
<a href="http://boolan.com/course/section/1000001103">section 12</a> |
<a href="http://boolan.com/course/section/1000001104">section 13</a> |
<a href="http://boolan.com/course/section/1000001105">section 14</a> |
<a href="http://boolan.com/course/section/1000001106">section 15</a> |
<a href="http://boolan.com/course/section/1000001107">section 16</a>

### 3. Netcat
* The Swiss army knife of networking
* Deal with two file descriptors simultaneously (stdin/out and TCP socket)
* Why IO-multiplexing must be used with non-blocking IO
* <a href="http://boolan.com/course/section/1000001118">Lecture section 17</a> |
<a href="http://boolan.com/course/section/1000001119">section 18</a> |
<a href="http://boolan.com/course/section/1000001120">section 19</a> |
<a href="http://boolan.com/course/section/1000001121">section 20</a> |
<a href="http://boolan.com/course/section/1000001122">section 21</a> |
<a href="http://boolan.com/course/section/1000001123">section 22</a> |
<a href="http://boolan.com/course/section/1000001124">section 23</a>

## Part II: Concurrent programs with non-blocking IO

### 4. procmon
* cpu / memory usage charts of one process
* dummyload
* <a href="http://boolan.com/course/section/1000001146">Lecture section 25</a> |
<a href="http://boolan.com/course/section/1000001147">section 25</a> |
<a href="http://boolan.com/course/section/1000001148">section 26</a> |
<a href="http://boolan.com/course/section/1000001149">section 27</a> |
<a href="http://boolan.com/course/section/1000001150">section 28</a> |
<a href="http://boolan.com/course/section/1000001151">section 29</a>

### 5. Simple memcached
* Customize the data structure
* Efficient locking by sharding
* Performance testing
* [Lecture section 30](http://boolan.com/course/section/1000000198) |
  [section 31](http://boolan.com/course/section/1000000199) |
  [section 32](http://boolan.com/course/section/1000000200) |
  [section 33](http://boolan.com/course/section/1000000201) |
  [section 34](http://boolan.com/course/section/1000002191) |
  [section 35](http://boolan.com/course/section/1000000203) |
  [section 36](http://boolan.com/course/section/1000000204) |
  [section 37](http://boolan.com/course/section/1000000205) |

### 6. Sudoku Solver
* Request-response model
* Client connections are independent
* Concurrency and parallel on multicore machines
* Disable Nagle's algorithm in low-latency servers
* Load balancing
* Overload protection
* [Lecture section 38](http://boolan.com/course/section/1000000313) |
  [section 39](http://boolan.com/course/section/1000000317) |
  [section 40](http://boolan.com/course/section/1000000315) |
  [section 41](http://boolan.com/course/section/1000000316) |
  [section 42](http://boolan.com/course/section/1000000318) |
  [section 43](http://boolan.com/course/section/1000000319) |
  [section 44](http://boolan.com/course/section/1000000320) |
  [section 45](http://boolan.com/course/section/1000000321) |
  [section 46](http://boolan.com/course/section/1000000348) |
  [section 47](http://boolan.com/course/section/1000000349) |
  [section 48](http://boolan.com/course/section/1000000350) |
  [section 49](http://boolan.com/course/section/1000000360) |
  [section 50](http://boolan.com/course/section/1000000361) |

### 7. Broadcasting to TCP peers
* Connections exchange data with each other
* How to deal with slow clients?
* [Lecture section 51](http://boolan.com/course/section/1000000435) |
  [section 52](http://boolan.com/course/section/1000000434) |
  [section 53](http://boolan.com/course/section/1000000436) |
  [section 54](http://boolan.com/course/section/1000000437) |
  [section 55](http://boolan.com/course/section/1000000438) |
  [section 56](http://boolan.com/course/section/1000000439) |

### 8. SOCKS proxy server
* Relay two TCP connections
* Mismatching bandwidth?
* Difference between level 4 and level 7?
* [Lecture section 57](http://boolan.com/course/section/1000002156) |
  [section 58](http://boolan.com/course/section/1000002157) |
  [section 59](http://boolan.com/course/section/1000002158) |
  [section 60](http://boolan.com/course/section/1000002159) |
  [section 61](http://boolan.com/course/section/1000002160) |
  [section 62](http://boolan.com/course/section/1000002161) |
  [section 63](http://boolan.com/course/section/1000002162) |
  [section 64](http://boolan.com/course/section/1000002163) |
  [section 65](http://boolan.com/course/section/1000002164) |
  [section 66](http://boolan.com/course/section/1000002165) |
  [section 67](http://boolan.com/course/section/1000002166) |
  [section 68](http://boolan.com/course/section/1000002167) |


## Part III: Data processing with multiple machines
### 9. Parallel N-queen puzzle
* Multithreaded N-queen puzzle
* Multi-machine N-queen puzzle using MapReduce
* [Lecture section 69](http://boolan.com/course/section/1000002168) |
  [section 70](http://boolan.com/course/section/1000002169) |
  [section 71](http://boolan.com/course/section/1000002170) |
  [section 72](http://boolan.com/course/section/1000002171) |
  [section 73](http://boolan.com/course/section/1000002172) |
  [section 74](http://boolan.com/course/section/1000002173) |

### 10. Median across machines
* [Lecture section 75](http://boolan.com/course/section/1000002174) |
  [section 76](http://boolan.com/course/section/1000002175) |
  [section 77](http://boolan.com/course/section/1000002176) |
  [section 78](http://boolan.com/course/section/1000002178) |

### 11. Most frequent queries
* [Lecture section 79](http://boolan.com/course/section/1000002183) |
  [section 80](http://boolan.com/course/section/1000002184) |
  [section 81](http://boolan.com/course/section/1000002185) |
  [section 82](http://boolan.com/course/section/1000002186) |
  [section 83](http://boolan.com/course/section/1000002187) |
  [section 84](http://boolan.com/course/section/1000002188) |
