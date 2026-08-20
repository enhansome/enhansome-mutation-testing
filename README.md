# Awesome Mutation testing with stars

Mutation testing is the practice of making better code by introducing bugs. As of now this repository is used to keep track of the current mutation testing tools developed and related resources. Its contents and purpose may however evolve depending on the community.

[Discord Invite](https://discord.com/invite/k5JBWU2)

### Contents

* [Existing libraries](#existing-libraries)
* [Abandoned libraries](abandoned.md)
* [Visualization Tool](#visualization-tool)
* [Papers](#papers)
* [Blogs/Posts/Videos](#blogspostsvideos)
* [Conferences](#conferences)
* [Friendly resources](#friendly-resources)
* [Tutorials](#tutorials)

### Existing libraries

* Alloy
  * [MuAlloy](https://github.com/kaiyuanw/MuAlloy) ⭐ 8 | 🐛 0 | 🌐 Alloy | 📅 2018-06-14
    * [MuAlloy papers](https://github.com/kaiyuanw/MuAlloy#publications) ⭐ 8 | 🐛 0 | 🌐 Alloy | 📅 2018-06-14
* C/C++
  * [mull-project/mull](https://github.com/mull-project/mull) ⭐ 831 | 🐛 23 | 🌐 C++ | 📅 2026-07-31
  * [mutate\_cpp](https://github.com/nlohmann/mutate_cpp) ⭐ 193 | 🐛 10 | 🌐 CSS | 📅 2024-06-30
  * [Dextool Mutate](https://github.com/joakim-brannstrom/dextool/tree/master/plugin/mutate) ⭐ 111 | 🐛 16 | 🌐 D | 📅 2026-04-20
  * [MART](https://github.com/thierry-tct/mart) ⭐ 25 | 🐛 0 | 🌐 C++ | 📅 2022-07-25
  * [Frama-C plugin](https://github.com/gpetiot/Frama-C-Mutation/) ⚠️ Archived
  * [MUSIC](https://github.com/swtv-kaist/MUSIC) ⭐ 18 | 🐛 3 | 🌐 C++ | 📅 2026-04-24
    * [MUSIC: Mutation Analysis Tool with High Configurability and Extensibility](http://swtv.kaist.ac.kr/publications/music-mutation18.pdf)
  * [SRCIROR](https://github.com/TestingResearchIllinois/srciror) ⭐ 13 | 🐛 2 | 🌐 C++ | 📅 2018-09-06 - A mutation tool for source and IR
    * [SRCIROR: A Toolset for Mutation Testing of C Source Code and LLVM Intermediate Representation](http://mir.cs.illinois.edu/farah/publications/ase18_srciror.pdf)
  * [accmut](https://github.com/wangbo15/accmut) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2018-01-25
    * [Faster mutation analysis via equivalence modulo states](http://sei.pku.edu.cn/%7Exiongyf04/papers/ISSTA17.pdf)
  * [llvm-mutate](https://eschulte.github.io/llvm-mutate/)
  * [MuCPP](https://neptuno.uca.es/redmine/projects/mucpp-mutation-tool/wiki)
    * [Assessment of Class Mutation Operators for C++ with the MuCPP Mutation System](https://pdfs.semanticscholar.org/05d5/2ba68ed4ba8505cc92e4f27ad68c1b944842.pdf)
* C#
  * [stryker-mutator/stryker-net](https://github.com/stryker-mutator/stryker-net) ⭐ 2,059 | 🐛 188 | 🌐 C# | 📅 2026-08-20
  * [Testura.Mutation](https://github.com/Testura/Testura.Mutation) ⭐ 105 | 🐛 23 | 🌐 C# | 📅 2022-12-08
  * [ComparetheMarket/fettle](https://github.com/ComparetheMarket/fettle) ⚠️ Archived
  * [Faultify](https://github.com/Faultify/Faultify) ⭐ 21 | 🐛 8 | 🌐 C# | 📅 2021-12-06
* Clojure
  * [mutant](https://github.com/jstepien/mutant) ⚠️ Archived
* Crystal
  * [crytic](https://github.com/hanneskaeufler/crytic) ⭐ 70 | 🐛 5 | 🌐 Crystal | 📅 2025-11-20
* Elixir
  * [JordiPolo/mutation](https://github.com/JordiPolo/mutation) ⭐ 21 | 🐛 0 | 🌐 Elixir | 📅 2017-01-11
* Erlang
  * [parsifal-47/muterl](https://github.com/parsifal-47/muterl) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2022-11-04
* Go
  * [go-gremlins](https://github.com/go-gremlins/gremlins) ⭐ 391 | 🐛 43 | 🌐 Go | 📅 2026-06-26
  * [Ooze](https://github.com/gtramontina/ooze) ⭐ 284 | 🐛 5 | 🌐 Go | 📅 2026-08-19
  * [jonbaldie/go-mutesting](https://github.com/jonbaldie/go-mutesting) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2026-08-06
* Haskell
  * [rudymatela/fitspec](https://github.com/rudymatela/fitspec) ⭐ 78 | 🐛 0 | 🌐 Haskell | 📅 2025-01-30
  * [mucheck](https://hackage.haskell.org/package/MuCheck)
* Java/JVM
  * [hcoles/pitest](https://github.com/hcoles/pitest) ⭐ 1,847 | 🐛 320 | 🌐 Java | 📅 2026-08-14
    \* [PIT : A Practical Mutation Testing Tool for Java (Demo)](https://dl.acm.org/citation.cfm?id=2948707)
    \* [An Experimental Evaluation of PIT’s Mutation Operators](http://www.diva-portal.org/smash/get/diva2:1161760/FULLTEXT01.pdf)
    * [Introduction to Mutation Testing](https://blog.frankel.ch/introduction-to-mutation-testing/)
    * [Faster Mutation Testing (in Java)](https://blog.frankel.ch/faster-mutation-testing/)
      * [Voxxed Athens 2017 :: Mutation Testing to the rescue of your Tests • Nicolas Fränkel](https://www.youtube.com/watch?v=E4UuxVWYCVQ)
  * [aliparsai/LittleDarwin](https://github.com/aliparsai/LittleDarwin) ⭐ 24 | 🐛 11 | 🌐 Python | 📅 2026-05-31
    * [LittleDarwin: a Feature-Rich and Extensible Mutation Testing Framework for Large and Complex Java Systems](https://www.parsai.net/files/research/LittleDarwin%20a%20Feature-Rich%20and%20Extensible%20Mutation%20Testing%20Framework%20for%20Large%20and%20Complex%20Java%20Systems%20\(pre-print\).pdf)
  * [metamutator](https://github.com/SpoonLabs/metamutator) ⭐ 19 | 🐛 1 | 🌐 Java | 📅 2022-08-13
  * [Major](http://mutation-testing.org)
    * [Publications related to the Major mutation framework](http://mutation-testing.org/publ/)
* JavaScript
  * [stryker-mutator/stryker](https://github.com/stryker-mutator/stryker) ⭐ 3,028 | 🐛 89 | 🌐 TypeScript | 📅 2026-08-15
* Kotlin
  * [mutant-kraken](https://github.com/JosueMolinaMorales/mutant-kraken) ⭐ 29 | 🐛 1 | 🌐 Rust | 📅 2025-11-06
  * [mutflow](https://github.com/anschnapp/mutflow) ⭐ 23 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-11
* PHP
  * [infection/infection](https://github.com/infection)
  * [PEST PHP](https://pestphp.com/docs/mutation-testing)
* Python
  * [boxed/mutmut](https://github.com/boxed/mutmut) ⭐ 1,395 | 🐛 47 | 🌐 Python | 📅 2026-08-17
  * [sixty-north/cosmic-ray](https://github.com/sixty-north/cosmic-ray) ⭐ 651 | 🐛 52 | 🌐 Python | 📅 2026-08-09
* R
  * [jakubsob/muttest](https://github.com/jakubsob/muttest) ⭐ 26 | 🐛 2 | 🌐 R | 📅 2026-07-21
  * [PRL-PRG/mutator](https://github.com/PRL-PRG/mutator) ⭐ 9 | 🐛 2 | 🌐 R | 📅 2026-08-04
* Ruby
  * [mbj/mutant](https://github.com/mbj/mutant) ⭐ 2,182 | 🐛 127 | 🌐 Ruby | 📅 2026-08-03
    * [Kill all the mutants - a deep dive into mutation testing and how the Mutant gem works](https://troessner.svbtle.com/kill-all-the-mutants-a-deep-dive-into-mutation-testing-and-how-the-mutant-gem-works)
  * [backus/mutest](https://github.com/backus/mutest) ⚠️ Archived
* Rust
  * [sourcefrog/cargo-mutants](https://github.com/sourcefrog/cargo-mutants) ⭐ 1,261 | 🐛 99 | 🌐 Rust | 📅 2026-08-17
  * [llogiq/mutagen](https://github.com/llogiq/mutagen) ⭐ 642 | 🐛 39 | 🌐 Rust | 📅 2023-05-29
* Scala
  * [sugakandrey/scalamu](https://github.com/sugakandrey/scalamu) ⭐ 44 | 🐛 4 | 🌐 Scala | 📅 2017-12-11
  * [stryker4s](https://stryker-mutator.io/stryker4s/)
* Smalltalk
  * [pavel-krivanek/mutalk](https://github.com/pavel-krivanek/mutalk) ⭐ 25 | 🐛 7 | 🌐 Smalltalk | 📅 2026-04-13
* Simulink
  * [MUT4SLX](https://github.com/haliliceylan/MUT4SLX) ⭐ 6 | 🐛 0 | 🌐 HTML | 📅 2025-04-29 - An open-source, model-based mutation testing tool for Simulink and Stateflow (MATLAB) models. Applies principles of shift-left testing.
    * [Reproduction Package](https://github.com/haliliceylan/MUT4SLX/blob/main/Reproduction-Package-ASE-2023.md) ⭐ 6 | 🐛 0 | 🌐 HTML | 📅 2025-04-29
    * [MUT4SLX: Fast mutant generation for simulink](https://ieeexplore.ieee.org/abstract/document/10298490)
    * [MUT4SLX: Extensions for Mutation Testing of Stateflow Models](https://ieeexplore.ieee.org/abstract/document/10621727)
* Solidity / Smart Contracts
  * [Certora/gambit](https://github.com/Certora/gambit) ⭐ 208 | 🐛 11 | 🌐 Rust | 📅 2026-08-12
  * [JoranHonig/vertigo](https://github.com/JoranHonig/vertigo) ⭐ 207 | 🐛 17 | 🌐 Python | 📅 2023-11-21
  * [RareSkills/vertigo-rs](https://github.com/RareSkills/vertigo-rs) ⭐ 128 | 🐛 6 | 🌐 Python | 📅 2024-09-05
* Swift
  * [muter-mutation-testing/muter](https://github.com/muter-mutation-testing/muter) ⭐ 558 | 🐛 36 | 🌐 Swift | 📅 2026-07-21
* OCaml
  * [mutaml](https://github.com/jmid/mutaml) ⭐ 75 | 🐛 12 | 🌐 OCaml | 📅 2025-11-24
* Lean
  * [Mutate.lean](https://github.com/jubnzv/Mutate.lean) ⭐ 3 | 🐛 0 | 🌐 Lean | 📅 2026-06-24
* Other
  * [codeintegrity-ai/mutahunter](https://github.com/codeintegrity-ai/mutahunter) ⭐ 299 | 🐛 2 | 🌐 Python | 📅 2025-04-17
  * [agroce/universalmutator](https://github.com/agroce/universalmutator) ⭐ 162 | 🐛 6 | 🌐 Python | 📅 2026-05-20
  * [squaresLab/boggart](https://github.com/squaresLab/boggart) ⭐ 2 | 🐛 9 | 🌐 Python | 📅 2019-01-09
  * [bough](https://github.com/CodeEnPlace/bough) ⭐ 1 | 🐛 33 | 🌐 Rust | 📅 2026-04-10

### Visualization Tool

* [sqrlab/VisMAn](https://github.com/sqrlab/VisMAn) ⭐ 6 | 🐛 0 | 🌐 Java | 📅 2013-08-14

### Publications

* [Hervé Robert, Shubho Sengupta (2025) *Mutation-Guided LLM-based Test Generation at Meta*](documents/Mutation-Guided%20LLM-based%20Test%20Generation%20at%20Meta%20\(2025\).pdf)
* [Jeongju Sohn, Ezekiel Soremekun, Michail Papadakis (2025) *Latent Mutants: A large-scale study on the Interplay between mutation testing and software evolution*](documents/Latent%20Mutants%20A%20large%20scale%20study%20on%20the%20Interplay%20between%20mutation%20testing%20and%20software%20evolution%20\(2025\).pdf)
* [Dolores Miao, Ignacio Laguna, Giorgis Georgakoudis, Konstantinos Parasyris, Cindy Rubio-González (2024) *An automated OpenMP mutation testing framework for performance optimization*](documents/An%20automated%20OpenMP%20mutation%20testing%20framework%20for%20performance%20optimization%20\(2024\).pdf)
* [Enzo Nicourt, Benjamin Kushigian, Chandrakana Nandi, Yliès Falcone (2024) *Using Mutation Testing To Improve and Minimize Test Suites for Smart Contracts*](documents/Using%20Mutation%20Testing%20To%20Improve%20and%20Minimize%20Test%20Suites%20for%20Smart%20Contracts.pdf)
* [Pedro Delgado-Pérez, Ana B. Sánchez, Sergio Segura, Inmaculada Medina-Bulo (2022) *Mutation testing in the wild: findings from GitHub*](documents/Mutation%20testing%20in%20the%20wild:%20findings%20from%20GitHub%20\(2022\).pdf)
* [Goran Petrovic, Marko Ivankovic, Gordon Fraser, René Just (2021) *Practical Mutation Testing at Scale: A view from Google*](documents/Practical%20Mutation%20Testing%20at%20Scale%20A%20view%20from%20Google%20\(2021\).pdf)
* [Goran Petrovic, Marko Ivankovic, Gordon Fraser, René Just (2021) *Does mutation testing improve testing practices?*](documents/Does%20mutation%20testing%20improve%20testing%20practices%3F%20\(2021\).pdf)
* [Giovani Guizzo, Federica Sarro, Jens Krinke, Silvia Regina Vergilio (2021) *Sentinel: A Hyper-Heuristic for the Generation of Mutant Reduction Strategies*](documents/Sentinel:%20A%20Hyper-Heuristic%20for%20the%20Generation%20of%20Mutant%20Reduction%20Strategies%20\(2021\).pdf)
* [Y. Ivanovaa, A. Khritankova (2020) *RegularMutator: A Mutation Testing Tool for Solidity Smart Contracts*](documents/RegularMutator:%20A%20Mutation%20Testing%20Tool%20for%20Solidity%20Smart%20Contracts%20\(2020\).pdf)
* [Alessandro Viola Pizzoletoa, Fabiano Cutigi Ferraria, Jeff Offuttb, Leo Fernandesc, Marcio Ribeirod (2019) *A Systematic Literature Review of Techniques and Metrics to Reduce the Cost of Mutation Testing*](documents/A%20Systematic%20Literature%20Review%20of%20Techniques%20and%20Metrics%20to%20Reduce%20the%20Cost%20of%20Mutation%20Testing%20\(2019\).pdf)
* [August Shi, Jonathan Bell, Darko Marinov (2019) *Mitigating the Effects of Flaky Tests on Mutation Testing*](documents/Mitigating%20the%20Effects%20of%20Flaky%20Tests%20on%20Mutation%20Testing%20\(2019\).pdf)
* [Esther Guerra, Jesús Sánchez Cuadrado, Juan de Lara (2019) *Towards effective mutation testing for ATL*](documents/Towards%20effective%20mutation%20testing%20for%20ATL%20\(2019\).pdf)
* [Lin Deng, Jeff Offutt (2018) *Reducing the Cost of Android Mutation Testing*](documents/Reducing%20the%20Cost%20of%20Android%20Mutation%20Testing%20\(2018\).pdf)
* [Goran Petrovic, Marko Ivankovic (2018) *State of Mutation Testing at Google*](documents/State%20of%20Mutation%20Testing%20at%20Google%20\(2018\).pdf)
* [Goran Petrovic, Marko Ivankovic, Bob Kurtz, Paul Ammann, René Just (2018) *An Industrial Application of Mutation Testing/ Lessons, Challenges, and Research Directions*](documents/An%20Industrial%20Application%20of%20Mutation%20Testing%20Lessons,%20Challenges,%20and%20Research%20Directions%20\(2018\).pdf)
* [Sten Vercammen, Serge Demeyer, Mohammad Ghafari, Markus Borg (2018) *Goal-Oriented Mutation Testing with Focal Methods*](documents/Goal-Oriented%20Mutation%20Testing%20with%20Focal%20Methods%20\(2018\).pdf)
* [Qianqian Zhu, Annibale Panichella, Andy Zaidman (2018) *A Systematic Literature Review of How Mutation Testing Supports Quality Assurance Processes*](documents/A%20Systematic%20Literature%20Review%20of%20Techniques%20and%20Metrics%20to%20Reduce%20the%20Cost%20of%20Mutation%20Testing%20\(2019\).pdf)
* [Lingchao Chen, Lingming Zhang (2018) *Speeding up Mutation Testing via Regression Test Selection: An Extensive Study*](documents/Speeding-Up%20Mutation%20Testing%20via%20Data%20Compression%20and%20State%20Infection%20\(2017\).pdf)
* [Mike Papadakisa, Marinos Kintisa, Jie Zhangc, Yue Jiab, Yves Le Traona, Mark Harmanb (2017) *Mutation Testing Advances: An Analysis and Survey*](documents/Mutation%20Testing%20Advances:%20An%20Analysis%20and%20Survey%20\(2017\).pdf)
* [Pablo C. Cañizares, Alberto Núñez, Juan de Lara (2017) *OUTRIDER: Optimizing the mUtation Testing pRocess In Distributed EnviRonments*](documents/OUTRIDER:%20Optimizing%20the%20mUtation%20Testing%20pRocess%20In%20Distributed%20EnviRonments%20\(2017\).pdf)
* [Qianqian Zhu, Annibale Panichella, Andy Zaidman (2017) *Speeding-Up Mutation Testing via Data Compression and State Infection*](documents/Speeding-Up%20Mutation%20Testing%20via%20Data%20Compression%20and%20State%20Infection%20\(2017\).pdf)
* [Jie Zhang, Ziyi Wang, Lingming Zhang, Dan Hao, Lei Zang, Shiyang Cheng, Lu Zhang (2016) *Predictive Mutation Testing*](documents/Predictive%20Mutation%20Testing%20\(2016\).pdf)
* [Marinos Kintis (2016) *Effective Methods to Tackle the Equivalent Mutant Problem when Testing Software with Mutation*](documents/Effective%20Methods%20to%20Tackle%20the%20Equivalent%20Mutant%20Problem%20when%20Testing%20Software%20with%20Mutation%20\(2016\).pdf)
* [René Just, Darioush Jalali, Laura Inozemtseva, Michael D. Ernst, Reid Holmes, Gordon Fraser (2014) *Are Mutants a Valid Substitute for Real Faults in Software Testing?*](documents/Are%20Mutants%20a%20Valid%20Substitute%20for%20Real%20Faults%20in%20Software%20Testing%3F%20\(2014\).pdf)
* [Lorena Gutiérrez-Madroñal, J. Domínguez-Jiménez, I. Medina-Bulo (2014) *Mutation Testing: Guideline and Mutation Operator Classification*](documents/Mutation%20Testing%20Guideline%20and%20Mutation%20Operator%20Classification%20\(2014\).pdf)
* [L. Madeyski, W. Orzeszyna, R. Torkar, M. Józala (2014) *Overcoming the Equivalent Mutant Problem/ A Systematic Literature Review and a Comparative Experiment of Second Order Mutation*](documents/Overcoming%20the%20Equivalent%20Mutant%20Problem%20A%20Systematic%20Literature%20Review%20and%20a%20Comparative%20Experiment%20of%20Second%20Order%20Mutation%20\(2014\).pdf)
* [Lingming Zhang, Darko Marinov, Sarfraz Khurshid (2013) *Faster Mutation Testing Inspired by Test Prioritization and Reduction*](documents/Faster%20Mutation%20Testing%20Inspired%20by%20Test%20Prioritization%20and%20Reduction%20\(2013\).pdf)
* [Bouchaib Falah, Bouriat Salwa (2013) *Effectiveness of Mutation Testing Techniques: Reducing Mutation Cost*](documents/Effectiveness%20of%20Mutation%20Testing%20Techniques%20Reducing%20Mutation%20Cost%20\(2013\).pdf)
* [Quang Vu Nguyen, Lech Madeyski (2013) *Problems of Mutation Testing and Higher Order Mutation Testing*](documents/Problems%20of%20Mutation%20Testing%20and%20Higher%20Order%20Mutation%20Testing%20\(2013\).pdf)
* [Lingming Zhang, Milos Gligoric, Darko Marinov, Sarfraz Khurshid (2013) *Operator-Based and Random Mutant Selection: Better Together*](documents/Operator-Based%20and%20Random%20Mutant%20Selection%20Better%20Together%20\(2013\).pdf)
* [Kevin Jalbert, Jeremy S. Bradbury (2012) *Predicting Mutation Scores using Source Code and Test Suite Metrics*](documents/Predicting%20Mutation%20Score%20Using%20Source%20Code%20and%20Test%20Suite%20Metrics%20\(2012\).pdf)
* [David Schuler (2011) *Assessing Test Quality*](documents/Assessing%20Test%20Quality%20\(2011\).pdf)
* [John A. Clarka, Haitao Danb, Robert M. Hieronsb (2011) *Semantic Mutation Testing*](documents/Semantic%20mutation%20testing%20\(2011\).pdf)
* [Yue Jia, Mark Harman (2010) *An Analysis and Survey of the Development of Mutation Testing*](documents/An%20Analysis%20and%20Survey%20of%20the%20Development%20of%20Mutation%20Testing%20\(2010\).pdf)
* [Gordon Fraser (2010) Mutation Testing (university course slides)](documents/Mutation%20Testing%20\(2010\).pdf)
* [Pedro Delgado-Pérez, Ana B. Sánchez, Sergio Segura, Inmaculada Medina-Bulo (2010) *Performance Mutation Testing*](documents/Performance%20Mutation%20Testing%20\(2010\).pdf)
* [Macario Polo, Mario Piattini (2009) *Mutation testing: practical aspects and cost analysis*](documents/Mutation%20testing%20practical%20aspects%20and%20cost%20analysis%20\(2009\).pdf)
* [Jeff Offutt, Paul Ammann, Lisa (Ling) Liu (2006) *Mutation Testing implements Grammar-Based Testing*](documents/Mutation%20Testing%20implements%20Grammar-Based%20Testing%20\(2006\).pdf)
* [Robert Geist, Jeff Offutt (1992) *Estimation and Enhancement of Real-Time Software Reliability through Mutation Analysis*](documents/Estimation%20and%20Enhancement%20of%20Real-Time%20Software%20Reliability%20through%20Mutation%20Analysis%20\(1992\).pdf)

### Blogs/Posts

* [LLMs Are the Key to Mutation Testing and Better Compliance (2025) • Mark Harman (Meta)](https://engineering.fb.com/2025/09/30/security/llms-are-the-key-to-mutation-testing-and-better-compliance/)
* [Revolutionizing software testing: Introducing LLM-powered bug catchers (2025) • Christopher Foster, Abhishek Gulati, Mark Harman, Inna Harper, Ke Mao, Jillian Ritchey, Hervé Robert, Shubho Sengupta (Meta)](https://engineering.fb.com/2025/02/05/security/revolutionizing-software-testing-llm-powered-bug-catchers-meta-ach/)
* [The Power of Mutation Testing (2024) • The Green Report](https://www.thegreenreport.blog/articles/the-power-of-mutation-testing/the-power-of-mutation-testing.html)
* [Enhancing Test Effectiveness with Mutation Testing (2024) • João Coelho](https://medium.com/@joaovitorcoelho10/enhancing-test-effectiveness-with-mutation-testing-6a714c1dfd01)
* [Solidity Mutation Testing (2023) • RareSkills](https://rareskills.io/post/solidity-mutation-testing)
* [Mutation Testing Google Blog Entry (2021) • Goran Petrovic (Google)](https://testing.googleblog.com/2021/04/mutation-testing.html)
* [GOTO 2019 • Making Mutants Work for You • Henry Coles](https://www.youtube.com/watch?v=LoFJajoJQ2g\&feature=youtu.be)
* [Test Automation Research for Industry 2019: Mutation Testing, Opportunities and Pitfalls • Ali Parsai](https://www.youtube.com/watch?v=oebxX3COmtg)
* [PHPDeveloperDay 2018: Mutation Testing • Théo Fidry](https://www.youtube.com/watch?v=dlVASJ-MbUE\&list=PLW4GAs3yDy3IqKoRGGLJY5gG74SnLOQRH)
* [RailsConf 2017: How to Write Better Code Using Mutation Testing • John Backus](https://www.youtube.com/watch?v=uB7m9T7ymn8)
* [FOSDEM 2017: Mutation Testing: Leaving the Stone Age • Alex Denisov](https://www.youtube.com/watch?v=YEgiyiICkpQ)
* [A note on Mutation Operators (2017) • Markus Schirp](https://gist.github.com/AlexDenisov/feb0b5ab7c0648441b492a462b0f307f)
* [Jfokus 2016: From jUnit to Mutation-Testing • Sven Ruppert](https://www.youtube.com/watch?v=9yG1c9Crnbk)
* [GOTO 2015: Mutation Testing in Python • Austin Bingham](https://www.youtube.com/watch?v=jwB3Nn4hR1o)
* [Relevant mutants (2024) • Manuel Rivero](https://codesai.com/posts/2024/07/relevant-mutants)
* [I built a single-compile mutation testing lib for Kotlin which runs inside your normal test suite (2026) • Andreas Schnapp](https://dev.to/5n4p_/i-built-a-single-compile-mutation-testing-lib-for-kotlin-which-runs-inside-your-normal-test-suite-4253)

### Videos

* [Rider Webinar 2023: How To Test C# Unit Tests With Mutation Testing • Stefan Pölz](https://www.youtube.com/watch?v=9BoKyeZapLs)

### Conferences

* International Workshop on Mutation Analysis
  * [MUTATION 2018, The 13th International Workshop on Mutation Analysis](https://mutation-workshop.github.io)

### Friendly resources

* [atodorov/mutation-testing-in-patterns](https://github.com/atodorov/mutation-testing-in-patterns) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2018-12-14
  * Practical examples of software and testing patterns related to mutation testing [Mutation Testing in Patterns](http://mutation-testing-patterns.rtfd.io)

### Tutorials

* [Introduction to Mutation Testing with PIT (Java)](https://github.com/sualeh/introduction-to-mutation-testing) ⭐ 23 | 🐛 15 | 🌐 C# | 📅 2026-08-01

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-20._
