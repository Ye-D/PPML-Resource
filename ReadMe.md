# Privacy-Preserving-Machine-Learning-Resources

## Content
- [About](#about)
- [Secure Machine Learning](#secure-machine-learning)
- [MPC](#MPC)
- [Federated Learning](#federated-learning)
- [Privacy Leakages of ML/FL](#privacy-leakages-of-ml/fl)
- [Blogs](#blogs)
- [Libraries and Frameworks](#libraries-and-frameworks)


# About
This is a current list of resources related to the research and development of privacy-preserving machine learning.


# Secure Machine Learning
* [Machine Learning Classification over Encrypted Data, NDSS'14](https://eprint.iacr.org/2014/331.pdf)
* [Oblivious Multi-Party Machine Learning on Trusted Processors, USENIX SECURITY'16](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/ohrimenko)
* [Prio: Private, Robust, and Scalable Computation of Aggregate Statistics, NSDI'17](https://www.usenix.org/conference/nsdi17/technical-sessions/presentation/corrigan-gibbs)
* [SecureML: A System for Scalable Privacy-Preserving Machine Learning, S&P'17](https://eprint.iacr.org/2017/396)
* [MiniONN: Oblivious Neural Network Predictions via MiniONN Transformations, CCS'17](https://acmccs.github.io/papers/p619-liuA.pdf)
* [Chameleon: A Hybrid Secure Computation Framework for Machine Learning Applications, AsiaCCS'17](https://eprint.iacr.org/2017/1164)
* [DeepSecure: Scalable Provably-Secure Deep Learning, DAC'17](https://arxiv.org/abs/1705.08963)
* [Secure Computation for Machine Learning With SPDZ, NIPS'18](https://arxiv.org/abs/1901.00329)
* [ABY3:a Mixed protocol Framework for Machine Learning, CCS'18](https://eprint.iacr.org/2018/403.pdf)
* [SecureNN: Efficient and Private Neural Network Training, PoPETs'18](https://eprint.iacr.org/2018/442.pdf)
* [Gazelle: A Low Latency Framework for Secure Neural Network Inference, USENIX SECURITY'18](https://arxiv.org/abs/1801.05507)
* [CHET: an optimizing compiler for fully-homomorphic neural-network inferencing, PLDI'19](https://dl.acm.org/citation.cfm?id=3314628)
* [New Primitives for Actively-Secure MPC over Rings with Applications to Private Machine Learning, S&P'19](https://eprint.iacr.org/2019/599.pdf)
* [Helen: Maliciously Secure Coopetitive Learning for Linear Models, S&P'19](https://ieeexplore.ieee.org/abstract/document/8835215)
* [Efficient multi-key homomorphic encryption with packed ciphertexts with application to oblivious neural network inference. CCS'19](https://dl.acm.org/citation.cfm?id=3363207)
* [XONN: XNOR-based Oblivious Deep Neural Network Inference, USENIX Security'19](https://www.usenix.org/conference/usenixsecurity19/presentation/riazi)
* [QUOTIENT: two-party secure neural network training and prediction, CCS'19](https://dl.acm.org/citation.cfm?id=3339819)
* [Secure Evaluation of Quantized Neural Networks, PoPETs'20](https://content.sciendo.com/view/journals/poPoPETs/2020/4/article-p355.xml)
* [ASTRA: High Throughput 3PC over Rings with Application to Secure Prediction, CCSW'19](https://eprint.iacr.org/2019/429)
* [SoK: Modular and Efficient Private Decision Tree Evaluation, PoPETs'19](https://eprint.iacr.org/2018/1099.pdf)
* [Trident: Efficient 4PC Framework for Privacy Preserving Machine Learning, NDSS'20](https://eprint.iacr.org/2019/1315)
* [BLAZE: Blazing Fast Privacy-Preserving Machine Learning, NDSS'20](https://eprint.iacr.org/2020/042)
* [FLASH: Fast and Robust Framework for Privacy-preserving Machine Learning, PoPETs'20](https://eprint.iacr.org/2019/1365)
* [Delphi: A Cryptographic Inference Service for Neural Networks, USENIX SECURITY'20](https://eprint.iacr.org/2020/050)
* [ParSecureML: An Efficient Parallel Secure Machine Learning Framework on GPUs, ICPP'20](https://dl.acm.org/doi/abs/10.1145/3404397.3404399)
* [FALCON: Honest-Majority Maliciously Secure Framework for Private Deep Learning, PoPETs'21](https://arxiv.org/abs/2004.02229)
* [MP2ML: A Mixed-Protocol Machine Learning Framework for Private Inference, ARES'20](https://dl.acm.org/doi/abs/10.1145/3407023.3407045)
* [SANNS: Scaling Up Secure Approximate k-Nearest Neighbors Search, USENIX Security'20](https://www.usenix.org/conference/usenixsecurity20/presentation/chen-hao)
* [PySyft: A Generic Framework for Privacy Preserving Deep Learning](https://arxiv.org/abs/1811.04017)
* [Private Deep Learning in TensorFlow Using Secure Computation](https://arxiv.org/abs/1810.08130)
* [CryptoDL: Deep Neural Networks over Encrypted Data](https://arxiv.org/abs/1711.05189)
* [CryptoNets: Applying Neural Networks to Encrypted Data with High Throughput and Accuracy](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/04/CryptonetsTechReport.pdf)
* [CrypTFlow: Secure TensorFlow Inference](https://eprint.iacr.org/2019/1049.pdf)
* [CrypTFlow2: Practical 2-Party Secure Inference, CCS'20](https://arxiv.org/abs/2010.06457)
* [ARIANN: Low-Interaction Privacy-Preserving Deep Learning via Function Secret Sharing](https://arxiv.org/abs/2006.04593)
* [Practical Privacy-Preserving K-means Clustering, PoPETs'20](https://content.sciendo.com/view/journals/poPoPETs/2020/4/article-p414.xml)
* [SOTERIA: In Search of Efficient Neural Networks for Private Inference, 20](https://arxiv.org/abs/2007.12934)
* [SWIFT: Super-fast and Robust Privacy-Preserving Machine Learning, USENIX Security'21](https://arxiv.org/abs/2005.10296)
* [An Efficient 3-Party Framework for Privacy-Preserving Neural Network Inference, ESORICS'20](https://link.springer.com/chapter/10.1007/978-3-030-58951-6_21)
* [Secure and Verifiable Inference in Deep Neural Networks, ACSAC'20](https://dl.acm.org/doi/abs/10.1145/3427228.3427232)
* [Privacy-preserving Density-based Clustering, AisaCCS'21](https://www.eurecom.fr/publication/6475/download/sec-publi-6475.0.pdf)
* [SIRNN: A Math Library for Secure RNN Inference, S&P'21](https://eprint.iacr.org/2021/459)
* [Let’s Stride Blindfolded in a Forest: Sublinear Multi-Client Decision Trees Evaluation, NDSS'21](https://www.ndss-symposium.org/ndss-paper/lets-stride-blindfolded-in-a-forest-sublinear-multi-client-decision-trees-evaluation/)
* [MUSE: Secure Inference Resilient to Malicious Clients, USENIX Security'21](https://people.eecs.berkeley.edu/~raluca/MUSEcamera.pdf)
* [DeepReDuce: ReLU Reduction for Fast Private Inference, ICML'21](https://arxiv.org/abs/2103.01396)
* [Garbled Neural Networks are Practical](https://eprint.iacr.org/2019/338.pdf)
* [GForce : GPU-Friendly Oblivious and Rapid Neural Network Inference, USENIX Security'21](https://www.usenix.org/conference/usenixsecurity21/presentation/ng)
* [CryptGPU: Fast Privacy-Preserving Machine Learning on the GPU, S&P'21](http://arxiv.org/abs/2104.10949)
* [GALA : Greedy ComputAtion for Linear Algebra in Privacy-Preserved Neural Networks, NDSS'21](https://www.ndss-symposium.org/ndss-paper/gala-greedy-computation-for-linear-algebra-in-privacy-preserved-neural-networks/)
* [Fantastic Four: Honest-Majority Four-Party Secure Computation With Malicious Security, USENIX Security'21](https://www.usenix.org/system/files/sec21fall-dalskov.pdf)
* [When homomorphic encryption marries secret sharing: secure large-scale sparse logistic regression and applications in risk control, KDD'21](https://arxiv.org/abs/2008.08753)
* [Glyph: Fast and Accurately Training Deep Neural Networks on Encrypted Data, NeurIPS'20](https://arxiv.org/pdf/1911.07101.pdf)
* [Mystique: Efficient Conversions for Zero-Knowledge Proofs with Applications to Machine Learning, USENIX Security'21](https://eprint.iacr.org/2021/730)
* [SoK: Efficient Privacy-preserving Clustering, PoPETs'21](https://eprint.iacr.org/2021/809)
* [ZEN: Efficient Zero-Knowledge Proofs for Neural Networks](https://eprint.iacr.org/2021/087/20210127:132648)
* [zkCNN: Zero Knowledge Proofs for Convolutional Neural Network Predictions and Accuracy, CCS'21](https://eprint.iacr.org/2021/673)
* [Secure Quantized Training for Deep Learning](https://arxiv.org/abs/2107.00501)
* [Cerebro: A Platform for Multi-Party Cryptographic Collaborative Learning, USENIX Security'21](https://www.usenix.org/conference/usenixsecurity21/presentation/zheng)
* [Tetrad: Actively Secure 4PC for Secure Training and Inference, NDSS'22](https://arxiv.org/abs/2106.02850)
* [Adam in Private : Secure and Fast Training of Deep Neural Networks with Adaptive Moment Estimation](https://arxiv.org/abs/2106.02203)
* [SIMC: ML Inference Secure Against Malicious Clients at Semi-Honest Cost, USENIX Security'22](https://www.usenix.org/conference/usenixsecurity22/presentation/chandran)
* [Circa : Stochastic ReLUs for Private Deep Learning, NeurIPS'21](https://proceedings.neurips.cc/paper/2021/file/11eba2991cc62daa4a85be5c0cfdae97-Paper.pdf)
* [Cheetah: Lean and Fast Secure Two-Party Deep Neural Network Inference, USENIX Security'22](https://eprint.iacr.org/2022/207)
* [Secure Poisson Regression, USENIX Security'22](https://www.usenix.org/conference/usenixsecurity22/presentation/kelkar)
* [MPClan: Protocol Suite for Privacy-Conscious Computations, IACR ePrint'22](https://eprint.iacr.org/2022/675)
* [LLAMA: A Low Latency Math Library for Secure Inference, PoPETs'22](https://eprint.iacr.org/2022/793)

# MPC
* [Scalable and unconditionally secure multiparty computation, Crypto'07](https://www.iacr.org/archive/crypto2007/46220565/46220565.pdf)
* [Sharemind: A framework for fast privacy-preserving computations, ESORICS'08](https://link.springer.com/chapter/10.1007/978-3-540-88313-5_13)
* [Secure computation with fixed-point numbers, FC'10](https://link.springer.com/chapter/10.1007/978-3-642-14577-3_6)
* [Multiparty computation from somewhat homomorphic encryption, Crypto'12](https://link.springer.com/chapter/10.1007/978-3-642-32009-5_38)
* [Practical covertly secure MPC for dishonest majority–or: breaking the SPDZ limits, ESORICS'13](https://link.springer.com/chapter/10.1007/978-3-642-40203-6_1)
* [GMW vs. Yao? Efficient secure two-party computation with low depth circuits, FC'13](https://link.springer.com/chapter/10.1007/978-3-642-39884-1_23)
* [Efficiently Verifiable Computation on Encrypted Data, CCS'14](https://dl.acm.org/citation.cfm?id=2660366)
* [实用安全多方计算协议关键技术研究进展, 计算机研究与发展'15](https://crad.ict.ac.cn/CN/10.7544/issn1000-1239.2015.20150763)
* [ABY: A Framework for Efficient Mixed-Protocol Secure Two-Party Computation, NDSS'15](https://encrypto.de/papers/DSZ15.pdf)
* [MASCOT: faster malicious arithmetic secure computation with oblivious transfer, CCS'16](https://dl.acm.org/citation.cfm?id=2978357)
* [High-Throughput Semi-Honest Secure Three-Party Computation with an Honest Majority, CCS'16](https://dl.acm.org/citation.cfm?id=2978331)
* [High- throughput secure three-party computation for malicious adversaries and an honest majority, Crypto'17](https://eprint.iacr.org/2016/944.pdf)
* [A Framework for Constructing Fast MPC over Arithmetic Circuits with Malicious Adversaries and an Honest-Majority, CCS'17](https://eprint.iacr.org/2017/816.pdf)
* [Overdrive^2k: Making SPDZ Great Again, Eurocrypto'18](https://eprint.iacr.org/2017/1230)
* [SPDZ^2k: Efficient MPC mod 2^k for Dishonest Majority, Crypto'18](https://link.springer.com/chapter/10.1007/978-3-319-96881-0_26)
* [Secure outsourced matrix computation and application to neural networks, CCS'18](https://dl.acm.org/doi/10.1145/3243734.3243837)
* [Fast large-scale honest-majority MPC for malicious adversaries, Crypto'18](https://eprint.iacr.org/2018/570)
* [PrivPy: General and Scalable Privacy-Preserving Data Mining, KDD'19](https://dl.acm.org/doi/abs/10.1145/3292500.3330920)
* [MP-SPDZ: A Versatile Framework for Multi-Party Computation, CCS'20](https://dl.acm.org/doi/10.1145/3372297.3417872)
* [Senate: A Maliciously-Secure MPC Platform for Collaborative Analytics, USENIX Security'20](https://www.usenix.org/conference/usenixsecurity21/presentation/poddar)
* [Improved primitives for mpc over mixed arithmetic-binary circuits, CRYPTO'20](https://eprint.iacr.org/2020/338.pdf)
* [MOTION - A Framework for Mixed-Protocol Multi-Party Computation, TOPS'21](https://eprint.iacr.org/2020/1137)
* [ABY2.0: Improved Mixed-Protocol Secure Two-Party Computation (Full Version), USENIX Security'21](https://eprint.iacr.org/2020/1225.pdf)
* [SynCirc: Efficient Synthesis of Depth-Optimized Circuits for Secure Computation, HOST'21](https://encrypto.de/papers/PSSY21HOST.pdf)
* [MAGE: Nearly Zero-Cost Virtual Memory for Secure Computation, USENIX OSDI'21](https://www.usenix.org/conference/osdi21/presentation/kumar)
* [VASA : Vector AES Instructions for Security Applications, ACSAC'21](https://eprint.iacr.org/2021/1493.pdf)
* [ATLAS: Efficient and Scalable MPC in the Honest Majority Setting, CRYPTO'21](https://eprint.iacr.org/2021/833)
* [The Cost of IEEE Arithmetic in Secure Computation, LatinCrypt'21](https://eprint.iacr.org/2021/054)
* [安全多方计算及其在机器学习中的应用, 计算机研究与发展'21](https://crad.ict.ac.cn/CN/10.7544/issn1000-1239.2021.20210626)
* [SecFloat: Accurate Floating-Point meets Secure 2-Party Computation, S&P'22](https://eprint.iacr.org/2022/322)
* [Fast Fully Secure Multi-Party Computation over Any Ring with Two-Thirds Honest Majority, CCS'22](https://eprint.iacr.org/2022/623)


# Federated Learning
## Secure Federated Learning
* [Privacy-Preserving Deep Learning, CCS'15](https://dl.acm.org/citation.cfm?id=2813687)
* [Practical Secure Aggregation for Privacy Preserving Machine Learning, CCS'17](https://eprint.iacr.org/2017/281.pdf)
* [Privacy-Preserving Deep Learning via Additively Homomorphic Encryption, TIFS'17](https://ieeexplore.ieee.org/document/8241854)
* [NIKE-based Fast Privacy-preserving High-dimensional Data Aggregation for Mobile Devices, CACR'18](http://cacr.uwaterloo.ca/techreports/2018/cacr2018-10.pdf)
* [PrivFL: Practical Privacy-preserving Federated Regressions on High-dimensional Data over Mobile Networks, CCSW'19](https://eprint.iacr.org/2019/979.pdf)
* [VerifyNet: Secure and verifiable federated learning, TIFS'19](https://ieeexplore.ieee.org/abstract/document/8765347)
* [PrivColl: Practical Privacy-Preserving Collaborative Machine Learning](https://link.springer.com/chapter/10.1007/978-3-030-58951-6_20)
* [NPMML: A Framework for Non-interactive Privacy-preserving Multi-party Machine Learning, TDSC'20](https://ieeexplore.ieee.org/abstract/document/8981947)
* [SAFER: Sparse secure Aggregation for FEderated leaRning](https://arxiv.org/abs/2007.14861)
* [Secure Byzantine-Robust Machine Learning](https://arxiv.org/abs/2006.04747)
* [Secure Single-Server Aggregation with (Poly)Logarithmic Overhead, CCS'20](https://eprint.iacr.org/2020/704.pdf)
* [Batchcrypt: Efficient homomorphic encryption for cross-silo federated learning, USENIX ATC'21](https://www.usenix.org/conference/atc20/presentation/zhang-chengliang)
* [FedSel: Federated SGD under Local Differential Privacy with Top-k Dimension Selection, DASFAA'20](https://arxiv.org/abs/2003.10637)
* [FLGUARD: Secure and Private Federated Learning, Cryptology Eprint'21](https://eprint.iacr.org/2021/025)
* [Biscotti: A Blockchain System for Private and Secure Federated Learning, TPDS'21](https://ieeexplore.ieee.org/document/9292450)
* [POSEIDON: Privacy-Preserving Federated Neural Network Learning, NDSS'21](https://arxiv.org/abs/2009.00349)
* [PPFL: Privacy-preserving Federated Learning with Trusted Execution Environments, MobiSys'21](https://arxiv.org/abs/2104.14380)

## Communication Optimization
* [Terngrad: Ternary gradients to reduce communication in distributed deep learning, NIPS'17](http://papers.nips.cc/paper/6749-terngrad-ternary-gradients-to-reduce-communication-in-distributed-deep-learning)
* [The Convergence of Sparsified Gradient Methods, NIPS'18](https://papers.nips.cc/paper/2018/hash/314450613369e0ee72d0da7f6fee773c-Abstract.html)

## Byzantine-Tolerant
* [Machine Learning with Adversaries: Byzantine Tolerant Gradient Descent, NIPS'17](http://papers.nips.cc/paper/6617-machine-learning-with-adversaries-byzantine-tolerant-gradient-descent)
* [Byzantine stochastic gradient descent, NIPS'18](https://papers.nips.cc/paper/2018/file/a07c2f3b3b907aaf8436a26c6d77f0a2-Paper.pdf)
* [The Hidden Vulnerability of Distributed Learning in Byzantium, ICML'18](https://arxiv.org/abs/1802.07927)
* [Byzantine-Robust Distributed Learning: Towards Optimal Statistical Rates, ICML'18](https://arxiv.org/abs/1803.01498)
* [Local Model Poisoning Attacks to Byzantine-Robust Federated Learning, USENIX Security'20](https://www.usenix.org/conference/usenixsecurity20/presentation/fang)
* [FLTrust: Byzantine-robust Federated Learning via Trust Bootstrapping, NDSS'21](https://arxiv.org/abs/2012.13995)
* [Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses for Federated Learning, NDSS'21](https://www.ndss-symposium.org/ndss-paper/manipulating-the-byzantine-optimizing-model-poisoning-attacks-and-defenses-for-federated-learning/)
* [Justinian’s GAAvernor: Robust Distributed Learning with Gradient Aggregation Agent, USENIX Security'20](https://www.usenix.org/system/files/sec20-pan.pdf)
* [Byzantine-robust and privacy-preserving framework for FEDML, ICLR Workshop'21](https://arxiv.org/pdf/2105.02295.pdf)
* [Learning from History for Byzantine Robust Optimization, ICML'21](http://proceedings.mlr.press/v139/karimireddy21a/karimireddy21a.pdf)
* [FLAME: Taming backdoors in federated learning, USENIX Security'22](https://arxiv.org/abs/2101.02281)


# Privacy Leakages of ML/FL
* [Membership inference attacks against machine learning models, S&P'17](https://ieeexplore.ieee.org/abstract/document/7958568)
* [Comprehensive privacy analysis of deep learning: Passive and active white-box inference attacks against centralized and federated learning, S&P'19](https://ieeexplore.ieee.org/abstract/document/8835245)
* [Data Poisoning Attacks Against Federated Learning Systems, ESORICS'20](https://link.springer.com/chapter/10.1007/978-3-030-58951-6_24)
* [A Framework for Evaluating Client Privacy Leakages in Federated Learning, ESORICS'20](https://link.springer.com/chapter/10.1007/978-3-030-58951-6_27)
* [A Critical Overview of Privacy in Machine Learning, IEEE Security & Privacy'21](https://www.computer.org/csdl/magazine/sp/2021/04/09433648/1tHMTWXyaUE)


# Blogs
* [Cryptography and Machine Learning: Mixing both for private data analysis](https://mortendahl.github.io/)
* [Building Safe A.I.: A Tutorial for Encrypted Deep Learning](https://iamtrask.github.io/2017/03/17/safe-ai/)
* [Awesome MPC: Curated List of resources for MPC](https://github.com/rdragos/awesome-mpc)
* [机器学习隐私保护](https://www.zhihu.com/column/c_1121838720017338368)


# Libraries and Frameworks
* [TinyGarble: Logic Synthesis and Sequential Descriptions for Yao's Garbled Circuits](https://github.com/esonghori/TinyGarble)
* [SPDZ-2: Multiparty computation with SPDZ, MASCOT, and Overdrive offline phases](https://github.com/bristolcrypto/SPDZ-2)
* [ABY: A Framework for Efficient Mixed-Protocol Secure Two-Party Computation](https://github.com/encryptogroup/aby)
* [Obliv - C: C compiler for embedding privacy preserving protocols:](http://oblivc.org/)
* [TFHE: Fast Fully Homomorphic Encryption Library over the Torus](https://github.com/tfhe/tfhe)
* [SEAL: Simple Encypted Arithmatic Library](https://www.microsoft.com/en-us/research/project/simple-encrypted-arithmetic-library/)
* [PySEAL: Python interface to SEAL](https://github.com/Lab41/PySEAL)
* [HElib: An Implementation of homomorphic encryption](https://github.com/shaih/HElib])
* [EzPC: programmable, efficient, and scalable secure two-party computation for machine learning](https://github.com/mpc-msri/EzPC)
* [CUDA-accelerated Fully Homomorphic Encryption Library](https://github.com/vernamlab/cuFHE)
* [CrypTen: A framework for Privacy Preserving Machine Learning](https://github.com/facebookresearch/CrypTen)
* [tf-encrypted: A Framework for Machine Learning on Encrypted Data](https://github.com/tf-encrypted/tf-encrypted)
* [Sharemind](https://sourceforge.net/projects/sharemind/)
* [PythonPaillier](https://github.com/data61/python-paillier)
* [TenSEAL](https://github.com/OpenMined/TenSEAL)
* [MP-SPDZ](https://github.com/data61/MP-SPDZ)
* [Securenn-public](https://github.com/snwagh/securenn-public)
* [SecMML](https://github.com/FudanMPL/SecMML)
* [mnist-mpc](https://github.com/csiro-mlai/mnist-mpc)
* [Private-Set-Intersection](https://github.com/bit-ml/Private-Set-Intersection)
* [falcon-public](https://github.com/snwagh/falcon-public)
* [Rosetta](https://github.com/LatticeX-Foundation/Rosetta)
* [Antchain-MPC](https://github.com/alipay/Antchain-MPC)
* [Kunlun](https://github.com/yuchen1024/Kunlun)
* [MOTION2NX](https://github.com/encryptogroup/MOTION2NX)
* [SecureQ8](https://github.com/anderspkd/SecureQ8)
* [mpc-benchmarks](https://github.com/mkskeller/mpc-benchmarks)
* [muse](https://github.com/mc2-project/muse)
* [Primihub](https://github.com/primihub/primihub)
