[Home](https://github.com/acg-team/ProPIP/blob/master/ProPIP.wiki/ProPIP-Progressive-Multiple-Sequence-Alignment-with-Poisson-Indel-Process.md)

---
# Dependencies, Compilation, Install
---

### Supported architectures

- i386
- x86_64


### Supported compilers

- gcc (GCC) 4.8.2 20140120 (Red Hat 4.8.2-15)
- Apple LLVM version 9.1.0 (clang-902.0.39.1)
- clang version 5.0.1 (tags/RELEASE_501/final)
- icpc (ICC) 18.0.2 20180210


[More infos here](Compilers_info.md)


### Supported linkers

- ld64-351.8 provieded with Apple LLVM version 9.1.0 (clang-902.0.39.1)


The project can also be compiled with other dynamic linkers or dynamic linker versions but unfortunately at the moment we cannot guarantee that problems will not be encountered.


### Libraries (dependencies)

miniJATI depends on the following libraries

- Bio++/bpp-core 2.4.0
- Bio++/bpp-seq	2.4.0
- Bio++/bpp-phyl 2.4.0
- glog - Google Logging Library
- boost - C++ Libraries
- TSHLib - Tree Search Heuristics Library 2.0.0
- Intel TBB - 2018 10005 (open source)


### How to compile

- [1] [Preparing your system](Preparing_system.md)

- [2.0] [Compiling on your local machine](Compiling_localenv.md)
- [2.1] [Compiling on a shared machine (i.e. cluster)](Compiling_sharedenv.md)
- [2.2] [Compiling on AWS](Compiling_aws.md)


### How to update


[Update ProPIP following this how-to](Updating.md)
