# Recent Papers/Blogs/Tools Related To Fuzzing

The blog post contains classic fuzzing books, papers about fuzzing at information security top conferences over the years, commonly used fuzzing tools, and blogs that can quickly learn fuzzing tools.

## 1 Books

- [The Fuzzing Book](https://www.fuzzingbook.org/) (2019)：This book is based on principles + code exercises, combined with practical exercises, to complete a fuzzing test framework from 0 to 1. If you want to write your own fuzzing framework, you can refer to this book.
- [Fuzzing for Software Security Testing and Quality Assurance](https://www.amazon.com/Fuzzing-Software-Security-Testing-Assurance/dp/1608078507/) (2018)：This book introduces the idea of fuzzing into the software development life cycle. In fact, many efficient fuzzing tests are often considered in the development stage. The book discusses the development of fuzz tools, including not only some emerging open source tools, but also many commercial ones. How to choose the right fuzzer for software development projects is also one of the themes of this book.

## 2 Articles&Papers

This chapter contains top-level information security and classic papers in some journals. We just want to select some of them with relatively high technical value or relatively novel articles to facilitate subsequent learning.

### Others

- [The Art, Science, and Engineering of Fuzzing: A Survey](https://ieeexplore.ieee.org/document/8863940) (2019)
- [Fuzzing: a survey](https://cybersecurity.springeropen.com/articles/10.1186/s42400-018-0002-y) (2018)
- [Evaluating Fuzz Testing, 2018](http://www.cs.umd.edu/~mwh/papers/fuzzeval.pdf)
- [Fuzzing: Art, Science, and Engineering, 2018](https://arxiv.org/pdf/1812.00140.pdf)
- [Fuzzing: State of the art, 2018](https://ieeexplore.ieee.org/document/8371326)
- [Source-and-Fuzzing](https://github.com/lcatro/Source-and-Fuzzing) (2019)
- [CoLaFUZE: Coverage-Guided and Layout-Aware Fuzzing for Android Drivers](https://www.jstage.jst.go.jp/article/transinf/E104.D/11/E104.D_2021NGP0005/_pdf) (2021)
- [Better Pay Attention Whilst Fuzzing](https://arxiv.org/pdf/2112.07143) (2022)
- [Effective File Format Fuzzing – Thoughts, Techniques and Results](https://www.youtube.com/watch?v=qTTwqFRD1H8)

### NDSS

- [EMS: History-Driven Mutation for Coverage-based Fuzzing](https://nesa.zju.edu.cn/download/lcy_pdf_ems_ndss22.pdf) (2022)
- [Favocado: Fuzzing the Binding Code of JavaScript Engines Using Semantically Correct Test Cases](https://www.ndss-symposium.org/ndss-paper/favocado-fuzzing-the-binding-code-of-javascript-engines-using-semantically-correct-test-cases/) (2021)
- [WINNIE : Fuzzing Windows Applications with Harness Synthesis and Fast Cloning, 2021](https://www.ndss-symposium.org/ndss-paper/winnie-fuzzing-windows-applications-with-harness-synthesis-and-fast-cloning/)
- [PGFUZZ: Policy-Guided Fuzzing for Robotic Vehicles](https://www.ndss-symposium.org/ndss-paper/pgfuzz-policy-guided-fuzzing-for-robotic-vehicles/) (2021)
- [Reinforcement Learning-based Hierarchical Seed Scheduling for Greybox Fuzzing](https://www.ndss-symposium.org/ndss-paper/reinforcement-learning-based-hierarchical-seed-scheduling-for-greybox-fuzzing/) (2021)
- [HFL: Hybrid Fuzzing on the Linux Kernel](https://www.unexploitable.systems/publication/kimhfl/) (2020)
- [HotFuzz: Discovering Algorithmic Denial-of-Service Vulnerabilities Through Guided Micro-Fuzzing](https://www.researchgate.net/publication/339164746_HotFuzz_Discovering_Algorithmic_Denial-of-Service_Vulnerabilities_Through_Guided_Micro-Fuzzing) (2020)
- [Not All Coverage Measurements Are Equal: Fuzzing by Coverage Accounting for Input Prioritization](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24422.pdf) (2020)
- [PeriScope: An Effective Probing and Fuzzing Framework for the Hardware-OS Boundary](https://people.cs.kuleuven.be/~stijn.volckaert/papers/2019_NDSS_PeriScope.pdf) (2019)
- [INSTRIM: Lightweight Instrumentation for Coverage-guided Fuzzing](https://www.ndss-symposium.org/wp-content/uploads/2018/07/bar2018_14_Hsu_paper.pdf) (2018)
- [What You Corrupt Is Not What You Crash: Challenges in Fuzzing Embedded Devices](http://s3.eurecom.fr/docs/ndss18_muench.pdf)
- [Enhancing Memory Error Detection for Large-Scale Applications and Fuzz Testing](https://lifeasageek.github.io/papers/han:meds.pdf) (2018)
- [DELTA: A Security Assessment Framework for Software-Defined Networks](https://www.ndss-symposium.org/wp-content/uploads/2017/09/ndss201702A-1LeePaper.pdf) (2017)

### USENIX Security

- [SyzScope: Revealing High-Risk Security Impacts of Fuzzer-Exposed Bugs inLinux kernel, 2022](https://www.usenix.org/system/files/sec22summer_zou.pdf)
- [Constraint-guided Directed Greybox Fuzzing, 2021](https://www.usenix.org/conference/usenixsecurity21/presentation/lee-gwangmu)
- [UNIFUZZ: A Holistic and Pragmatic Metrics-Driven Platform for Evaluating Fuzzers, 2021](https://www.usenix.org/biblio-6129)
- [Nyx: Greybox Hypervisor Fuzzing using Fast Snapshots and Affine Types, 2021](https://www.usenix.org/conference/usenixsecurity21/presentation/schumilo)
- [Breaking Through Binaries: Compiler-quality Instrumentation for Better Binary-only Fuzzing, 2021](https://www.usenix.org/conference/usenixsecurity21/presentation/nagy)
- [The Use of Likely Invariants as Feedback for Fuzzers, 2021](https://www.usenix.org/conference/usenixsecurity21/presentation/fioraldi)
- [Analysis of DTLS Implementations Using Protocol State Fuzzing](https://www.usenix.org/conference/usenixsecurity20/presentation/fiterau-brostean) 
- [EcoFuzz: Adaptive Energy-Saving Greybox Fuzzing as a Variant of the Adversarial Multi-Armed Bandit](https://www.usenix.org/conference/usenixsecurity20/presentation/yue) (2020)
- [FANS: Fuzzing Android Native System Services via Automated Interface Analysis](https://www.usenix.org/conference/usenixsecurity20/presentation/liu) (2020)
- [Fuzzing Error Handling Code using Context-Sensitive Software Fault Injection](https://www.usenix.org/conference/usenixsecurity20/presentation/jiang) (2020)
- [FuzzGen: Automatic Fuzzer Generation, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/ispoglou)
- [GREYONE: Data Flow Sensitive Fuzzing, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/gan)
- [Fuzzification: Anti-Fuzzing Techniques, 2019](https://www.usenix.org/conference/usenixsecurity19/presentation/jung)
- [AntiFuzz: Impeding Fuzzing Audits of Binary Executables, 2019](https://www.usenix.org/conference/usenixsecurity19/presentation/guler)
- [MoonShine: Optimizing OS Fuzzer Seed Selection with Trace Distillation, 2018](https://www.usenix.org/conference/usenixsecurity18/presentation/pailoor)
- [QSYM : A Practical Concolic Execution Engine Tailored for Hybrid Fuzzing, 2018](https://www.usenix.org/conference/usenixsecurity18/presentation/yun)
- [OSS-Fuzz - Google's continuous fuzzing service for open source software, 2017](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/serebryany)
- [kAFL: Hardware-Assisted Feedback Fuzzing for OS Kernels, 2017](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/schumilo)

### IEEE S&P

- [BEACON: Directed Grey-Box Fuzzing with Provable Path Pruning, 2022](https://qingkaishi.github.io/public_pdfs/SP22.pdf)
- [DiFuzzRTL: Differential Fuzz Testing to Find CPU Bugs, 2021](https://ieeexplore.ieee.org/document/9519470)
- [StochFuzz: Sound and Cost-effective Fuzzing of Stripped Binaries by Incremental and Stochastic Rewriting, 2021](https://ieeexplore.ieee.org/document/9519407)
- [NtFuzz: Enabling Type-Aware Kernel Fuzzing on Windows with Static Binary Analysis, 2021](https://ieeexplore.ieee.org/document/9519448)
- [Diane: Identifying Fuzzing Triggers in Apps to Generate Under-constrained Inputs for IoT Devices, 2021](https://ieeexplore.ieee.org/document/9519432)
- [One Engine to Fuzz 'em All: Generic Language Processor Testing with Semantic Validation, 2021](https://ieeexplore.ieee.org/document/9519403)
- [IJON: Exploring Deep State Spaces via Fuzzing, 2020](https://www.syssec.ruhr-uni-bochum.de/media/emma/veroeffentlichungen/2020/02/27/IJON-Oakland20.pdf)
- [Krace: Data Race Fuzzing for Kernel File Systems, 2020](https://www.cc.gatech.edu/~mxu80/pubs/xu:krace.pdf)
- [Pangolin:Incremental Hybrid Fuzzing with Polyhedral Path Abstraction, 2020](https://qingkaishi.github.io/public_pdfs/SP2020.pdf) 
- [RetroWrite: Statically Instrumenting COTS Binaries for Fuzzing and Sanitization, 2020](https://www.semanticscholar.org/paper/RetroWrite%3A-Statically-Instrumenting-COTS-Binaries-Dinesh-Burow/845cafb153b0e4b9943c6d9b6a7e42c14845a0d6)
- [Full-speed Fuzzing: Reducing Fuzzing Overhead through Coverage-guided Tracing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000b122/19skgbGVFEQ)
- [Fuzzing File Systems via Two-Dimensional Input Space Exploration, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a594/19skfLYOpaw)
- [NEUZZ: Efficient Fuzzing with Neural Program Smoothing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a900/19skg5XghG0)
- [Razzer: Finding Kernel Race Bugs through Fuzzing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a296/19skfwZLirm)
- [Angora: Efficient Fuzzing by Principled Search, 2018](http://web.cs.ucdavis.edu/~hchen/paper/chen2018angora.pdf)
- [CollAFL: Path Sensitive Fuzzing, 2018](http://chao.100871.net/papers/oakland18.pdf)
- [T-Fuzz: fuzzing by program transformation, 2018](https://nebelwelt.net/publications/files/18Oakland.pdf)
- [Skyfire: Data-Driven Seed Generation for Fuzzing, 2017](https://www.ieee-security.org/TC/SP2017/papers/42.pdf)

### ACM CCS

- [Favocado: Fuzzing the Binding Code of JavaScript Engines Using Semantically Correct Test Cases, 2021](https://www.ndss-symposium.org/ndss-paper/favocado-fuzzing-the-binding-code-of-javascript-engines-using-semantically-correct-test-cases/)
- [WINNIE : Fuzzing Windows Applications with Harness Synthesis and Fast Cloning, 2021](https://www.ndss-symposium.org/ndss-paper/winnie-fuzzing-windows-applications-with-harness-synthesis-and-fast-cloning/)
- [PGFUZZ: Policy-Guided Fuzzing for Robotic Vehicles, 2021](https://www.ndss-symposium.org/ndss-paper/pgfuzz-policy-guided-fuzzing-for-robotic-vehicles/)
- [Reinforcement Learning-based Hierarchical Seed Scheduling for Greybox Fuzzing, 2021](https://www.ndss-symposium.org/ndss-paper/reinforcement-learning-based-hierarchical-seed-scheduling-for-greybox-fuzzing/)
- [DIFUZE: Interface Aware Fuzzing for Kernel Drivers, 2017](https://acmccs.github.io/papers/p2123-corinaA.pdf) 
- [Learning to Fuzz from Symbolic Execution with Application to Smart Contracts, 2019](https://files.sri.inf.ethz.ch/website/papers/ccs19-ilf.pdf)
- [Matryoshka: fuzzing deeply nested branches, 2019](https://web.cs.ucdavis.edu/~hchen/paper/chen2019matryoshka.pdf)
- [Hawkeye: Towards a Desired Directed Grey-box Fuzzer, 2018](https://chenbihuan.github.io/paper/ccs18-chen-hawkeye.pdf)
- [IMF: Inferred Model-based Fuzzer, 2017](http://daramg.gift/paper/han-ccs2017.pdf)
- [SemFuzz: Semantics-based Automatic Generation of Proof-of-Concept Exploits, 2017](https://www.informatics.indiana.edu/xw7/papers/p2139-you.pdf)
- [Directed Greybox Fuzzing, 2017](https://dl.acm.org/citation.cfm?id=3134020)
- [SlowFuzz: Automated Domain-Independent Detection of Algorithmic Complexity Vulnerabilities, 2017](https://arxiv.org/pdf/1708.08437.pdf)
- [DIFUZE: Interface Aware Fuzzing for Kernel Drivers, 2017](https://acmccs.github.io/papers/p2123-corinaA.pdf)

## 3 Tools

Common and practical tools are included here, most of which have been practiced by the author and have a certain degree of universality. There are also some excellent tools that have not been maintained and updated for a long time and have very limited applicable scenarios, which are not included.

### Mutator

- [Radamsa](https://gitlab.com/akihe/radamsa): Radamsa is a test case generator for robustness testing, a.k.a. a fuzzer. It is typically used to test how well a program can withstand malformed and potentially malicious inputs. It works by reading sample files of valid data and generating interestringly different outputs from them. The main selling points of radamsa are that it has already found a slew of bugs in programs that actually matter, it is easily scriptable and, easy to get up and running. 
- [zzuf](https://github.com/samhocevar/zzuf): zzuf is a transparent application input fuzzer. It works by intercepting file operations and changing random bits in the program's input. zzuf's behaviour is deterministic, making it easy to reproduce bugs. 

### Binary

- [afl-unicorn: Fuzzing The 'Unfuzzable' ](https://www.youtube.com/watch?v=OheODvF0884): afl-unicorn lets you fuzz any piece of binary that can be emulated by Unicorn Engine. 
- [Intriguer](https://github.com/seclab-yonsei/intriguer): Intriguer is a concolic execution engine for hybrid fuzzing. The key idea of Intriguer is a field-level constraint solving, which optimizes symbolic execution with field-level information. 
- [Unicorefuzz](https://github.com/fgsect/unicorefuzz): Fuzzing the Kernel using UnicornAFL and AFL++. For details, skim through [the WOOT paper](https://www.usenix.org/system/files/woot19-paper_maier.pdf) or watch [this talk at CCCamp19](https://media.ccc.de/v/thms-32--emulate-fuzz-break-kernels). 
- [libFuzzer](http://llvm.org/docs/LibFuzzer.html): LibFuzzer is in-process, coverage-guided, evolutionary fuzzing engine. LibFuzzer is linked with the library under test, and feeds fuzzed inputs to the library via a specific fuzzing entrypoint (aka “target function”); the fuzzer then tracks which areas of the code are reached, and generates mutations on the corpus of input data in order to maximize the code coverage. The code coverage information for libFuzzer is provided by LLVM’s [SanitizerCoverage](https://clang.llvm.org/docs/SanitizerCoverage.html) instrumentation.
- [Honggfuzz](https://github.com/google/honggfuzz): A security oriented, feedback-driven, evolutionary, easy-to-use fuzzer with interesting analysis options. See the [Usage document](https://github.com/google/honggfuzz/blob/master/docs/USAGE.md) for a primer on Honggfuzz use. 
- [syzkaller](https://github.com/google/syzkaller): syzkaller is an unsupervised coverage-guided kernel fuzzer.
- [frida-fuzzer](https://github.com/andreafioraldi/frida-fuzzer):  This experimetal fuzzer is meant to be used for API in-memory fuzzing. 
- [winafl](https://github.com/googleprojectzero/winafl): A fork of AFL for fuzzing Windows binaries
- [trinity](https://github.com/kernelslacker/trinity):  Linux system call fuzzer.
- [NtCall64](https://github.com/hfiref0x/NtCall64):  Windows NT x64 syscall fuzzer .
- [kDriver-Fuzzer](https://github.com/k0keoyo/kDriver-Fuzzer): A kernel driver fuzzer, based on ioctlbf.
- [FuzzBALL](https://github.com/bitblaze-fuzzball/fuzzball): Vine-based Binary Symbolic Execution.

### API/Protocol

- [Sulley](https://github.com/OpenRCE/sulley)/[Boofuzz](https://github.com/jtpereyda/boofuzz): A fork and successor of the Sulley Fuzzing Framework 
- [fuzzowski](https://github.com/nccgroup/fuzzowski): The Network Protocol Fuzzer that we will want to use.
- [Peach](https://github.com/MozillaSecurity/peach): Peach is a fuzzing framework which uses a DSL for building fuzzers and an observer based architecture to execute and monitor them. 
- [Defensics](https://www.synopsys.com/software-integrity/security-testing/fuzz-testing.html):  Defensics is a comprehensive, versatile, automated black box fuzzer that enables organizations to efficiently and effectively discover and remediate [security weaknesses](https://www.synopsys.com/blogs/software-security/types-of-security-vulnerabilities/) in software. 
- [bsSTORM](https://beyondsecurity.com/bestorm-and-the-sdl.html?cn-reloaded=1):  Black box Fuzz Testing is a requirement of the Verification phase of the SDL, the industry-leading software security assurance process that was created by Microsoft and proven effective since 2004. 
- [API-fuzzer](https://github.com/Fuzzapi/API-fuzzer):  API Fuzzer which allows to fuzz request attributes using common pentesting techniques and lists vulnerabilities 
- [domato](https://github.com/googleprojectzero/domato): A DOM fuzzer: Written and maintained by Ivan Fratric, [ifratric@google.com](mailto:ifratric@google.com)

### Firmware

- [IOTFUZZER: Discovering Memory Corruptions in IoT Through App-based Fuzzing](https://www.ndss-symposium.org/wp-content/uploads/2018/02/ndss2018_01A-1_Chen_paper.pdf)
- [FIRM-AFL: High-Throughput Greybox Fuzzing of IoT Firmware via Augmented Process Emulation](https://www.usenix.org/conference/usenixsecurity19/presentation/zheng)
- [FIRMCORN: Vulnerability-Oriented Fuzzing of IoT Firmware via Optimized Virtual Execution](https://ieeexplore.ieee.org/document/8990098)