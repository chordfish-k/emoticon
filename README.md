# QChatGPT 表情包插件

- 需要配合[**QChatGPT**](https://github.com/RockChinQ/QChatGPT)最新版本的情景JSON进行调教后方可食用~

- 暂时只支持url形式的图片

<details>

<summary>

## 效果图

</summary>

<img src="/preview.jpg" alt="Preview" width="300" height="250" />

</details>

## 快速品鉴🥰

1. 将 `emoticon_template_mahiru.json` 放入 `scenario` 文件夹.
2. 在bot的 `config.py`文件中将 `preset_mode` 改为 `full_scenario`,并将 `prompt_submit_length`调高到`2000`以上
3. 执行`!reload`命令，并执行 `!reset emoticon_template_mahiru` 切换预设。
4. 开始聊天！

## 自定义方法

1. 在你自定义的JSON预设中**模仿**`emoticon_template_mahiru.json`加入表情包相关要求，并确保机器人能正常输出 `:关键字:`格式的表达式
2. 更改本插件的 `config.py`，设定对应关键字表情包的链接
