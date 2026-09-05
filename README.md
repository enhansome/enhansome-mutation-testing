# Awesome Mutation Testing with stars

Mutation testing evaluates a test suite by introducing small changes—called mutants—into a program and checking whether the tests detect them.

This repository catalogues mutation-testing tools, publications, talks, tutorials, and other resources. Projects are included for their practical, educational, research or historical value. Inclusion does not imply that a project is actively maintained.

[Discord Invite](https://discord.com/invite/k5JBWU2)

## Contents

* [Tools](#tools)
* [Archived tools](archived.md#archived-tools)
* [Visualisation tools](#visualisation-tools)
* [Publications](#publications)
* [Blogs/Posts](#blogsposts)
* [Videos](#videos)
* [Conference presentations](#conference-presentations)
* [Conferences](#conferences)
* [Examples and practical resources](#examples-and-practical-resources)
* [Tutorials](#tutorials)

## Tools

* Alloy
  * [MuAlloy](https://github.com/kaiyuanw/MuAlloy) ⭐ 8 | 🐛 0 | 🌐 Alloy | 📅 2018-06-14
    * [MuAlloy papers](https://github.com/kaiyuanw/MuAlloy#publications) ⭐ 8 | 🐛 0 | 🌐 Alloy | 📅 2018-06-14
* C/C++
  * [Mull](https://github.com/mull-project/mull) ⭐ 835 | 🐛 23 | 🌐 C++ | 📅 2026-07-31 - An LLVM-based mutation-testing and fault-injection tool for C and C++.
  * [Mutate++](https://github.com/nlohmann/mutate_cpp) ⭐ 194 | 🐛 10 | 🌐 CSS | 📅 2024-06-30
  * [Dextool Mutate](https://github.com/joakim-brannstrom/dextool/tree/master/plugin/mutate) ⭐ 112 | 🐛 16 | 🌐 D | 📅 2026-04-20 - A mutation-testing plug-in in the LLVM- and Clang-based Dextool suite.
  * [MART](https://github.com/thierry-tct/mart) ⭐ 26 | 🐛 0 | 🌐 C++ | 📅 2022-07-25 - A configurable mutation-testing framework based on LLVM.
  * [Frama-C Mutation](https://github.com/gpetiot/Frama-C-Mutation/) ⚠️ Archived - A Frama-C plug-in for generating mutant C programs.
  * [MUSIC](https://github.com/swtv-kaist/MUSIC) ⭐ 18 | 🐛 3 | 🌐 C++ | 📅 2026-04-24 - A configurable and extensible mutation-analysis tool for C programs.
    * [MUSIC: Mutation Analysis Tool with High Configurability and Extensibility](http://swtv.kaist.ac.kr/publications/music-mutation18.pdf)
  * [SRCIROR](https://github.com/TestingResearchIllinois/srciror) ⭐ 13 | 🐛 2 | 🌐 C++ | 📅 2018-09-06 - A mutation tool for C source code and LLVM IR.
    * [SRCIROR: A Toolset for Mutation Testing of C Source Code and LLVM Intermediate Representation](http://mir.cs.illinois.edu/farah/publications/ase18_srciror.pdf)
  * [AccMut](https://github.com/wangbo15/accmut) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2018-01-25 - An LLVM IR-based framework for accelerating mutation testing.
    * [Faster mutation analysis via equivalence modulo states](http://sei.pku.edu.cn/%7Exiongyf04/papers/ISSTA17.pdf)
  * [llvm-mutate](https://eschulte.github.io/llvm-mutate/) - An LLVM-based mutation tool for C and C++.
  * [MuCPP](https://neptuno.uca.es/redmine/projects/mucpp-mutation-tool/wiki) - A mutation system for applying class-level operators to C++ programs.
    * [Assessment of Class Mutation Operators for C++ with the MuCPP Mutation System](https://pdfs.semanticscholar.org/05d5/2ba68ed4ba8505cc92e4f27ad68c1b944842.pdf)
* C#
  * [Stryker.NET](https://github.com/stryker-mutator/stryker-net) ⭐ 2,066 | 🐛 197 | 🌐 C# | 📅 2026-09-05 - A mutation-testing tool for .NET Framework and .NET.
  * [Testura.Mutation](https://github.com/Testura/Testura.Mutation) ⭐ 106 | 🐛 23 | 🌐 C# | 📅 2022-12-08
  * [Fettle](https://github.com/ComparetheMarket/fettle) ⚠️ Archived - An experimental mutation-testing tool for C#.
  * [Faultify](https://github.com/Faultify/Faultify) ⭐ 21 | 🐛 8 | 🌐 C# | 📅 2021-12-06 - A bytecode-level mutation-testing tool for .NET.
* Clojure
  * [mutant](https://github.com/jstepien/mutant) ⚠️ Archived
* Crystal
  * [crytic](https://github.com/hanneskaeufler/crytic) ⭐ 70 | 🐛 5 | 🌐 Crystal | 📅 2025-11-20
* Elixir
  * [Mutation](https://github.com/JordiPolo/mutation) ⭐ 21 | 🐛 0 | 🌐 Elixir | 📅 2017-01-11
* Erlang
  * [Muterl](https://github.com/parsifal-47/muterl) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2022-11-04
* Go
  * [Gremlins](https://github.com/go-gremlins/gremlins) ⭐ 403 | 🐛 46 | 🌐 Go | 📅 2026-06-26
  * [Ooze](https://github.com/gtramontina/ooze) ⭐ 286 | 🐛 12 | 🌐 Go | 📅 2026-08-31
  * [go-mutesting](https://github.com/jonbaldie/go-mutesting) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2026-09-03
* Haskell
  * [FitSpec](https://github.com/rudymatela/fitspec) ⭐ 78 | 🐛 0 | 🌐 Haskell | 📅 2025-01-30 - A tool that uses mutations to refine properties for testing Haskell programs.
  * [MuCheck](https://hackage.haskell.org/package/MuCheck)
* Java/JVM
  * [PIT](https://github.com/hcoles/pitest) ⭐ 1,859 | 🐛 318 | 🌐 Java | 📅 2026-08-28 - A bytecode-level mutation-testing system for the JVM.
    * [PIT: A Practical Mutation Testing Tool for Java (Demo)](https://dl.acm.org/citation.cfm?id=2948707)
    * [An Experimental Evaluation of PIT’s Mutation Operators](http://www.diva-portal.org/smash/get/diva2:1161760/FULLTEXT01.pdf)
    * [Introduction to Mutation Testing](https://blog.frankel.ch/introduction-to-mutation-testing/)
    * [Faster Mutation Testing (in Java)](https://blog.frankel.ch/faster-mutation-testing/)
  * [LittleDarwin](https://github.com/aliparsai/LittleDarwin) ⭐ 24 | 🐛 11 | 🌐 Python | 📅 2026-05-31 - A Java mutation-testing framework implemented in Python.
    * [LittleDarwin: a Feature-Rich and Extensible Mutation Testing Framework for Large and Complex Java Systems](https://www.parsai.net/files/research/LittleDarwin%20a%20Feature-Rich%20and%20Extensible%20Mutation%20Testing%20Framework%20for%20Large%20and%20Complex%20Java%20Systems%20\(pre-print\).pdf)
  * [metamutator](https://github.com/SpoonLabs/metamutator) ⭐ 20 | 🐛 1 | 🌐 Java | 📅 2022-08-13 - A Java mutation engine based on mutant schemata and metaprogramming.
  * [Major](http://mutation-testing.org) - A compiler-integrated mutation-testing system for Java.
    * [Publications related to the Major mutation framework](http://mutation-testing.org/publ/)
* JavaScript
  * [StrykerJS](https://github.com/stryker-mutator/stryker) ⭐ 3,083 | 🐛 105 | 🌐 TypeScript | 📅 2026-09-04 - A mutation-testing framework for JavaScript and TypeScript.
  * [testtruth](https://github.com/T4LEL/testtruth) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-26 - A tool that compares mutation results before and after a Git diff to detect weakened JavaScript and TypeScript tests.
* Kotlin
  * [Mutant Kraken](https://github.com/JosueMolinaMorales/mutant-kraken) ⭐ 30 | 🐛 1 | 🌐 Rust | 📅 2025-11-06
  * [mutflow](https://github.com/anschnapp/mutflow) ⭐ 26 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-31 - A Kotlin library that performs mutation testing within the test suite after a single compilation.
* PHP
  * [Infection](https://github.com/infection)
  * [Pest PHP](https://pestphp.com/docs/mutation-testing) - Mutation testing integrated into the Pest PHP testing framework.
* Python
  * [mutmut](https://github.com/boxed/mutmut) ⭐ 1,423 | 🐛 53 | 🌐 Python | 📅 2026-09-05
  * [Cosmic Ray](https://github.com/sixty-north/cosmic-ray) ⭐ 656 | 🐛 52 | 🌐 Python | 📅 2026-08-09
* R
  * [muttest](https://github.com/jakubsob/muttest) ⭐ 26 | 🐛 2 | 🌐 R | 📅 2026-07-21 - A mutation-testing tool for assessing test assertions in R.
  * [mutator](https://github.com/PRL-PRG/mutator) ⭐ 9 | 🐛 2 | 🌐 R | 📅 2026-08-04
* Ruby
  * [Mutant](https://github.com/mbj/mutant) ⭐ 2,188 | 🐛 125 | 🌐 Ruby | 📅 2026-09-03
    * [Kill all the mutants - a deep dive into mutation testing and how the Mutant gem works](https://troessner.svbtle.com/kill-all-the-mutants-a-deep-dive-into-mutation-testing-and-how-the-mutant-gem-works)
  * [mutest](https://github.com/backus/mutest) ⚠️ Archived - A fork of Mutant with additional mutations and inline disable comments.
* Rust
  * [cargo-mutants](https://github.com/sourcefrog/cargo-mutants) ⭐ 1,284 | 🐛 101 | 🌐 Rust | 📅 2026-08-23 - A Cargo-based mutation-testing tool for Rust.
  * [mutagen](https://github.com/llogiq/mutagen) ⭐ 642 | 🐛 39 | 🌐 Rust | 📅 2023-05-29 - A mutation-testing plug-in for Rust.
* Scala
  * [Scalamu](https://github.com/sugakandrey/scalamu) ⭐ 44 | 🐛 4 | 🌐 Scala | 📅 2017-12-11
  * [Stryker4s](https://stryker-mutator.io/stryker4s/)
* Smalltalk
  * [MuTalk](https://github.com/pavel-krivanek/mutalk) ⭐ 25 | 🐛 7 | 🌐 Smalltalk | 📅 2026-04-13 - A mutation-testing tool for Pharo Smalltalk.
* Simulink
  * [MUT4SLX](https://github.com/haliliceylan/MUT4SLX) ⭐ 6 | 🐛 0 | 🌐 HTML | 📅 2025-04-29 - A model-based mutation-testing framework for Simulink and Stateflow models in MATLAB.
    * [Reproduction Package](https://github.com/haliliceylan/MUT4SLX/blob/main/Reproduction-Package-ASE-2023.md) ⭐ 6 | 🐛 0 | 🌐 HTML | 📅 2025-04-29
    * [MUT4SLX: Fast mutant generation for Simulink](https://ieeexplore.ieee.org/abstract/document/10298490)
    * [MUT4SLX: Extensions for Mutation Testing of Stateflow Models](https://ieeexplore.ieee.org/abstract/document/10621727)
* Solidity / Smart Contracts
  * [Gambit](https://github.com/Certora/gambit) ⭐ 210 | 🐛 11 | 🌐 Rust | 📅 2026-08-12 - A mutation generator for improving specifications and test suites for Solidity contracts.
  * [vertigo](https://github.com/JoranHonig/vertigo) ⭐ 208 | 🐛 17 | 🌐 Python | 📅 2023-11-21
  * [vertigo-rs](https://github.com/RareSkills/vertigo-rs) ⭐ 127 | 🐛 6 | 🌐 Python | 📅 2024-09-05 - A mutation-testing tool for Ethereum smart contracts using Foundry.
* Swift
  * [Muter](https://github.com/muter-mutation-testing/muter) ⭐ 562 | 🐛 36 | 🌐 Swift | 📅 2026-07-21
* OCaml
  * [Mutaml](https://github.com/jmid/mutaml) ⭐ 74 | 🐛 12 | 🌐 OCaml | 📅 2025-11-24
* Lean
  * [Mutate.lean](https://github.com/jubnzv/Mutate.lean) ⭐ 3 | 🐛 0 | 🌐 Lean | 📅 2026-06-24
* Other
  * [Mutahunter](https://github.com/codeintegrity-ai/mutahunter) ⭐ 300 | 🐛 2 | 🌐 Python | 📅 2025-04-17 - An open-source, language-agnostic mutation-testing tool.
  * [Universal Mutator](https://github.com/agroce/universalmutator) ⭐ 162 | 🐛 6 | 🌐 Python | 📅 2026-05-20 - A regular-expression-based mutation tool for source code in multiple languages.
  * [boggart](https://github.com/squaresLab/boggart) ⭐ 2 | 🐛 9 | 🌐 Python | 📅 2019-01-09 - A lightweight, extensible, language-independent mutation-testing framework.
  * [Bough](https://github.com/CodeEnPlace/bough) ⭐ 1 | 🐛 33 | 🌐 Rust | 📅 2026-04-10 - A polyglot incremental mutation-testing tool.

## Visualisation tools

* [VisMAn](https://github.com/sqrlab/VisMAn) ⭐ 6 | 🐛 0 | 🌐 Java | 📅 2013-08-14

## Publications

Publication titles retain their original spelling. Entries link to DOI or publisher pages or to locally archived copies when redistribution is permitted.

### Papers

> **Local PDF** links to a file stored in this repository. **External** links to another website.

* **External:** [Mario Rosano Barroso (2026) *Aplicación de modelos de aprendizaje profundo al Predictive Mutation Testing*](http://hdl.handle.net/10498/39116)
* **Local PDF:** [Hervé Robert, Shubho Sengupta (2025) *Mutation-Guided LLM-based Test Generation at Meta*](documents/Mutation-Guided%20LLM-based%20Test%20Generation%20at%20Meta%20\(2025\).pdf)
* **Local PDF:** [Jeongju Sohn, Ezekiel Soremekun, Michail Papadakis (2025) *Latent Mutants: A large-scale study on the Interplay between mutation testing and software evolution*](documents/Latent%20Mutants%20A%20large%20scale%20study%20on%20the%20Interplay%20between%20mutation%20testing%20and%20software%20evolution%20\(2025\).pdf)
* **External:** [Deniz Eren, Gabriele Taentzer, Sascha Lehmann, Freya Dorn, Daniel Neufeld, Christoph Bockisch (2025) *Advanced Mutation Testing of Java Bytecode Using Model Transformation*](https://doi.org/10.18420/se2025-11)
* **External:** [Bekzat Skakov (2025) *LLM-DRIVEN MUTATION TESTING IN MICROARCHITECTURE VERIFICATION*](https://nur.nu.edu.kz/handle/123456789/8509)
* **Local PDF:** [Marcela G. dos Santos, Sylvain Hallé, Fábio Petrillo (2025) *Mutation Testing for Industrial Robotic Systems*](documents/Mutation%20Testing%20for%20Industrial%20Robotic%20Systems%20\(2025\).pdf) — [DOI](https://doi.org/10.4204/eptcs.436.5)
* **External:** [Pablo Gómez‐Abajo, Esther Guerra, Juan de Lara (2025) *Wodel-Test: A model-based framework for engineering language-specific mutation testing tools*](https://doi.org/10.1016/j.softx.2025.102195)
* **Local PDF:** [Dolores Miao, Ignacio Laguna, Giorgis Georgakoudis, Konstantinos Parasyris, Cindy Rubio-González (2024) *An automated OpenMP mutation testing framework for performance optimization*](documents/An%20automated%20OpenMP%20mutation%20testing%20framework%20for%20performance%20optimization%20\(2024\).pdf) — [DOI](https://doi.org/10.1016/j.parco.2024.103097)
* **Local PDF:** [Enzo Nicourt, Benjamin Kushigian, Chandrakana Nandi, Yliès Falcone (2024) *Using Mutation Testing To Improve and Minimize Test Suites for Smart Contracts*](documents/Using%20Mutation%20Testing%20To%20Improve%20and%20Minimize%20Test%20Suites%20for%20Smart%20Contracts.pdf)
* **External:** [Kadiatou Diallo, Zizhao Chen, W. E. Wong, Shou-Yu Lee (2024) *An Analysis and Comparison of Mutation Testing Tools for Python*](https://doi.org/10.1109/dsa63982.2024.00030)
* **Local PDF:** [Zhifei Chen, Yang Hao, Qichao Liu, Yuyong Liu, Mingyang Zhu, Liang Xiao (2024) *Deep Learning for Hyperspectral Image Classification: A Critical Evaluation via Mutation Testing*](documents/Deep%20Learning%20for%20Hyperspectral%20Image%20Classification%20A%20Critical%20Evaluation%20via%20Mutation%20Testing%20\(2024\).pdf) — [DOI](https://doi.org/10.3390/rs16244695)
* **External:** [Serhat Uzunbayir, Kaan Kurtel (2024) *Leveraging Genetic Algorithms for Efficient Search-Based Higher Order Mutation Testing*](https://doi.org/10.31577/cai_2024_3_709)
* **External:** [Erasmo Junkes (2024) *Mutant Codebraker: A game to assist in teaching mutation testing*](http://repositorio.utfpr.edu.br/jspui/handle/1/36188)
* **External:** [Yichun Wang, Zhiyi Zhang, Yongming Yao, Zhiqiu Huang (2023) *A Fine-Grained Evaluation of Mutation Operators for Deep Learning Systems: A Selective Mutation Approach*](https://doi.org/10.1145/3609437.3609453)
* **External:** [Sergen Aşik, Uğur Yayan (2023) *Generating Python Mutants From Bug Fixes Using Neural Machine Translation*](https://doi.org/10.1109/access.2023.3302695)
* **External:** [Miloš Ojdanić, Ahmed Khanfir, Aayush Garg, R. Degiovanni, Mike Papadakis, Yves Le Traon (2023) *On Comparing Mutation Testing Tools through Learning-based Mutant Selection*](https://doi.org/10.1109/ast58925.2023.00008)
* **External:** [Ezio Bartocci, Leonardo Mariani, Dejan Ničković, Drishti Yadav (2023) *Property-Based Mutation Testing*](https://doi.org/10.1109/icst57152.2023.00029)
* **Local PDF:** [Pedro Delgado-Pérez, Ana B. Sánchez, Sergio Segura, Inmaculada Medina-Bulo (2022) *Mutation testing in the wild: findings from GitHub*](documents/Mutation%20testing%20in%20the%20wild:%20findings%20from%20GitHub%20\(2022\).pdf) — [DOI](https://doi.org/10.1007/s10664-022-10177-8)
* **Local PDF:** [Giovani Guizzo, Federica Sarro, Jens Krinke, Silvia Regina Vergilio (2022) *Sentinel: A Hyper-Heuristic for the Generation of Mutant Reduction Strategies*](documents/Sentinel:%20A%20Hyper-Heuristic%20for%20the%20Generation%20of%20Mutant%20Reduction%20Strategies%20\(2021\).pdf) — [DOI](https://doi.org/10.1109/TSE.2020.3002496)
* **Local PDF:** [Deepti Mishra, Biswaranjan Acharya, Dharashree Rath, Vassilis C. Gerogiannis, Andreas Kanavos (2022) *A Novel Real Coded Genetic Algorithm for Software Mutation Testing*](documents/A%20Novel%20Real%20Coded%20Genetic%20Algorithm%20for%20Software%20Mutation%20Testing%20\(2022\).pdf) — [DOI](https://doi.org/10.3390/sym14081525)
* **External:** [Nishtha Jatana, Bharti Suri (2022) *Application of Nature Inspired Algorithms to Test Data Generation/Selection/Minimization using Mutation Testing*](https://doi.org/10.2174/9789815036091122010016)
* **External:** [Miloš Ojdanić (2022) *Change-aware mutation testing for evolving systems*](https://doi.org/10.1145/3540250.3558911)
* **External:** [Matheus Yudi Fujiike Ferreira (2022) *Generation test data for weak mutation testing using search-based techniques*](http://repositorio.utfpr.edu.br/jspui/handle/1/33093)
* **External:** [Sara Tarek ElSayed Abbas, Rohayanti Hassan, Shahliza Abd Halim, Shahreen Kasim, Rohaizan Ramlan (2022) *Investigation on Java Mutation Testing Tools*](https://doi.org/10.30630/joiv.6.2-2.1090)
* **External:** [Li-Chao Feng, Xing-Ya Wang, Shi-Yu Zhang, Rui-Zhi Gao, Zhi-Hong Zhao (2022) *Mutation Operator Reduction for Cost-effective Deep Learning Software Testing via Decision Boundary Change Measurement*](https://doi.org/10.53106/160792642022052303018)
* **Local PDF:** [Miloš Ojdanić, Ezekiel Soremekun, Renzo Degiovanni, Mike Papadakis, Yves Le Traon (2022) *Mutation Testing in Evolving Systems: Studying the Relevance of Mutants to Code Evolution*](documents/Mutation%20Testing%20in%20Evolving%20Systems%20\(2022\).pdf) — [DOI](https://doi.org/10.1145/3530786)
* **External:** [Daniel Fortunato, José Campos, Rui Abreu (2022) *Mutation Testing of Quantum Programs: A Case Study With Qiskit*](https://doi.org/10.1109/tqe.2022.3195061)
* **External:** [Xinyi Wang, Tongxuan Yu, Paolo Arcaini, Tao Yue, Shaukat Ali (2022) *Mutation-based test generation for quantum programs with multi-objective search*](https://doi.org/10.1145/3512290.3528869)
* **External:** [Daniel Fortunato, José Campos, Rui Abreu (2022) *QMutPy: a mutation testing tool for Quantum algorithms and applications in Qiskit*](https://doi.org/10.1145/3533767.3543296)
* **External:** [Morena Barboni, Francesco Casoni, Andrea Morichetta, Andrea Polini (2022) *ReSuMo: Regression Mutation Testing for Solidity Smart Contracts*](https://doi.org/10.1007/978-3-031-14179-9_5)
* **External:** [Van-Nho Do, Quang-Vu Nguyen, Thanh-Binh Nguyen (2022) *Toward Improving the Quality of Mutation Operator and Test Case Effectiveness in Higher-Order Mutation Testing*](https://doi.org/10.1142/s2196888822500282)
* **Local PDF:** [Goran Petrović, Marko Ivanković, Gordon Fraser, René Just (2021) *Practical Mutation Testing at Scale: A view from Google*](documents/Practical%20Mutation%20Testing%20at%20Scale%20A%20view%20from%20Google%20\(2021\).pdf) — [DOI](https://doi.org/10.1109/TSE.2021.3107634)
* **Local PDF:** [Goran Petrović, Marko Ivanković, Gordon Fraser, René Just (2021) *Does mutation testing improve testing practices?*](documents/Does%20mutation%20testing%20improve%20testing%20practices%3F%20\(2021\).pdf) — [DOI](https://doi.org/10.1109/ICSE43902.2021.00087)
* **External:** [Zhenpeng Liu, Xianwei Yang, Yi Liu, Yonggang Zhao, Xiaofei Li (2021) *ImReMuDF: Redundant Mutants Identification Method Based on Definition and Reference of Variables*](https://doi.org/10.1155/2021/7543896)
* **External:** [Jinlei Sun, Song Huang, Changyou Zheng, Tingyong Wang, Cheng Zong, Zhanwei Hui (2021) *Mutation testing for integer overflow in ethereum smart contracts*](https://doi.org/10.26599/tst.2020.9010036)
* **External:** [Galina Cherneva, Pavlо Khalimov (2021) *MUTATION TESTING OF ACCESS CONTROL POLICIES*](https://doi.org/10.20998/2522-9052.2021.1.17)
* **External:** [Changqing Wei, Xiangjuan Yao, Dunwei Gong, Huai Liu (2021) *Spectral clustering based mutant reduction for mutation testing*](https://doi.org/10.1016/j.infsof.2020.106502)
* **Local PDF:** [Y. Ivanova, A. Khritankov (2020) *RegularMutator: A Mutation Testing Tool for Solidity Smart Contracts*](documents/RegularMutator:%20A%20Mutation%20Testing%20Tool%20for%20Solidity%20Smart%20Contracts%20\(2020\).pdf) — [DOI](https://doi.org/10.1016/j.procs.2020.11.009)
* **Local PDF:** [Pedro Delgado-Pérez, Ana Belén Sánchez, Sergio Segura, Inmaculada Medina-Bulo (2020) *Performance mutation testing*](documents/Performance%20Mutation%20Testing%20\(2010\).pdf) — [DOI](https://doi.org/10.1002/stvr.1728)
* **External:** [Beatriz Souza, Rohit Gheyi (2020) *A Lightweight Technique to Identify Equivalent Mutants*](https://doi.org/10.5753/cbsoft_estendido.2020.14630)
* **Local PDF:** [Alessandro Viola Pizzoleto, Fabiano Cutigi Ferrari, Jeff Offutt, Leo Fernandes, Márcio Ribeiro (2019) *A Systematic Literature Review of Techniques and Metrics to Reduce the Cost of Mutation Testing*](documents/A%20Systematic%20Literature%20Review%20of%20Techniques%20and%20Metrics%20to%20Reduce%20the%20Cost%20of%20Mutation%20Testing%20\(2019\).pdf) — [DOI](https://doi.org/10.1016/j.jss.2019.07.100)
* **Local PDF:** [August Shi, Jonathan Bell, Darko Marinov (2019) *Mitigating the Effects of Flaky Tests on Mutation Testing*](documents/Mitigating%20the%20Effects%20of%20Flaky%20Tests%20on%20Mutation%20Testing%20\(2019\).pdf) — [DOI](https://doi.org/10.1145/3293882.3330568)
* **Local PDF:** [Esther Guerra, Jesús Sánchez Cuadrado, Juan de Lara (2019) *Towards effective mutation testing for ATL*](documents/Towards%20effective%20mutation%20testing%20for%20ATL%20\(2019\).pdf)
* **Local PDF:** [Mike Papadakis, Marinos Kintis, Jie Zhang, Yue Jia, Yves Le Traon, Mark Harman (2019) *Mutation Testing Advances: An Analysis and Survey*](documents/Mutation%20Testing%20Advances:%20An%20Analysis%20and%20Survey%20\(2017\).pdf) — [DOI](https://doi.org/10.1016/bs.adcom.2018.03.015)
* **External:** [Jackson Antonio do Prado Lima, Silvia Regina Vergilio (2019) *A systematic mapping study on higher order mutation testing*](https://doi.org/10.1016/j.jss.2019.04.031)
* **External:** [Serhat Uzunbayir, Kaan Kurtel (2019) *An Analysis on Mutation Testing Tools For C# Programming Language*](https://doi.org/10.1109/ubmk.2019.8907222)
* **External:** [Muhammad Bilal Bashir, Aamer Nadeem (2019) *An Evolutionary Mutation Testing System for Java Programs: eMuJava*](https://doi.org/10.1007/978-3-030-22868-2_58)
* **External:** [Qiang Hu, Lei Ma, Xiaofei Xie, Bing Yu, Yang Liu, Jianjun Zhao (2019) *DeepMutation++: A Mutation Testing Framework for Deep Learning Systems*](https://doi.org/10.1109/ase.2019.00126)
* **External:** [Patrick Chapman, Dianxiang Xu, Lin Deng, Yin Xiong (2019) *Deviant: A Mutation Testing Tool for Solidity Smart Contracts*](https://doi.org/10.1109/blockchain.2019.00050)
* **External:** [Alex Alberto (2019) *Formal mutation testing in Circus process algebra*](https://doi.org/10.11606/t.55.2019.tde-04012019-112931)
* **Local PDF:** [Yoo-Min Choi, Dong-Jin Lim (2019) *Model-Based Test Suite Generation Using Mutation Analysis for Fault Localization*](documents/Model-Based%20Test%20Suite%20Generation%20Using%20Mutation%20Analysis%20for%20Fault%20Localization%20\(2019\).pdf) — [DOI](https://doi.org/10.3390/app9173492)
* **External:** [Andreas Fellner, Willibald Krenn, Rupert Schlick, Thorsten Tarrach, Georg Weissenbacher (2019) *Model-based, Mutation-driven Test-case Generation Via Heuristic-guided Branching Search*](https://doi.org/10.1145/3289256)
* **External:** [Tomasz Lewowski, Lech Madeyski (2019) *Mutants as Patches: Towards a formal approach to Mutation Testing*](https://doi.org/10.2478/fcds-2019-0019)
* **External:** [Nishtha Jatana, Bharti Suri (2019) *Particle Swarm and Genetic Algorithm applied to mutation testing for test data generation: A comparative evaluation*](https://doi.org/10.1016/j.jksuci.2019.05.004)
* **External:** [Thomas Laurent, Anthony Ventresque (2019) *PIT-HOM: an Extension of Pitest for Higher Order Mutation Analysis*](https://doi.org/10.1109/icstw.2019.00036)
* **External:** [Muhammad Rashid Naeem, Tao Lin, Hamad Naeem, Farhan Ullah, Saqib Saeed (2019) *Scalable Mutation Testing Using Predictive Analysis of Deep Learning Model*](https://doi.org/10.1109/access.2019.2950171)
* **Local PDF:** [Lin Deng, Jeff Offutt (2018) *Reducing the Cost of Android Mutation Testing*](documents/Reducing%20the%20Cost%20of%20Android%20Mutation%20Testing%20\(2018\).pdf)
* **Local PDF:** [Goran Petrović, Marko Ivanković (2018) *State of Mutation Testing at Google*](documents/State%20of%20Mutation%20Testing%20at%20Google%20\(2018\).pdf) — [DOI](https://doi.org/10.1145/3183519.3183521)
* **Local PDF:** [Goran Petrović, Marko Ivanković, Bob Kurtz, Paul Ammann, René Just (2018) *An Industrial Application of Mutation Testing: Lessons, Challenges, and Research Directions*](documents/An%20Industrial%20Application%20of%20Mutation%20Testing%20Lessons,%20Challenges,%20and%20Research%20Directions%20\(2018\).pdf) — [DOI](https://doi.org/10.1109/ICSTW.2018.00027)
* **Local PDF:** [Sten Vercammen, Mohammad Ghafari, Serge Demeyer, Markus Borg (2018) *Goal-Oriented Mutation Testing with Focal Methods*](documents/Goal-Oriented%20Mutation%20Testing%20with%20Focal%20Methods%20\(2018\).pdf) — [DOI](https://doi.org/10.1145/3278186.3278190)
* **Local PDF:** [Qianqian Zhu, Annibale Panichella, Andy Zaidman (2018) *A Systematic Literature Review of How Mutation Testing Supports Quality Assurance Processes*](documents/A%20Systematic%20Literature%20Review%20of%20How%20Mutation%20Testing%20Supports%20Quality%20Assurance%20Processes%20\(2018\).pdf) — [DOI](https://doi.org/10.1002/stvr.1675)
* **Local PDF:** [Lingchao Chen, Lingming Zhang (2018) *Speeding up Mutation Testing via Regression Test Selection: An Extensive Study*](documents/Speeding%20up%20Mutation%20Testing%20via%20Regression%20Test%20Selection:%20An%20Extensive%20Study%20\(2018\).pdf)
* **External:** [Qianqian Zhu, Annibale Panichella, Andy Zaidman (2018) *An Investigation of Compression Techniques to Speed up Mutation Testing*](https://doi.org/10.1109/icst.2018.00035)
* **External:** [Lei Ma, Fuyuan Zhang, Jiyuan Sun, Minhui Xue, Bo Li, Felix Juefei-Xu, Chao Xie, Li Li, Yang Liu, Jianjun Zhao, Yadong Wang (2018) *DeepMutation: Mutation Testing of Deep Learning Systems*](https://doi.org/10.1109/issre.2018.00021)
* **External:** [S. Rani, Bharti Suri (2018) *Equivalent Mutant Problem and its Problem-Solving Techniques: A Retrospective View*](https://doi.org/10.1109/confluence.2018.8442785)
* **External:** [Farah Hariri (2018) *Exploring design decisions for mutation testing*](http://hdl.handle.net/2142/101008)
* **External:** [Paolo Arcaini, Angelo Gargantini, Elvinia Riccobene (2018) *Fault‐based test generation for regular expressions by mutation*](https://doi.org/10.1002/stvr.1664)
* **External:** [Diego Rodríguez-Baquero, Mario Linares‐Vásquez (2018) *Mutode: generic JavaScript and Node.js mutation testing tool*](https://doi.org/10.1145/3213846.3229504)
* **External:** [Rodolfo Adamshuk Silva (2018) *Search based software testing for the generation of synchronization sequences for mutation testing of concurrent programs*](https://doi.org/10.11606/t.55.2018.tde-10102018-141934)
* **External:** [Jorge López, Natalia Kushik, Nina Yevtushenko (2018) *Source code optimization using equivalent mutants*](https://doi.org/10.1016/j.infsof.2018.06.013)
* **Local PDF:** [Pablo C. Cañizares, Alberto Núñez, Juan de Lara (2017) *OUTRIDER: Optimizing the mUtation Testing pRocess In Distributed EnviRonments*](documents/OUTRIDER:%20Optimizing%20the%20mUtation%20Testing%20pRocess%20In%20Distributed%20EnviRonments%20\(2017\).pdf)
* **Local PDF:** [Qianqian Zhu, Annibale Panichella, Andy Zaidman (2017) *Speeding-Up Mutation Testing via Data Compression and State Infection*](documents/Speeding-Up%20Mutation%20Testing%20via%20Data%20Compression%20and%20State%20Infection%20\(2017\).pdf)
* **External:** [Allison Sullivan, Kaiyuan Wang, Razieh Nokhbeh Zaeem, S. Khurshid (2017) *Automated Test Generation and Mutation Testing for Alloy*](https://doi.org/10.1109/icst.2017.31)
* **External:** [Leontiuc, Ioana (2017) *Continuous Mutation Testing in Modern Software Development*](http://resolver.tudelft.nl/uuid:ce135a31-972f-4f96-bfbb-28b813045e1b)
* **Local PDF:** [Anna Derezińska, Marcin Rudnik (2017) *Evaluation of Mutant Sampling Criteria in Object-Oriented Mutation Testing*](documents/Evaluation%20of%20Mutant%20Sampling%20Criteria%20in%20Object-Oriented%20Mutation%20Testing%20\(2017\).pdf) — [DOI](https://doi.org/10.15439/2017f375)
* **External:** [Mayank Singh, Viranjay M. Srivastava (2017) *Extended firm mutation testing: A cost reduction technique for mutation testing*](https://doi.org/10.1109/iciip.2017.8313788)
* **External:** [Ahmed S. Ghiduk, M. Girgis, Marwa H. Shehata (2017) *Higher order mutation testing: A Systematic Literature Review*](https://doi.org/10.1016/j.cosrev.2017.06.001)
* **External:** [Marinos Kintis, Mike Papadakis, Andreas Papadopoulos, Evangelos Valvis, Nicos Malevris, Yves Le Traon (2017) *How effective are mutation testing tools? An empirical analysis of Java mutation testing tools with manual analysis and real faults*](https://doi.org/10.1007/s10664-017-9582-5)
* **External:** [Fan Wu, Jay Nanavati, Mark Harman, Yue Jia, Jens Krinke (2017) *Memory mutation testing*](https://doi.org/10.1016/j.infsof.2016.03.002)
* **External:** [Dunwei Gong, Gongjie Zhang, Xiangjuan Yao, Fanlin Meng (2017) *Mutant reduction based on dominance relation for weak mutation testing*](https://doi.org/10.1016/j.infsof.2016.05.001)
* **External:** [Phra Pridsadi Tadeesom, Taratip Suwannasart (2017) *Mutation Operators in BPMN Model*](https://doi.org/10.1145/3178264.3178286)
* **External:** [Le Thi My Hanh, Nguyen Thanh Binh, Khuat Thanh Tung (2017) *Parallel Mutant Execution Techniques in Mutation Testing Process for Simulink Models*](https://doi.org/10.26636/jtit.2017.113617)
* **External:** [Nishtha Jatana, Bharti Suri, Rani Shweta (2017) *Systematic Literature Review on Search Based Mutation Testing*](https://doi.org/10.5277/e-inf170103)
* **Local PDF:** [Joanna Strug, Barbara Strug (2017) *Using Classification for Cost Reduction of Applying Mutation Testing*](documents/Using%20Classification%20for%20Cost%20Reduction%20of%20Applying%20Mutation%20Testing%20\(2017\).pdf) — [DOI](https://doi.org/10.15439/2017f215)
* **Local PDF:** [Jie Zhang, Ziyi Wang, Lingming Zhang, Dan Hao, Lei Zang, Shiyang Cheng, Lu Zhang (2016) *Predictive Mutation Testing*](documents/Predictive%20Mutation%20Testing%20\(2016\).pdf) — [DOI](https://doi.org/10.1145/2931037.2931038)
* **Local PDF:** [Marinos Kintis (2016) *Effective Methods to Tackle the Equivalent Mutant Problem when Testing Software with Mutation*](documents/Effective%20Methods%20to%20Tackle%20the%20Equivalent%20Mutant%20Problem%20when%20Testing%20Software%20with%20Mutation%20\(2016\).pdf)
* **External:** [Zhu, Qianqian, Panichella, Annibale, Zaidman, Andy (2016) *A systematic literature review of how mutation testing supports test activities*](https://doi.org/10.7287/peerj.preprints.2483v1)
* **External:** [Marinos Kintis, Mike Papadakis, Andreas Papadopoulos, Evangelos Valvis, Nicos Malevris (2016) *Analysing and Comparing the Effectiveness of Mutation Testing Tools: A Manual Study*](https://doi.org/10.1109/scam.2016.28)
* **Local PDF:** [Joanna Strug (2016) *Applying Mutation Testing for Assessing Test Suites Quality at Model Level*](documents/Applying%20Mutation%20Testing%20for%20Assessing%20Test%20Suites%20Quality%20at%20Model%20Level%20\(2016\).pdf) — [DOI](https://doi.org/10.15439/2016f82)
* **External:** [Thomas Laurent, Anthony Ventresque, Mike Papadakis, Christopher Henard, Y. Traon (2016) *Assessing and Improving the Mutation Testing Practice of PIT*](https://doi.org/10.1109/icst.2017.47)
* **External:** [Joanna Strug (2016) *Mutation Testing Approach to Negative Testing*](https://doi.org/10.1155/2016/6589140)
* **External:** [Eduard P. Enoiu, Daniel Sundmark, Adnan Čaušević, Robert Feldt, Paul Pettersson (2016) *Mutation-Based Test Generation for PLC Embedded Software Using Model Checking*](https://doi.org/10.1007/978-3-319-47443-4_10)
* **External:** [Henry Coles, Thomas Laurent, Christopher Henard, Mike Papadakis, Anthony Ventresque (2016) *PIT: a practical mutation testing tool for Java (demo)*](https://doi.org/10.1145/2931037.2948707)
* **External:** [Mehrnoosh Ebrahimipour (2016) *Undefined Behaviour in Mutation Testing*](http://summit.sfu.ca/item/16790)
* **External:** [Nan Li, Michael West, Anthony Escalona, Vinicius H. S. Durelli (2015) *Mutation testing in practice using Ruby*](https://doi.org/10.1109/icstw.2015.7107453)
* **External:** [Yiling Lou, Dan Hao, Lu Zhang (2015) *Mutation-based test-case prioritization in software evolution*](https://doi.org/10.1109/issre.2015.7381798)
* **External:** [Mike Papadakis, Yue Jia, M. Harman, Yves Le Traon (2015) *Trivial Compiler Equivalence: A Large Scale Empirical Study of a Simple, Fast and Effective Equivalent Mutant Detection Technique*](https://doi.org/10.5555/2818754.2818867)
* **Local PDF:** [René Just, Darioush Jalali, Laura Inozemtseva, Michael D. Ernst, Reid Holmes, Gordon Fraser (2014) *Are Mutants a Valid Substitute for Real Faults in Software Testing?*](documents/Are%20Mutants%20a%20Valid%20Substitute%20for%20Real%20Faults%20in%20Software%20Testing%3F%20\(2014\).pdf) — [DOI](https://doi.org/10.1145/2635868.2635929)
* **Local PDF:** [Lorena Gutiérrez-Madroñal, J. Domínguez-Jiménez, I. Medina-Bulo (2014) *Mutation Testing: Guideline and Mutation Operator Classification*](documents/Mutation%20Testing%20Guideline%20and%20Mutation%20Operator%20Classification%20\(2014\).pdf)
* **Local PDF:** [L. Madeyski, W. Orzeszyna, R. Torkar, M. Józala (2014) *Overcoming the Equivalent Mutant Problem: A Systematic Literature Review and a Comparative Experiment of Second Order Mutation*](documents/Overcoming%20the%20Equivalent%20Mutant%20Problem%20A%20Systematic%20Literature%20Review%20and%20a%20Comparative%20Experiment%20of%20Second%20Order%20Mutation%20\(2014\).pdf)
* **External:** [Srinivas Prasad (2014) *A Novel Approach of Mutation Testing of Object-Oriented Programs*](https://doi.org/10.15866/irecos.v9i11.4542)
* **External:** [LEONARDO DA SILVA SOUSA (2014) *A service-based infrastructure for evolution of mutation testing*](http://repositorio.bc.ufg.br/tede/handle/tede/4647)
* **External:** [Gordon Fraser, Andrea Arcuri (2014) *Achieving scalable mutation-based generation of whole test suites*](https://doi.org/10.1007/s10664-013-9299-z)
* **External:** [Jie Zhang, Muyao Zhu, Dan Hao, Lu Zhang (2014) *An Empirical Study on the Scalability of Selective Mutation Testing*](https://doi.org/10.1109/issre.2014.27)
* **External:** [Mike Papadakis, Y. Traon (2014) *Effective fault localization via mutation analysis: a selective mutation approach*](https://doi.org/10.1145/2554850.2554978)
* **External:** [Marinos Kintis, Mike Papadakis, Nicos Malevris (2014) *Employing second‐order mutation for isolating first‐order equivalent mutants*](https://doi.org/10.1002/stvr.1529)
* **External:** [Mike Papadakis, Marcio Delamaro, Yves Le Traon (2014) *Mitigating the effects of equivalent mutants with mutant classification strategies*](https://doi.org/10.1016/j.scico.2014.05.012)
* **External:** [Pedro Reales, Macario Polo, José Luis Fernández-Alemán, Ambrosio Toval, Mario Piattini (2014) *Mutation Testing*](https://doi.org/10.1109/ms.2014.68)
* **External:** [Francisco Carlos, M Souza, Mike Papadakis, Vinícius H. S. Durelli, Delamaro, Marcio Eduardo (2014) *Test Data Generation Techniques for Mutation Testing: A Systematic Mapping*](https://doi.org/10.13140/rg.2.1.3699.9209)
* **External:** [Lingming Zhang (2014) *Unifying regression testing with mutation testing*](http://hdl.handle.net/2152/25055)
* **Local PDF:** [Lingming Zhang, Darko Marinov, Sarfraz Khurshid (2013) *Faster Mutation Testing Inspired by Test Prioritization and Reduction*](documents/Faster%20Mutation%20Testing%20Inspired%20by%20Test%20Prioritization%20and%20Reduction%20\(2013\).pdf) — [DOI](https://doi.org/10.1145/2483760.2483782)
* **Local PDF:** [Bouchaib Falah, Bouriat Salwa (2013) *Effectiveness of Mutation Testing Techniques: Reducing Mutation Cost*](documents/Effectiveness%20of%20Mutation%20Testing%20Techniques%20Reducing%20Mutation%20Cost%20\(2013\).pdf)
* **Local PDF:** [Quang Vu Nguyen, Lech Madeyski (2013) *Problems of Mutation Testing and Higher Order Mutation Testing*](documents/Problems%20of%20Mutation%20Testing%20and%20Higher%20Order%20Mutation%20Testing%20\(2013\).pdf)
* **Local PDF:** [Lingming Zhang, Milos Gligoric, Darko Marinov, Sarfraz Khurshid (2013) *Operator-Based and Random Mutant Selection: Better Together*](documents/Operator-Based%20and%20Random%20Mutant%20Selection%20Better%20Together%20\(2013\).pdf)
* **External:** [D. Singh, B. Suri (2013) *Mutation testing tools- an empirical study*](https://doi.org/10.1049/cp.2013.2596)
* **Local PDF:** [Kevin Jalbert, Jeremy S. Bradbury (2012) *Predicting Mutation Scores using Source Code and Test Suite Metrics*](documents/Predicting%20Mutation%20Score%20Using%20Source%20Code%20and%20Test%20Suite%20Metrics%20\(2012\).pdf)
* **External:** [David Schuler, Andreas Zeller (2012) *Covering and Uncovering Equivalent Mutants*](https://doi.org/10.1002/stvr.1473)
* **External:** [Mike Papadakis, Nicos Malevris (2012) *Mutation based test case generation via a path selection strategy*](https://doi.org/10.1016/j.infsof.2012.02.004)
* **External:** [René Just (2012) *On effective and efficient mutation analysis for unit and integration testing*](https://doi.org/10.18725/oparu-2474)
* **External:** [Pedro Reales Mateo, Macario Polo Usaola (2012) *Parallel mutation testing*](https://doi.org/10.1002/stvr.1471)
* **External:** [Lingming Zhang, Darko Marinov, Lu Zhang, Sarfraz Khurshid (2012) *Regression mutation testing*](https://doi.org/10.1145/2338965.2336793)
* **External:** [Eric Schulte, Zachary P. Fry, Ethan Fast, Westley Weimer, Stephanie Forrest (2012) *Software Mutational Robustness*](https://doi.org/10.48550/arxiv.1204.4224)
* **External:** [Bernhard K. Aichernig, Elisabeth Jöbstl (2012) *Towards Symbolic Model-Based Mutation Testing: Combining Reachability and Refinement Checking*](https://doi.org/10.4204/eptcs.80.7)
* **External:** [Simona Nica, F. Wotawa (2012) *Using Constraints for Equivalent Mutant Detection*](https://doi.org/10.4204/eptcs.86.1)
* **Local PDF:** [David Schuler (2011) *Assessing Test Quality*](documents/Assessing%20Test%20Quality%20\(2011\).pdf)
* **Local PDF:** [John A. Clark, Haitao Dan, Robert M. Hierons (2011) *Semantic Mutation Testing*](documents/Semantic%20mutation%20testing%20\(2011\).pdf) — [DOI](https://doi.org/10.1016/j.scico.2011.03.011)
* **External:** [J.J. Domínguez-Jiménez, A. Estero-Botaro, A. García-Domínguez, I. Medina-Bulo (2011) *Evolutionary mutation testing*](https://doi.org/10.1016/j.infsof.2011.03.008)
* **External:** [Sergio Segura, Segura, S, Benavides, D, Antonio Ruiz-Cortés, Ruiz Cortés, Antonio, Segura Rueda, Sergio, Robert M. Hierons, Benavides Cuevas, David Felipe, Hierons, Robert M., David Benavides, Hierons, RM, Ruiz-Cortes, A (2011) *Mutation testing on an object-oriented framework: An experience report*](https://doi.org/10.1016/j.infsof.2011.03.006)
* **External:** [Z. Ivanković, D. Radosav, B. Markoski (2011) *Mutation Testing: Object-Oriented Mutation and Testing Tools*](https://doi.org/10.7251/jit1102105i)
* **External:** [Frédéric Dadeau, Pierre-Cyrille Héam, Rafik Kheddam (2011) *Mutation-Based Test Generation from Security Protocols in HLPSL*](https://doi.org/10.1109/icst.2011.42)
* **External:** [Sam Ratcliff, David R. White, John A. Clark (2011) *Searching for invariants using genetic programming and mutation testing*](https://doi.org/10.1145/2001576.2001832)
* **External:** [Mark Harman, Yue Jia, William B. Langdon (2011) *Strong higher order mutation-based test data generation*](https://doi.org/10.1145/2025113.2025144)
* **External:** [Ronny Mandal (2011) *Towards Safe Mutation Testing in a Sandbox Environment*](http://hdl.handle.net/10852/8888)
* **Local PDF:** [Yue Jia, Mark Harman (2010) *An Analysis and Survey of the Development of Mutation Testing*](documents/An%20Analysis%20and%20Survey%20of%20the%20Development%20of%20Mutation%20Testing%20\(2010\).pdf) — [DOI](https://doi.org/10.1109/TSE.2010.62)
* **External:** [M. Harman, Yue Jia, W. Langdon (2010) *A Manifesto for Higher Order Mutation Testing*](https://doi.org/10.1109/icstw.2010.13)
* **External:** [William B. Langdon, Mark Harman, Yue Jia (2010) *Efficient multi-objective higher order mutation testing with genetic programming*](https://doi.org/10.1016/j.jss.2010.07.027)
* **External:** [Lu Zhang, Shan-Shan Hou, Jun-Jue Hu, Tao Xie, Hong Mei (2010) *Is operator-based mutant selection superior to random mutant selection?*](https://doi.org/10.1145/1806799.1806863)
* **External:** [L. Madeyski, N. Radyk (2010) *Judy – a mutation testing tool for Java*](https://doi.org/10.1049/iet-sen.2008.0038)
* **External:** [Yue Jia, Mark Harman (2009) *Higher Order Mutation Testing*](https://doi.org/10.1016/j.infsof.2008.09.016)
* **Local PDF:** [Macario Polo, Mario Piattini (2009) *Mutation testing: practical aspects and cost analysis*](documents/Mutation%20testing%20practical%20aspects%20and%20cost%20analysis%20\(2009\).pdf)
* **External:** [W. Langdon, M. Harman, Yue Jia (2009) *Multi Objective Higher Order Mutation Testing with Genetic Programming*](https://doi.org/10.1109/taicpart.2009.18)
* **External:** [Robert M. Hierons, Mercedes G. Merayo (2009) *Mutation testing from probabilistic and stochastic finite state machines*](https://doi.org/10.1016/j.jss.2009.06.030)
* **External:** [Yue Jia, Mark Harman (2008) *Constructing Subtle Faults Using Higher Order Mutation Testing*](https://doi.org/10.1109/scam.2008.36)
* **External:** [Yue Jia, Mark Harman (2008) *MILU: A Customizable, Runtime-Optimized Higher Order Mutation Testing Tool for the Full C Language*](https://doi.org/10.1109/taic-part.2008.18)
* **External:** [Robert M. Hierons, Mercedes G. Merayo (2007) *Mutation testing from probabilistic finite state machines*](https://doi.org/10.1109/taic.part.2007.20)
* **Local PDF:** [Jeff Offutt, Paul Ammann, Lisa (Ling) Liu (2006) *Mutation Testing implements Grammar-Based Testing*](documents/Mutation%20Testing%20implements%20Grammar-Based%20Testing%20\(2006\).pdf)
* **External:** [Auri Marcelo Rizzo Vincenzi, Adenilso Simão, Márcio Eduardo Delamaro, J. C. Maldonado (2006) *Muta-Pro: Towards the definition of a mutation testing process*](https://doi.org/10.1007/bf03192394)
* **External:** [Ying Jiang, Shan-Shan Hou, Jinhui Shan, Lu Zhang, Bing Xie (2005) *Contract-based mutation for testing components*](https://doi.org/10.1109/icsm.2005.36)
* **External:** [A.J. Offutt, Jie Pan (2002) *Detecting equivalent mutants and the feasible path problem*](https://doi.org/10.1109/cmpass.1996.507890)
* **External:** [Auri Marcelo Rizzo Vincenzi, José Carlos Maldonado, Ellen Francine Barbosa, Márcio Eduardo Delamaro (2001) *Unit and integration testing strategies for C programs using mutation*](https://doi.org/10.1002/stvr.242)
* **External:** [Auri Marcelo Rizzo Vincenzi, José Carlos Maldonado, Ellen Francine Barbosa, Márcio Eduardo Delamaro (2001) *Unit and Integration Testing Strategies for C Programs Using Mutation-Based Criteria*](https://doi.org/10.1007/978-1-4757-5939-6_8)
* **External:** [Phyllis G. Frankl, Stewart N. Weiss, Cang Hu (1997) *All-uses vs mutation testing: An experimental comparison of effectiveness*](https://doi.org/10.1016/s0164-1212\(96\)00154-9)
* **External:** [A. Jefferson Offutt, Jie Pan (1997) *Automatically detecting equivalent mutants and infeasible paths*](https://doi.org/10.1002/\(sici\)1099-1689\(199709\)7:3<165::aid-stvr143>3.0.co;2-u)
* **External:** [A. Jefferson Offutt, Ammei Lee, Gregg Rothermel, Roland H. Untch, Christian Zapf (1996) *An Experimental Determination of Sufficient Mutant Operators*](https://doi.org/10.1145/227607.227610)
* **External:** [W.Eric Wong, Aditya P. Mathur (1995) *Reducing the cost of mutation testing: An empirical study*](https://doi.org/10.1016/0164-1212\(94\)00098-0)
* **External:** [A. Jefferson Offutt, Stephen D. Lee (1994) *An empirical evaluation of weak mutation*](https://doi.org/10.1109/32.286422)
* **External:** [A. Jefferson Offutt, W. Michael Craft (1994) *Using compiler optimization techniques to detect equivalent mutants*](https://doi.org/10.1002/stvr.4370040303)
* **External:** [Roland H. Untch, A. Jefferson Offutt, Mary Jean Harrold (1993) *Mutation Analysis Using Mutant Schemata*](https://doi.org/10.1145/154183.154265)
* **External:** [Martin R. Woodward (1993) *Errors in algebraic specifications and an experimental mutation testing tool*](https://doi.org/10.1049/sej.1993.0027)
* **External:** [A. Jefferson Offutt (1992) *Investigations of the Software Testing Coupling Effect*](https://doi.org/10.1145/146637.146610)
* **Local PDF:** [Robert Geist, Jeff Offutt (1992) *Estimation and Enhancement of Real-Time Software Reliability through Mutation Analysis*](documents/Estimation%20and%20Enhancement%20of%20Real-Time%20Software%20Reliability%20through%20Mutation%20Analysis%20\(1992\).pdf)
* **External:** [I. M. M. Duncan, D. J. Robson (1990) *Ordered mutation testing*](https://doi.org/10.1145/382296.382699)
* **External:** [W.E. Howden (1982) *Weak Mutation Testing and Completeness of Test Sets*](https://doi.org/10.1109/tse.1982.235571)
* **External:** [Timothy A. Budd, Richard A. DeMillo, Richard J. Lipton, Frederick G. Sayward (1980) *Theoretical and Empirical Studies on Using Program Mutation to Test the Functional Correctness of Programs*](https://doi.org/10.1145/567446.567468)
* **External:** [Richard A. DeMillo, Richard J. Lipton, Frederick G. Sayward (1978) *Hints on Test Data Selection: Help for the Practicing Programmer*](https://doi.org/10.1109/C-M.1978.218136)

### Course material

* [Gordon Fraser (2010) *Mutation Testing* — university course slides](documents/Mutation%20Testing%20\(2010\).pdf)

## Blogs/Posts

* [Who Mutates the Mutator? (2026) • Aleksei Gagarin (Testo)](https://php-testo.github.io/blog/self-mutation)
* [Infection + Testo (2026) • Aleksei Gagarin (Testo)](https://php-testo.github.io/blog/infection-debut)
* [Mutation Testing (2026) • Aleksei Gagarin (Testo)](https://php-testo.github.io/docs/theory/mutation-testing)
* [Path Coverage or Mutation Testing? (2025) • Sebastian Bergmann](https://phpunit.expert/articles/path-coverage-or-mutation-testing.html)
* [LLMs Are the Key to Mutation Testing and Better Compliance (2025) • Mark Harman (Meta)](https://engineering.fb.com/2025/09/30/security/llms-are-the-key-to-mutation-testing-and-better-compliance/)
* [Revolutionizing software testing: Introducing LLM-powered bug catchers (2025) • Christopher Foster, Abhishek Gulati, Mark Harman, Inna Harper, Ke Mao, Jillian Ritchey, Hervé Robert, Shubho Sengupta (Meta)](https://engineering.fb.com/2025/02/05/security/revolutionizing-software-testing-llm-powered-bug-catchers-meta-ach/)
* [The Power of Mutation Testing (2024) • The Green Report](https://www.thegreenreport.blog/articles/the-power-of-mutation-testing/the-power-of-mutation-testing.html)
* [Enhancing Test Effectiveness with Mutation Testing (2024) • João Coelho](https://medium.com/@joaovitorcoelho10/enhancing-test-effectiveness-with-mutation-testing-6a714c1dfd01)
* [Solidity Mutation Testing (2023) • RareSkills](https://rareskills.io/post/solidity-mutation-testing)
* [Mutation Testing Google Blog Entry (2021) • Goran Petrovic (Google)](https://testing.googleblog.com/2021/04/mutation-testing.html)
* [Test Your Tests Are Testing (2018) • Gert de Pagter](https://backendtea.com/post/test-your-tests-are-testing/)
* [A note on Mutation Operators (2017) • Markus Schirp](https://gist.github.com/AlexDenisov/feb0b5ab7c0648441b492a462b0f307f)
* [Relevant mutants (2024) • Manuel Rivero](https://codesai.com/posts/2024/07/relevant-mutants)
* [I built a single-compile mutation testing lib for Kotlin which runs inside your normal test suite (2026) • Andreas Schnapp](https://dev.to/5n4p_/i-built-a-single-compile-mutation-testing-lib-for-kotlin-which-runs-inside-your-normal-test-suite-4253)

## Videos

* [Rider Webinar 2023: How To Test C# Unit Tests With Mutation Testing • Stefan Pölz](https://www.youtube.com/watch?v=9BoKyeZapLs)
* [GOTO 2019 • Making Mutants Work for You • Henry Coles](https://www.youtube.com/watch?v=LoFJajoJQ2g\&feature=youtu.be)
* [Test Automation Research for Industry 2019: Mutation Testing, Opportunities and Pitfalls • Ali Parsai](https://www.youtube.com/watch?v=oebxX3COmtg)
* [PHPDeveloperDay 2018: Mutation Testing • Théo Fidry](https://www.youtube.com/watch?v=dlVASJ-MbUE\&list=PLW4GAs3yDy3IqKoRGGLJY5gG74SnLOQRH)
* [RailsConf 2017: How to Write Better Code Using Mutation Testing • John Backus](https://www.youtube.com/watch?v=uB7m9T7ymn8)
* [FOSDEM 2017: Mutation Testing: Leaving the Stone Age • Alex Denisov](https://www.youtube.com/watch?v=YEgiyiICkpQ)
* [Voxxed Athens 2017: Mutation Testing to the Rescue of Your Tests • Nicolas Fränkel](https://www.youtube.com/watch?v=E4UuxVWYCVQ)
* [Jfokus 2016: From JUnit to Mutation Testing • Sven Ruppert](https://www.youtube.com/watch?v=9yG1c9Crnbk)
* [GOTO 2015: Mutation Testing in Python • Austin Bingham](https://www.youtube.com/watch?v=jwB3Nn4hR1o)

## Conference presentations

* [Speaker Deck 2026: Would Your Tests Catch This Bug? A Mutation Testing Story • Szymon Fiedler](https://speakerdeck.com/szymonfiedler/would-your-tests-catch-this-bug-a-mutation-testing-story)
* [RubyConf 2024: The Mutation Game — Cracking the Enigma of Mutation Testing • Tyler Lemburg](https://www.youtube.com/watch?v=WqrL5w0WP0o)
* [NDC TechTown 2024: Mutation Testing in Python with Cosmic Ray • Austin Bingham](https://www.youtube.com/watch?v=HBqhjLaZejA)
* [PHP UK Conference 2024: The Absolute Beginner’s Guide to Mutation Testing • Neal Brooks](https://www.youtube.com/watch?v=h1fIXGb06h8)
* [ICCQ 2023: Mutant Selection Strategies in Mutation Testing • Rowland Pitts](https://www.youtube.com/watch?v=86TPTFavdFU)
* [Build Stuff 2023: Kill All Mutants! Intro to Mutation Testing • Dave Aronson](https://www.youtube.com/watch?v=pJyuQXo5Uyo)
* [ACCU 2022: Kill All Mutants! Intro to Mutation Testing • Dave Aronson](https://www.youtube.com/watch?v=u78zWfkCZ1Q)
* [Code BEAM Europe 2022: Kill All Mutants! Intro to Mutation Testing • Dave Aronson](https://www.youtube.com/watch?v=30ydZKPtVn4)
* [ICCQ 2022: Quasi-Dominators and Random Selection in Mutation Testing • Rowland Pitts](https://www.youtube.com/watch?v=XDXKAs6s8Eo)
* [Devoxx Poland 2021: Mutation Testing — Too Good to Be True? • Piotr Kubowicz](https://www.youtube.com/watch?v=hxFMqyn4U5A)
* [Laracon EU 2021: Mutation Testing with PHP • Jeroen Groenendijk](https://www.youtube.com/watch?v=OukNLda4TxA)
* [PHPKonf 2021: Mutation Testing in PHP • Maks Rafałko](https://www.youtube.com/watch?v=aDdXTY372Vo)
* [JSConf Hawaii 2020: Kill All Mutants! Introduction to Mutation Testing • Dave Aronson](https://www.youtube.com/watch?v=yNMBOj7JUPs)
* [LLVM Developers’ Meeting 2020: LLVM-Based Mutation Testing for C and C++ • Alex Denisov](https://www.youtube.com/watch?v=DfoS9kdTWmI)
* [MSR 2020: Mutation Testing Meets Software Analytics — A Hands-On Tutorial](https://www.youtube.com/watch?v=QY6T6znfm9Y)
* [NDC 2020: Testing the Tests — Mutation Testing for C++ • Seph De Busser](https://www.youtube.com/watch?v=M-5_M8qZXaE)
* [PHP Barcelona 2020: Mutation Testing — Better Code by Making Bugs • Théo Fidry](https://www.youtube.com/watch?v=GRB0sTweUVY)
* [PHP North East 2020: Mutation Testing with Infection](https://www.youtube.com/watch?v=E1xQXaXTjpQ)
* [Speaker Deck 2020: Getting Started with Mutation Testing • Denis Brumann](https://speakerdeck.com/dbrumann/getting-started-with-mutation-testing)
* [Symfony User Group 2020: What’s New in Symfony 5.1 and Getting Started with Mutation Testing](https://www.youtube.com/watch?v=lFY1td8kzEw)
* [DevConf Johannesburg 2019: Testing Your Tests’ Quality — Introduction to Mutation Testing • Felix Wu](https://www.youtube.com/watch?v=WTR8k6oPTyY)
* [fwdays 2019: Mutation Testing in PHP • Maks Rafałko](https://www.youtube.com/watch?v=8t-gCS3wbEE)
* [RubyConf 2019: Kill All Mutants! Intro to Mutation Testing • Dave Aronson](https://www.youtube.com/watch?v=9GId6mFL0_c)
* [Speaker Deck 2019: Mutation Testing at Pixels Camp • Pedro Rijo](https://speakerdeck.com/pedrorijo91/mutation-testing-pixels-camp-2019)
* [Speaker Deck 2019: Mutation Testing in Elixir • Daniel Serrano](https://speakerdeck.com/dnlserrano/mutation-testing-in-elixir)
* [Speaker Deck 2019: Mutation Testing with Infection • DragonBe](https://speakerdeck.com/dragonbe/mutation-testing-with-infection)
* [Speaker Deck 2018: Mutation Testing at PHPDeveloperDay • Théo Fidry](https://speakerdeck.com/theofidry/mutation-testing-phpdeveloperday)
* [Symfony User Group Osnabrück: Mutation Testing with Symfony](https://www.youtube.com/watch?v=CUzjQ-BOd6w)
* [Speaker Deck 2014: Mutation Testing with Mutant • Erik Berlin](https://speakerdeck.com/sferik/mutation-testing-with-mutant)

## Conferences

* International Workshop on Mutation Analysis
  * [MUTATION 2018, The 13th International Workshop on Mutation Analysis](https://mutation-workshop.github.io)

## Examples and practical resources

* [atodorov/mutation-testing-in-patterns](https://github.com/atodorov/mutation-testing-in-patterns) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2018-12-14
  * Practical examples of software and testing patterns related to mutation testing [Mutation Testing in Patterns](http://mutation-testing-patterns.rtfd.io)

## Tutorials

* [Introduction to Mutation Testing with PIT (Java)](https://github.com/sualeh/introduction-to-mutation-testing) ⭐ 23 | 🐛 30 | 🌐 C# | 📅 2026-09-01

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-05._
