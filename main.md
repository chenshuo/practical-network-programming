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
* <a href="http://boolan.com/course/section/1000001031">Lecture section 1</a> |
<a href="http://boolan.com/course/section/1000001053">section 2</a> |
<a href="http://boolan.com/course/section/1000001054">section 3</a> |
<a href="http://boolan.com/course/section/1000001062">section 4</a> |
<a href="http://boolan.com/course/section/1000001063">section 5</a> |
<a href="http://boolan.com/course/section/1000001066">section 6</a>

### 2. Round-trip
* How NTP works
* Measure clock error between two hosts
* The only UDP example
* <a href="http://boolan.com/course/section/1000001071">Lecture section 1</a> |
<a href="http://boolan.com/course/section/1000001102">section 2</a> |
<a href="http://boolan.com/course/section/1000001103">section 3</a> |
<a href="http://boolan.com/course/section/1000001104">section 4</a> |
<a href="http://boolan.com/course/section/1000001105">section 5</a> |
<a href="http://boolan.com/course/section/1000001106">section 6</a> |
<a href="http://boolan.com/course/section/1000001107">section 7</a> |

### 3. Netcat
* The Swiss army knife of networking
* Deal with two file descriptors simultaneously (stdin/out and TCP socket)
* Why IO-multiplexing must be used with non-blocking IO
* <a href="http://boolan.com/course/section/1000001118">Lecture section 1</a> |
<a href="http://boolan.com/course/section/1000001119">section 2</a> |
<a href="http://boolan.com/course/section/1000001120">section 3</a> |
<a href="http://boolan.com/course/section/1000001121">section 4</a> |
<a href="http://boolan.com/course/section/1000001122">section 5</a> |
<a href="http://boolan.com/course/section/1000001123">section 6</a> |
<a href="http://boolan.com/course/section/1000001124">section 7</a> |

## Part II: Concurrent programs with non-blocking IO

### 4. procmon
* cpu / memory usage charts of one process
* <a href="http://boolan.com/course/section/1000001146">Lecture section 1</a> |
<a href="http://boolan.com/course/section/1000001147">section 2</a> |
<a href="http://boolan.com/course/section/1000001148">section 3</a> |
<a href="http://boolan.com/course/section/1000001149">section 4</a> |
<a href="http://boolan.com/course/section/1000001150">section 5</a> |
<a href="http://boolan.com/course/section/1000001151">section 6</a>

### 5. Simple memcached
* Clients share the same state of the server
* Efficient locking by sharding

### 6. Sudoku Solver
* Request-response model
* Client connections are independent
* Concurrency and parallel on multicore machines


### 11. SOCKS proxy server
* Relay two TCP connections
* Mismatching bandwidth?
* Difference between level 4 and level 7?

### 13. Broadcasting to TCP peers
* Connections exchange data with each other
* How to deal with slow clients?

### 14. RPC load balancer
* Better than round-robin

## Part III: Data processing with multiple machines
### 20. Parallel N-queen
### 21. Median across machines
### 22. Most frequent queries
### 23. Distributed sorting

## Part IV: Capacity provisioning, latency managing, etc.

