# ZJUBCA.PROPOSALS
ZJUBCA improivment proposals repository。

本仓库用于收集协会成员对协会发展的提案，并结合内部投票工具对提案进行投票。一旦投票通过后，提案应当被无条件执行。

## Working Flow
1. 新建issue，根据模板填写提案内容。**提案号即为issue号**。初步审查后，**添加标签`valid`。**
2. 提案经过充分讨论并修正后，由管理员加上`voting`标签，进入**投票阶段**。
3. 在规定的期限内，使用内部投票工具对提案进行投票。TODO：投票规则设计与工具开发。
4. 到期时检查投票数量，判断提案是否通过。
5. 若提案通过，仓库维护者将相应提案的issue关闭，并加上`pass`标签。同时，在本项目的`proposals`目录下，以`ZIP-#提案号.md`为文件名创建提案文件，并将提案内容以`markdown`形式填写。
6. 协会管理层对通过的提案指定解决方案与计划，提交至对应提案的子目录下。由协会所有成员监督。
7. 若提案不通过，仓库维护者关闭相应`issue`，并加上`not pass`标签。

## Notice
1. 杜绝刷票行为。
2. 对提案的讨论与广泛共识尽量在**线下完成**，线上投票应仅作为**最终共识的表现形式**。
3. 提案的执行纳入激励机制的作用范围。
