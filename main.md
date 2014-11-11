# Course Description
* Teach common network programming techniques by examples
* Focus on server-side TCP network programming on Linux
* Walk-through code in C++, Python and Go

# Prerequisites 
* Have read _Unix Network Programming_ volume 1 (either 2nd ed. or 3rd ed.) by late W. Richard Stevens
* Know basics of TCP/IP, eg. IP addresses, ports,
* Know how to write an echo server with basic sockets APIs in any language

# Schedule

### 0. Overview

<a href="http://boolan.com/lecture/1000001028">Lecture section 1</a> |
<a href="http://boolan.com/lecture/1000001029">Lecture section 2</a> |
<a href="http://boolan.com/lecture/1000001030">Lecture section 3</a>

## Part I: Basic non-concurrent programs with blocking IO

### 1. TTCP
* Review basic Sockets API
* Measure throughput of TCP over Gigabit Ethernet

### 2. Round-trip
* The only UDP example
* Measure clock error between two hosts

### 3. Netcat
* The Swiss army knife of networking
* Deal with two file descriptors simultaneously (stdin/out and TCP socket)

### 4. Slow sink/source
* Simulate low-bandwidth or slow peer
* Generate traffic generator at given speed

## Part II: Concurrent programs with non-blocking IO

### 5. SOCKS proxy server
* Relay two TCP connections
* Mismatching bandwidth?
* Difference between level 4 and level 7?

### 6. Sudoku Solver
* Request-response model
* Client connections are independent
* Concurrency and parallel on multicore machines

### 7. Simple memcached
* Clients share the same state of the server
* Efficient locking by sharding

### 8. Broadcasting to TCP peers
* Connections exchange data with each other
* How to deal with slow clients?

### 9. RPC load balancer
* Better than round-robin

## Part III: Data processing with multiple machines
### 10. Parallel N-queue
### 11. Median across machines
### 12. Most frequent queries
### 13. Distributed sorting

## Part IV: Capacity provisioning, latency managing, etc.

