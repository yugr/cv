My name is YURI GRIBOV (also "IURII GRIBOV", "YURY GRIBOV").
I normally go as "yugr" (or "the_real_yugr") on social networks.

# About me

I’m a professional programmer with extensive experience in development tools
(compilers, code generators, dynamic and static analyzers), low-level optimization and system programming.

Throughout my career I’ve developed several commercial toolchains for both traditional and
novel computer architectures and brought up numerous successful teams.

I’m passionate about my work and have over 30 open-source projects on [GitHub](https://github.com/yugr).
The most popular ones are
  - [Implib.so](https://github.com/yugr/Implib.so) - delay-loading of shared libraries on POSIX systems
  - [Sortchecker](https://github.com/yugr/sortcheck), [Sortchecker++](https://github.com/yugr/sortcheckxx) - detect misuses of sorting APIs in C/C++ programs
  - [ShlibVisibilityChecker](https://github.com/yugr/ShlibVisibilityChecker) - find redundant exports in shared libraries on Linux

I'm interested in jobs that include design and implementation of complex, math-intensive systems and algorithms (usually such positions have a "Strong mathematical background" requirement). I am particularly interested in system programming (compilers, etc.), SW verification (static and dynamic analysis, model checking, etc.), computer architecture, HPC.

# Professional skills

I am experienced in
  - Software development on Linux/Windows platforms
    * C/C++, shell, Python, Perl, assembler
    * (to a lesser degree) Rust, Haskell, Fortran, Java
  - Design and implementation of optimizing compilers  (handmade, Open64, GCC and LLVM, MLIR) and runtimes
  - Software/hardware verification (dynamic and static analyzers, model checking via TLA+/SPIN)
  - Parallel programming (Pthreads, MPI, Intel TBB, Shmem, GASNet, UPC)
  - Computer architecture
  - Mathematical software development with MATLAB/Simulink and Maple (signal processing, mechanics, optimization, etc.)

# Education

2001 – 2006, Moscow Institute of Electronics and Mathematics (MIEM, later High School of Economics)
  - MSc in Applied Mathematics
  - Thesis: "Knowledge-based systems for mosaic synthesis"
    * Rule-based expert system in CLIPS/JESS
    * Image and signal processing in MATLAB and C++

# Publications and conferences

- [Dynamic libraries and how to optimize them](https://github.com/yugr/CppRussia/blob/master/2024/EN.pdf) (C++Russia 2024, [video in Russian](https://www.youtube.com/watch?v=blQavgcwrpA))
- [Painless C++ comparators](https://github.com/yugr/CppRussia/blob/master/2023/EN.pdf) (C++Russia 2023, [video in Russian](https://github.com/yugr/CppRussia/blob/master/2023/EN.pdf))
- Hanwoong Jung et al., [Accelerating Deep Neural Networks on Mobile Multicore NPUs](https://www.youtube.com/watch?v=NKn1pAoB2MM&t=1171s) (CGO 2023)
- Y. Gribov et al., Fast memory debugger for large software projects (International Journal of Open Information Technologies, vol. 3, no. 9, 2015)
- Y. Gribov, Development of mosaic synthesis system in knowledge-based systems class (international conference “New information technologies”, Crimea, 2005, first place and grant nomination)
- Y. Gribov, Development of mosaic synthesis system in knowledge-based systems class (scientific and technical conference of MIEM, Moscow, 2005, first place)
- Y. Gribov, Numeric analysis of stressedly-deformed corner stress concentrators (4-th international scientific conference "Aerospace technologies", 2004)

# Professional experience

## Dec 2022 - present, Huawei (electronic industry), Moscow

Principal Developer:
  - LLVM and AI compiler research and performance analysis

## March 2020 - Dec 2022, Samsung Electronics (electronic industry), Moscow

HPC Lab lead:
  - Leading various projects in Accelerated Computing Team:
    * bringing up teams and leading development of new features and optimizations for NPU and PIM compilers and runtime systems
    * Monitoring and controlling team activities (code reviews, design and daily meetings, planning sessions, reporting to upper management and customers, hiring and mentoring, etc.)

AI compiler optimizations teamlead, AI compiler project lead:
  - Monitoring and controlling team activities (code reviews, design and daily meetings, planning sessions, reporting to upper management, etc.)
  - Developing various components of AI compiler (scheduler, tiler, etc.)
  - Mentoring new employees
  - Interviewing new hires

## January 2009 – present, freelance

- Commercial GNU/LLVM toolchain maintenance (fixing bugs and developing new features in Binutils, GCC, QEMU, GDB, supporting and supervising external contractors and other teams)
- Porting parallel languages and libraries (GASNet, UPC, ARMCI, CAF) to new platforms
- Various data mining and image processing tasks (mostly MATLAB but also C and Haskell)
- Financial modeling (Maple)
- Parallelization of [Molconn library](http://www.molconn.com) (molecular structure descriptors)
  * Mostly C++, some Fortran, calibration done in Haskell

## May 2016 - March 2020, CEVA Limited (electronic industry), UK/Russia

Principal Developer in SW Development Tools R&D group:
  - Tools and architecture R&D:
    * Initial support for new architectural and/or toolchain features in compiler
    * Benchmarking and data analysis for Arch team
    * Low-level performance analysis
    * Development processes optimisations

Senior engineer in SW Development Tools group:
  - Typical LLVM/Open64 toolchain work:
    * Triaging/fixing bugs
    * Implementing new features (incl. bringup of new cores)
    * Optimizing customer codes
    * Automation of QA and other infrastructure tasks
  - Various exploration activities for new compiler features:
    * Symbolic evaluation of ISA specs
    * Backend unification
  - Minor tasks for VLSI team:
    * Various static analyzers of Verilog codes
    * Code generation from specs
    * SW models for performance studies
  - Team activities:
    * Technical leadership of new compiler features (preparing requirement and design specs in collaboration with other teams, planning and monitoring progress)
    * Documentation and improvement of team development processes
    * Mentoring new employees
    * Collaboration with other teams (Binutils, Architecture, QA, Performance Analysis) and external contractors

## July 2013 - May 2016, Samsung Electronics (electronic industry), Moscow

Expert engineer in Compiler Group, Team leader since Feb 2015:
  - Various SmartTV toolchain activities:
    - Leading static analysis and toolchain teams (3-4 people each): collecting requirements, planning, tracking, reporting, setting up development processes
    - Supporting SmartTV product team
    - Developing, investigating and integrating various QA and analysis tools (static and dynamic analyzers, fuzzers, etc.)
    - Fixing bugs and adding new features to GCC and LLVM toolchains (compilers, binutils, runtime library, sanitizers, etc.)
    - Contributing to open-source projects (GCC, LLVM, Glibc, Binutils, etc.)
    - Benchmarking
    - Documentation and improvement of team development processes

## March 2010 – July 2013, NVIDIA Ltd. (GPU hardware and software engineering), Moscow

Senior developer in Tegra team (September 2011 - July 2013):
  - Various system programming tasks:
    * LLVM toolchain for custom virtual machine (I did assembler-linker and parts of compiler, all in C++; system libraries were written in assembler and C)
    * Extensive functional and random testing and debugging of VM core (tests were in assembler, the testing scripts were mostly Python and Perl)
    * Toolchain tests (we used GNU and LLVM testsuites and parts of Shootout) 
    * Various secure system codes and JIT compiler for internal microcontrollers
    * Quality assurance of critical firmware code
    * Documentation and improvement of team development processes

Senior developer in APEX team (March 2010 - September 2011):
  - Working on various parts on APEX physics engine:
    * prototype physics shader language with CPU and GPU backends (parser/code generator based on Clang, runtime system: C++, CUDA, test harness in Perl)
    * metadata object system with reflection and inplace serialization for various platforms (C++, Perl);
    * particle systems (C++, CUDA)

## January 2008 – March 2010, JSC NICEVT (hardware and system software engineering), Moscow

Senior programmer:
  - Stress testing of parallel computations libraries on clusters
  - Design, development, testing and performance analysis of system software for Cray MTA-like projected supercomputers:
    * Optimizing compilers for C and Fortran (C++)
    * Macrolibraries for easier assembler programming (m4 macroprocessor)
    * Experimental dataflow computations library (programming in C and assembler, analysis with Perl, gnuplot and Octave)
    * Visualization of simulation results (Java)
    * Fixing bugs in other toolchain components (assembler, linker, object file analyzer, simulator of designed supercomputer)

## March 2006 – January 2008, Siemens VDO Engineering (electronic automotive control systems), Moscow

Senior engineer:
  - Software for design of automotive engine control systems (MATLAB/Simulink, C, Perl)
  - Software for analysis of experimental data (MATLAB/Simulink, C++)
  - Automation of common specification checks in legacy MATLAB codes (Perl)
  - Static analysis and automatic adaptation of legacy MATLAB codes (Perl, C/yacc/flex)
  - Automated tests for verification of engine control systems (for automotive HIL-simulators dSpace and Labcar)
  - Continuous contact with foreign customers (telephone conferences, e-mail)
  - Training new employees

## July 2002 - November 2002, MIEM, Moscow

Technician:
  - Design and implementation of mathematical algorithms for continuum mechanics modeling (C, MATLAB/FEMLAB, Delphi).

