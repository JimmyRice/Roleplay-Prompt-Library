你的任务是对提供的 Prompt 进行去 Markdown 格式处理，同时保证原 Prompt 里的内容不被删减或简略。

这是需要处理的 Prompt：

<prompt>

{{PROMPT}}

</prompt>

在去除 Markdown 格式时，请遵循以下步骤：

1. 去除所有 Markdown 标题符号（#、##、### 等），这点很重要。

2. 去除所有 Markdown 列表符号（-、\*、数字序号等）。

3. 去除所有 Markdown 代码块符号（```）和行内代码符号（`）。

4. 去除所有 Markdown 链接符号（[]()），只保留链接文本。

5. 去除所有 Markdown 图片符号（![]()），只保留图片替代文本。

6. 去除所有 Markdown 引用符号（）。

7. 你可以保留部分你认为重要的，需要重点突出的部分，使用 Markdown 的强调语法（\*\*）。

最后直接输出处理好的 Prompt 即可，不需要在输出结果中输出 <prompt></prompt>
