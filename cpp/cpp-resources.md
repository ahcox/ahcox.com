
### Using C++ Features Conservatively

* [Orthodox C++](https://gist.github.com/bkaradzic/2e39896bc7d8c34e042b)
  _"Orthodox C++ (sometimes referred as C+) is minimal subset of C++ that improves C, but avoids all unnecessary things from so called Modern C++. It's exactly opposite of what Modern C++ suppose to be."_
* [Why Your C++ Should Be Simple](https://hacksoflife.blogspot.co.uk/2017/03/why-your-c-should-be-simple.html)

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
- [**libFuzzer:**](http://llvm.org/docs/LibFuzzer.html)
  A Clang Tools project to do fuzz-testing for C++ based on coverage analysis.
  I.e., throws broken inputs at your program to see if it falls over while tracking
  which code paths are being reached.
* [**Brigand Metaprogramming:**](https://github.com/edouarda/brigand/blob/master/README.md)
  A macro-free template metaprogramming library which relies on C++ 11 and so compiles faster than Boost::MPL
  while leading to less verbose client code.
  [Eleven minute talk](https://www.youtube.com/watch?v=B8XSDhWx7hY).

### C++ Tools
* [**Cling:**](https://root.cern.ch/cling)
  An LVM-jitted REPL for C++
  ([video](http://www.youtube.com/watch?v=f9Xfh8pv3Fs),
  [video](http://llvm.org/devmtg/2010-11/videos/Naumann_Cling-desktop.mp4), [article](https://www.infoq.com/news/2015/05/cling-cpp-interpreter)).

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

### C++ in the Weeds
* `std::move`
  - [std::move Is Not Destructive Move](https://github.com/mcalabrese/cpp-stuff/wiki/std::move-Is-Not-Destructive-Move),
    Matt Calabrese, May 30 2014.
    Matt points out that `std::move` is not destructive and that the object on the rhs of a move should still be
    in a reasonable state after the move.
    Destructive moves would actually be desireable from an efficiency point of view: after all moved from objects
    are typically thrown away immediately post-move.
  - [About Move](http://sean-parent.stlab.cc/2014/05/30/about-move.html),
    Sean Parent, 2014.

*[Edit](https://github.com/ahcox/ahcox.com/edit/master/cpp/cpp-resources.md) [this page](http://ahcox.com/cpp/cpp-resources/)*.
