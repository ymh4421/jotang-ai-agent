# 任务一：

- 使用agent：Codex

- 安装过程：open ai官网安装。配置过程：系统生成默认配置

- 任务：修改之前make和cmake任务中answers文件夹中的两个md格式文件

- 修改内容：大面积修改我的答案，补充了解答内容，如关于预处理步骤中替换#define定义的宏等细节，并用markdown优化了note的排版

- 在输入git diff之后，终端首先输出了diff --git a/answers/task1.md b/answers/task1.md
- index df74e9d..20b54e9 100644
- --- a/answers/task1.md
- +++ b/answers/task1.md
- @@ -1,14 +1,31 @@
- 然后显示了codex修改的两个文件，其中原版本的文本行前面都有"-"标记，且显示为红色，修改后的文本行开头有"+"标记，显示为绿色

- 一开始尝试时codex无法访问WSL里面的文件，多次尝试无果，然后我将文件迁移到windows系统里，codex才能正常工作。但最终结果令我满意