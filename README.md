## simd-programming-resources
A collection of various SIMD related books, blogs, videos, code repos

I recently started learning & exploring [SIMD](https://en.wikipedia.org/wiki/Single_instruction%2C_multiple_data) programming. This repository is meant to record and organize various resources for quick reference. Hopefully, others may also find it useful.


### Books
- [SIMD for C++ Developers](http://const.me/articles/simd/simd.pdf), a small ebook by Konstantin
- [Optimizing software in C++ An optimization guide for Windows, Linux, and Mac platforms](https://agner.org/optimize/optimizing_cpp.pdf), by Prof. Agner Fog, Technical University of Denmark
- [SIMD Programming Cookbook](https://github.com/dsmatthews/Bookgen/blob/main/SIMD_Programming_Cookbook_book_1a.pdf), by [D. S. Matthews](https://x.com/DanielSMatthews)


### Reference Manuals
- [Intel® Intrinsics Guide](https://www.intel.com/content/www/us/en/docs/intrinsics-guide/index.html), Version 3.6.9
- ARM [NEON™ Programmer's Guide](https://developer.arm.com/documentation/den0018/latest/), Version: 1.0


### Blogs
- [Scan HTML faster with SIMD instructions: Chrome edition](https://lemire.me/blog/2024/06/08/scan-html-faster-with-simd-instructions-chrome-edition/)


### Code
|**Repo**|**Comments**|**Related Presentation Links**|
|:-----------------------------------------------|:-----------------------------------------------|:-----------------------------------------------|
| [Intel® Hands-on SIMD Programming with C++](https://github.com/yuninxia/hands-on-simd-programming)| An example-driven guide to SIMD programming techniques. ||
| [The Vector Class C++ Library](https://github.com/vectorclass) | by [Prof. Agner Fog](https://agner.org/optimize) | - [Agner Fog's VCL (Vector Class Library Installation and Overview)](https://www.youtube.com/watch?v=TKjYdLIMTrI), by Creel<br> - [Agner Fog's VCL 2: Performance Programming using Vector Class Library](https://www.youtube.com/watch?v=u6v_70opPsk), by Creel |
| [C++ wrappers for SIMD intrinsics](https://github.com/xtensor-stack/xsimd) | Used by Apache Arrow, Mozilla Firefox etc.| |
| [EVE - the Expressive Vector Engine](https://github.com/jfalcou/eve) | - by Joel Falcou, [Denis Yaroshevskiy](https://x.com/dyaroshev) et el.<br> - requires [C++20](https://en.wikipedia.org/wiki/C++20) | - [SIMD in C++20: EVE of a new Era - Joel Falcou & Denis Yaroshevskiy - CppCon 2021](https://www.youtube.com/watch?v=WZGNCPBMInI) |
| [simdjson : Parsing gigabytes of JSON per second](https://github.com/simdjson/simdjson) | - by [Prof. Daniel Lemire](https://github.com/lemire) and others<br> - used by ClickHouse, Meta Velox, Node.js runtime etc. | - [Parsing JSON Really Quickly: Lessons Learned - Daniel Lemire](https://www.youtube.com/watch?v=wlvKAT7SZIQ), QCon San Francisco 2019 |


### Videos
- [SIMD Libraries in C++ - Jeff Garland - CppNow 2023](https://www.youtube.com/watch?v=hlgCeWC9jxI)


### Research Papers
- [A High Throughput B+tree for SIMD Architectures](https://www.ece.lsu.edu/lpeng/papers/tpds-20-1.pdf)

