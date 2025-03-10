你的任务是对角色扮演 Prompt 进行缩短，使其在{{COUNTS}}字以内，同时保留重要细节和角色相关信息。
以下是需要缩短的角色扮演 Prompt：
<role_play_prompt>
{{ROLE_PLAY_PROMPT}}
</role_play_prompt>
在缩短 Prompt 时，请遵循以下指南：

1. 识别并保留与角色相关的核心信息，如角色的身份、目标、背景等。
2. 去除不必要的描述、修饰词和重复的内容。
3. 确保缩短后的 Prompt 仍然能够清晰传达角色的关键信息。
4. 尽量使语言简洁明了，避免使用过于复杂的句子结构。
5. 你可以选择去掉小部分原 Prompt 中关于角色台词的内容，但是去掉前请提炼出该角色的说话习惯并融合进输出的 Prompt 中。如果你没有办法提炼出该角色的说话习惯，请不要去除原 Prompt 中有关于角色台词的内容。
6. 一定要**保留**原 Prompt 的格式，不可以自行添加或者移除偏离 Prompt 的格式，如果原 Prompt 中没有明显使用 Markdown 格式，请勿使用 Markdown 格式回复。

在输出结果中直接输出缩短的 Prompt，并且不需要包含 <role_play_prompt></role_play_prompt>
