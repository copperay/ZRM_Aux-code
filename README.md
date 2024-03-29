# ZRM_Aux-code
- 这是笔者根据同好者整理的《自然码2009新春版码表（6码标准版）》整理而成的适配手心输入法导入辅助码格式的自然码码表。
- 仅为笔者作为自然码爱好者为推广自然码之用，禁止商用，欢迎同好者下载！

*2022.1.11 Update:* `ZRM_Aux-code_2.0.txt`

- 9428 identical items that are caused due to previous unreasonable algorithm have been removed by a novel version of algorithm.

*2022.7.1 Update:* `ZRM_Aux-code_3.0.txt`

- 充分利用手心输入法对辅助码表的格式要求上的便利，在完全不影响实际导入的内容的情况下，将码表进一步压缩，使之更加小巧强大。

*2022.12.1 Update:* `ZRM_Aux-code_4.0.txt`

- 为提高兼容性，以`ZRM_Aux-code_2.0.txt`为底物，放弃`ZRM_Aux-code_3.0.txt`

- 已删除词条：

  XO=,

  3C=,

  ￥=b

  QQ=,

  QC=,

  PK=,

  No=,

  NC=,

  ○=o

  ○=oo

  ID=,

  GB=,

  ↑=js

  ↑=jt

  ↑=ju

  →=jt

  →=jy

  ←=jt

  ←=jz

  ↓=jt

  ↓=jx

  ↖=jt

  ↗=jt

  ↘=jt

  ↙=jt

  ↙=zw

- 已删除《生僻字码改造计划（第一版）》中收录的词条

*2022.12.12 Update:* `ZRM_Aux-code_4.2.txt`

- 已删除《生僻字码改造计划（第一版）》中收录的词条
- 已删除《生僻字码改造计划（第二版）》中收录的词条
- 已删除《生僻字码改造计划（第三版）》中收录的词条

*2023.1.30 Update:* `ZRM_Aux-code_4.3.txt`

- 已删除《生僻字码改造计划（第四版）》中收录的词条

# 生僻字码改造计划

- 生僻字码改造计划是我结合实际使用，设想的一个对码表的优化计划。旨在将《自然码2009新春版》码表中与常用二字词冲突的四码生僻字和部分不合理编码剔除，以此达到尽量不影响生僻字输入的前提下，减少对常用四码二字词的输入的妨碍，提高输入效率。
- 热心的本套码表的使用者们，你们也可举出你们在使用过程中发现的，与高频的四码二字词冲突的四码生僻字，我新开了一个Issue专门讨论这个计划，十分感谢您为码表优化所做的贡献！
- 当然，如果您不喜欢这样的改造，您可以选择未经修改的以前版本：`ZRM_Aux-code.txt`、`ZRM_Aux-code_2.0.txt`、`ZRM_Aux-code_3.0.txt`

# CodeSearcher
*2022.2.4 Update:*
- 《自然码辅码查询》是笔者基于Qt（C++ Binding）开发的用以查询自然码辅码的小程序，运行后选择安装目录，密码为："Copper"，解压后运行CodeSearcher.exe文件即可使用！建议创建一个快捷方式到桌面，方便使用。
- 使用说明：输入框输入待查询的汉字或辅助码，然后选择模式即可查询。需要指出的是，在无论是输入框还是结果的输出框，“辅码”都只包括四码中的后二码（或第三码）。

# AuxcodeQuerier
*2022.7.1 Update:*
- 这是由我开发的一个可以在线查询自然码辅助码的网站，便利大家使用。
- [AuxcodeQuerier](https://copperay.github.io/AuxcodeQuerier)

# Zacqs
*2022.11.12 Update:*
- Zacqs, or Ziranma Auxiliary-Code Querying System（自然码辅助码查询系统）, is my latest App developed under WPF framework, providing the same features of CodeSearcher, which is written under Qt instead of WPF, thus higher performance and less storage space occupation than CodeSearcher available. 

*2022.12.1 Update:*
- 新增默认按钮为查询，即输入查询字后按回车即可查询
- 优化了UI