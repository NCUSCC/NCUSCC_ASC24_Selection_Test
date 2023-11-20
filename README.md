# NCUSCC_ASC24_Selection_Test

ASC24超算竞赛南昌大学参赛队员选拔试题

## 题目背景

随着科技的不断发展，超级计算机在科学研究、工程模拟等领域发挥着越来越重要的作用。为了选拔出在并行计算和高性能计算方面具有优秀能力的学生，我们设计了以下选拔赛题，期待大家能从赛题从有所收获。

赛题参考了今年参加完的SC23竞赛。

## 任务描述

参加者需要在规定的时间内，尽可能的获得较多的得分。
我们将提供远程的云服务器（报名之后通过邮件的形式发送），云服务器使用Chameleon，操作系统均为Ubuntu20.04版本，可以通过提供的IP地址以及密钥通过SSH远程登录（Windows中，可以通过vscode、MobaXterm、Xshell）。

大家在登录进云服务器之后，需要用户的根目录下，创建一个自己名称的目录。

1. 基本的HPL测试，设计一个并行计算程序，解决一个实际科学或工程问题。该问题可能涉及数值模拟、数据处理、图算法等方面，旨在考察参赛者在高性能计算环境下优化算法、提高计算效率的能力。
2. OSPRay
3. 分子动力学模拟，GROMACS，可以根据GROMACS_Test中的文件GROMACS_Test.pdf进行完成，根据问题完成的情况进行评分。
4. Your : 请在报告的结束部分列出加入超算队伍的大概规划和打算学习的内容，由于竞赛的周期较长，我们需要看到你的决心和毅力来完成这项看上去不可能但是能够挑战的竞赛，永不放弃、拼搏极限是我们的宗旨
## 评分标准

正确性、性能优化、文档质量、时间效率进行综合给分。

1. HPL(30分)
2. OSPRay(30分)
3. GRPMACS(30分)
4. Your Determination Challenge(10)

## 提交要求
1. 英文报告必须采用LaTeX撰写（建议使用Overleaf云写作平台，本地不用配置LaTeX写作环境），最后只接收PDF格式的报告，代码及其他支撑材料压缩一并提交。（**代码可以提交Github链接，并且推荐大家使用Github进行代码存储，以防云环境出现问题**）
2. 接收邮箱为：xxx
3. 邮件主题及报告命名：ASC24选拔+班级+姓名
4. Dealine: 2023年12月8日
5. 温馨提示：
   * 可以将曾经获得的竞赛奖项、参与项目等证书以附件提交，作为部分参考依据；
   * 如果试题无法全部完成，也请提交报告，说明无法完成部分的原因，坚持和抗压是最难能可贵的品质。

## 要求限制

* 参赛者可以在规定时间内使用任何编程语言和工具。
* 鼓励参赛者在解决问题时创新思维，提出可能的性能优化方案。
* 禁止使用ChatGPT等大语言模型直接撰写报告，我们有相应的措施进行检测。
* 禁止篡改相关数据，请尽量保留相关的log文件以便使用和检查。
* 禁止互相传阅代码，细则参照：[What is Academic Integrity? | Academic Integrity at MIT](https://integrity.mit.edu/)https://integrity.mit.edu/。

## 参考链接：
* chameleoncloud官网：https://chameleoncloud.readthedocs.io/en/latest/
