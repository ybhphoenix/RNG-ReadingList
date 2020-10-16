# RNG-ReadingList
This is a reading list for people who are interested in random number generators.

Now it is under the maintance from [Vladimir Rožić](https://www.esat.kuleuven.be/cosic/vladimir-rozic/ "Vladimir's Homepage") and [Bohan Yang](https://www.esat.kuleuven.be/cosic/965-2/ "Bohan's Homepage")


## READING LIST:

### TRNG designs:

[1] Oto Petura. Ugo Mureddu, Nathalie Bochard, Viktor Fischer, and Lilian Bossuet, _A survey of AIS-20/31 compliant TRNG cores suitable for FPGA devices._ 26th International Conference on Field Programmable Logic and Applications (FPL 2016).
http://ieeexplore.ieee.org/document/7577379/ 

[2] Abdelkarim Cherkaoui, Viktor Fischer, Laurent Fesquet and Alain Aubert, _A Very High Speed True Random Number Generator with Entropy Assessment_, Cryptographic Hardware and Embedded Systems (CHES 2013).
https://link.springer.com/content/pdf/10.1007%2F978-3-642-40349-1_11.pdf 

[3] Michal Varchola and Miloš Drutarovsky, _New High Entropy Element for FPGA Based True Random Number Generators,_  Cryptographic Hardware and Embedded Systems (CHES 2010).
https://link.springer.com/content/pdf/10.1007%2F978-3-642-15031-9_24.pdf 

[4] Berk Sunar, William J. Martin and Douglas R. Stinson, _A Provably Secure True Random Number Generator with Built-In Tolerance to Active Attacks,_ IEEE Transactions on Computers, vol. 56(1), 2007.
http://ieeexplore.ieee.org/abstract/document/4016501/ 

[5]  Florent Lozach, Molka Ben-Romdhane, Tarik Graba and Jean-Luc Danger, _FPGA Design of an Open-Loop True Random Number Generator,_  Euromicro Conference on Digital System Design (DSD 2013)
http://ieeexplore.ieee.org/document/6628334/ 

[6] Viktor Fischer, Miloš Drutarovsky, Martin Šimka and Nathalie Bochard, _High Performance True Random Number Generator in Altera Stratix FPLDs,_ 14th International Conference on Field Programmable Logic and Application (FPL 2004).
https://link.springer.com/content/pdf/10.1007%2F978-3-540-30117-2_57.pdf 

[7] Tim Guneysu, _True random number generation in block memories of reconfigurable devices,_ International Conference on Field-Programmable Technology, (FPT 2010).
http://ieeexplore.ieee.org/document/5681499/ 

[8] Jovan Golić, _New Methods for Digital Generation and Postprocessing of Random Data._ IEEE Transactions on Computers, vol. 55(10), 2006.
http://ieeexplore.ieee.org/document/1683753/ 

[9] Md. Tauhidur Rahman, Kan Xiao, Domenic Forte, Xuhei Zhang, Jerry Shi and Mohammad Tehranipoor, _TI-TRNG: Technology Independent True Random Number Generator,_ Design Automation Conference (DAC 2014).
https://dl.acm.org/citation.cfm?doid=2593069.2593236 

[10] B. Yang, V. Rožić, M. Grujić, N. Mentens, and I. Verbauwhede, _ES-TRNG: A High-throughput, Low-area True Random Number Generator based on Edge Sampling,_ IACR Transactions on Cryptographic Hardware and Embedded Systems (TCHES 2018)
https://tches.iacr.org/index.php/TCHES/article/view/7276

[11] S. Best, X. Xu, _An All-Digital True Random Number GeneratorBased on Chaotic Cellular Automata Topology,_ IEEE/ACM International Conference on Computer-Aided Design (ICCAD 2019)
https://ieeexplore.ieee.org/abstract/document/8942050

[12] G. Di Patrizio Stanchieri, A. De Marcellis, E. Palange, and M. Faccio, _A true random number generator architecture based on a reducednumber of FPGA primitives,_ International Journal of Electronics andCommunications  (2019)
https://www.sciencedirect.com/science/article/pii/S1434841118327080

[13] A. Peetermans, V. Rožić, and I. Verbauwhede, _A Highly-Portable True Random Number Generator Based on Coherent Sampling,_ International Conference on Field Programmable Logic and Applications (FPL 2019)
https://ieeexplore.ieee.org/abstract/document/8892076

### Attacks:

[14]Yang Cao, Vladimir Rožić, Bohan Yang, Josep Balasch and Ingrid Verbauwhede, _Exploring Active Manipulation Attacks on the TERO Random Number Generator,_ IEEE 59th International Midwest Symposium on Circuits and Systems (MWSCAS 2016).
https://www.esat.kuleuven.be/cosic/publications/article-2716.pdf 

[15]Yang Cao, _Securing Hardware Random Number Generators against Physical Attacks,_ Master Thesis, KU Leuven, 2016.
https://www.esat.kuleuven.be/cosic/publications/thesis-272.pdf 

[16] A. T. Markettos and S. W. Moore, _The Frequency Injection Attack on Ring-Oscillator-Based True Random Number Generators,_   Cryptographic Hardware and Embedded Systems (CHES 2009)
https://link.springer.com/content/pdf/10.1007%2F978-3-642-04138-9_23.pdf 

[17] P. Bayon, L. Bossuet, A. Aubert, V. Fischer, F. Poucheret, B. Robisson, and P. Maurine, _Contactless Electromagnetic Active Attack on Ring Oscillator Based True Random Number Generator,_ International Workshop on Constructive Side-Channel Analysis and Secure Design (COSADE 2012)
https://link.springer.com/content/pdf/10.1007%2F978-3-642-29912-4_12.pdf 

#### Remote fault attacks:

[18] D. Gnad, F. Oboril, and M. Tahoori, _Voltage drop-based fault attacks on FPGAs using valid,_ International Conference on Field Programmable Logic and Applications (FPL 2017)
https://ieeexplore.ieee.org/abstract/document/8056840

[19] D. Mahmoud, and M. Stojilovic, _Timing Violation Induced Faults in Multi-Tenant FPGAs,_ Design, Automation and Test in Europe Conference and Exhibition (DATE 2019)
https://ieeexplore.ieee.org/abstract/document/8715263

[20] D. Gnad, F. Oboril, S. Kiamehr, and M. Tahoori, _An Experimental Evaluation and Analysis of Transient Voltage Fluctuations in FPGAs,_ IEEE Transactions on Very Large Scale Integration (VLSI) Systems (2018)
https://ieeexplore.ieee.org/abstract/document/8410585

[21] F. Schellenberg, D. Gnad, A. Moradi, and M. Tahoori, _An inside job: Remote power analysis attacks on FPGAs,_ Design, Automation and Test in Europe Conference and Exhibition (DATE 2018)
https://ieeexplore.ieee.org/abstract/document/8342177

[22] J. Krautter, D. Gnad, and M. Tahoori, _FPGAhammer: Remote Voltage Fault Attacks on Shared FPGAs, suitable for DFA on AES,_ IACR Transactions on Cryptographic Hardware and Embedded Systems (TCHES 2018)
https://tches.iacr.org/index.php/TCHES/article/view/7268

#### Locking:

[23] U. Mureddu, N. Bochard, L. Bossuet, and V. Fischer, _Experimental Study of Locking Phenomena on Oscillating Rings Implemented in Logic Devices,_ IEEE Transactions on Circuits and Systems I: Regular Papers (TCASI 2019).
https://ieeexplore.ieee.org/abstract/document/8667322/authors#authors

### Testing:

[24] Bohan Yang, Vladimir Rožić, Nele Mentens, Wim Dehaene and Ingrid Verbauwhede, _TOTAL: TRNG On-the-fly Testing for Attack detection using Lightweight hardware,_ Design, Automation & Test in Europe (DATE 2016).
https://www.esat.kuleuven.be/cosic/publications/article-2595.pdf 

[25] Miloš Grujić, Vladimir Rožić, Bohan Yang and Ingrid Verbauwhede, _Lightweight Prediction-Based Tests for On-Line Min-Entropy Estimation,_ IEEE Embedded Systems Letters vol. 9 (2), 2017.
http://ieeexplore.ieee.org/document/7886358/ 

