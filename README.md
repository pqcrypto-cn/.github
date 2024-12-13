## 组织介绍

我们是国内专注于后量子密码算法设计与高性能安全实现的研究团队，长期从事密码领域相关的理论研究，具备丰富的密码软件高性能安全实现的开发经验，同时熟悉**密码理论**与**实践层面**的安全分析，持续为本领域各方面需求提供技术输出。

我们设计的多个后量子密码算法，具备国际领先的技术水平，同时通过 PQMagic 高性能后量子密码算法库，提供当前最优性能的开源实现，为学术和工业界提供技术支持，为后量子密码迁移工作提供解决方案。

## PQMagic 高性能后量子密码算法库

[PQMagic](https://pqcrypto.dev/)（Post-Quantum Magic）是国内首个支持 [FIPS 203 204 205 标准](https://csrc.nist.gov/news/2024/postquantum-cryptography-fips-approved) 的**高性能安全后量子密码算法库**，并支持性能更高效的**国产自研** PQC 算法 **Aigis-Enc、Aigis-Sig**（[PKC 2020]((https://eprint.iacr.org/2019/510))）和 **SPHINCS-Alpha**（[CRYPTO 2023](https://eprint.iacr.org/2022/059)）。 该项目由郁昱教授团队（[上海交通大学](https://crypto.sjtu.edu.cn/lab/) 、[上海期智研究院](https://sqz.ac.cn/password-48)）开发和维护，旨在提供自主、可控、安全、高性能的 PQC 算法，以及为后量子密码迁移工作提供解决方案。

PQMagic 支持针对不同架构与国产化设备定制高性能优化版本，有进一步需求欢迎[联系我们](#联系我们)。

|           | PQMagic-std  | PQMagic-adv |
| :-------: | :----------: | :---------: |
| ML-KEM (FIPS 203)    |  ✅          |  ✅                  |
| Kyber     |  ✅          |  ✅                  |
| Aigis-enc |  ✅          |  ✅                  |
| ML-DSA (FIPS 204)    |  ✅          |  ✅                  |
| SLH-DSA (FIPS 205)   |  ✅          |  ✅                  |
| Dilithium |  ✅          |  ✅                  |
| Aigis-sig |  ✅          |  ✅                  |
| SPHINCS-Alpha |  ✅          |  ✅                  |
| 特性       | 跨平台/架构 高度兼容 | 针对x64（海光）、ARM（飞腾）等定制高性能优化版本 |
| 源码       | 开源于[gitee](https://gitee.com/pqcrypto/pqmagic) 和 [github](https://github.com/pqcrypto-cn/PQMagic) | 请[联系我们](#联系我们)获取高性能优化支持 |

### 应用

- [PQSign](https://pqcrypto.cn/applications/pqsign/)（使用 Aigis-sig 对文件做签名/验签）
- [SM3Sum](https://pqcrypto.cn/applications/sm3sum)（使用 SM3 哈希来检验文件完整性）
- OpenSSH（已支持后量子密钥交换）

## 他们正在使用

我们与如下单位进行合作，提供跨平台高兼容性版本和高性能版本后量子密码算法支持。

- [中电信量子集团](http://www.chinatelecom.com.cn/)
- [量子网络](https://qtict.com/)
- [上海市数字证书认证中心有限公司](https://www.sheca.com/)

## 捐助
如果您觉得我们的开源软件对你有所帮助，请多多使用并欢迎提出您的宝贵意见～
需要高性能版本支持请[联系我们](#联系我们)。

## 联系我们
网站1: https://pqcrypto.dev
网站2: https://pqcrypto.cn
邮箱: contact [at] pqcrypto.dev
