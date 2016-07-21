
### C++ Debugging Resources
* [**rr:** A deterministic **r**ecord and **r**eplay tool for C++](http://rr-project.org/).
  Allows a run of an application to be fully captured.
  This trace can then be replayed under gbd to allow debugging,
  both forwards and efficiently backwards. 

### C++ Libraries
* [**musl:**](https://www.musl-libc.org) A Linux libc implementation which is designed to be
  statically linkable as well as small, efficient, and readable.
* [**HPX:**](https://github.com/STEllAR-GROUP/hpx)
  A parallel runtime based on advanced futures and lightweight tasks which scales from embedded devices
  to distributed clusters.

### C++ Standards Documents
* [**Parallelism TS:**](https://github.com/cplusplus/parallelism-ts) Improvements to C++ concurrency support aimed
  at exploiting multiple cores and heterogenous compute capabilities.

### C++ Techniques
* Transducers
  * [**CppCon 15.**](https://www.youtube.com/watch?v=vohGJjGxtJQ)
  * [**C++ 14 Transducers:**](http://vitiy.info/cpp14-how-to-implement-transducers/)
    How to implement Transducers in C++ 14.
  * [**Atria.**](http://ableton.github.io/atria/)

### Large Scale C++
* [Hourglass Interfaces for C++ APIs](https://www.youtube.com/watch?v=PVYdHDm0q6Y)
  - **TLDW:** Export only a minimal C89 interface from your C++ shared libraries but provide a
  full-fat C++ wrapper to be compiled into library clients.
  - [Slides](http://www.slideshare.net/StefanusDuToit/cpp-con-2014-hourglass-interfaces-for-c-apis) ([PDF](https://github.com/CppCon/CppCon2014/raw/master/Presentations/Hourglass%20Interfaces%20for%20C%2B%2B%20APIs/Hourglass%20Interfaces%20for%20C%2B%2B%20APIs%20-%20Stefanus%20Du%20Toit%20-%20CppCon%202014.pdf))
  - [Code](https://github.com/CppCon/CppCon2014/tree/master/Presentations/Hourglass%20Interfaces%20for%20C%2B%2B%20APIs/code)
  

*[Edit](https://github.com/ahcox/ahcox.com/edit/master/cpp/cpp-resources.md) [this page](http://ahcox.com/cpp/cpp-resources/)*.
