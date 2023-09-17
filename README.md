# Cache Simulator

The simulator supports different configurations of associativity, cache size, and block size. These 3 are the major tuning parameters in cache design. Each policy is simulated for a full range of these 3 parameters to see how the tuning affects the cache performance. The simulator is implemented in Python, and the results are shown below.

![EE275 MP3 Progress drawio](https://github.com/bhavinpt/cache-simulator/assets/117598876/a6a4ff37-9a17-4521-b4da-48a3f1e63a47 "Python Code Architecture")


## Cache Performance

The results are shown in the below diagrams.

![image](https://github.com/bhavinpt/cache-simulator/assets/117598876/36b295a2-8045-48e8-b938-97f1916edb4a "Cache Performance Comparison")

- Increasing associative increases misses for LRU.
- Increasing cache size reduces misses as the cache can now have more lines available.
- Increasing block size also reduces misses as larger blocks can hold more addresses.

Please check out the Python notebook output and the project report in this repo.
