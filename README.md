# ProgramTestData

本仓库主要内容为“区块链脆弱性分析及利用技术研究”项目测试数据

## 说明

* 本项目主要包括两个原型系统
    * 区块链合约层漏洞检测原型系统
    * 智能合约安全形式化验证原型系统
      分别支持**solidity**和**golang**两种语言智能合约的**漏洞检测**和**形式化验证**。
* 按照项目要求，本项目支持未知漏洞的检测
      即发现以往研究工作中未曾关注到的安全漏洞，对该漏洞进行定义和分析，并支持此类之前未知类型的漏洞的检测。
* 按照项目要求，本项目支持区块链智能合约漏洞利用
      即在仿真环境中部署已发现存在漏洞的智能合约，利用其存在的漏洞，对该合约进行攻击，以研究漏洞的危害以及防御的方式。
* 各目录中存放各功能点对应的测试代码。
      所列代码均为开源代码，相应说明了其存在的安全问题以及下载地址。
