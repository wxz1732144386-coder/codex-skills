# Codex 技能

这个仓库保存个人使用的 Codex 技能。

## LibTV 分镜提示词

技能路径：[`skills/libtv-storyboard-prompt`](skills/libtv-storyboard-prompt)

直接拆解交给 Codex 的参考视频，逐镜记录动作、服装发型、面部状态、背景、机位、剪辑与声音；需要时结合当次已核实的 LibTV 连线素材，写出中文可复制提示词。技能本身不上传素材、不提交生成任务，也不消耗 LibTV 积分。

### 在另一台电脑安装

登录 Codex 后，让它安装这个 GitHub 技能：

> 请从 `wxz1732144386-coder/codex-skills` 仓库的 `skills/libtv-storyboard-prompt` 路径安装技能。

也可以将仓库克隆到本地，再把整个 `skills/libtv-storyboard-prompt` 目录复制到该电脑的 `~/.codex/skills/` 下。安装后在新对话中使用 `$libtv-storyboard-prompt`。

GitHub 仓库用于保存和分发技能；在另一台电脑登录 Codex 后，仍需安装一次。

## 擦边舞蹈替换人物

提供原舞蹈视频和 LibTV 连线图，将目标模特图连到同一个生成节点。技能会按当次素材编号编写一段可复制的中文提示词，默认使用 Wan 3.0、720P。模特图控制人物外观和穿搭，原视频控制舞步、节奏和镜头。

在另一台电脑的 Codex 中发送以下安装指令：

> 请从 `wxz1732144386-coder/codex-skills` 仓库的 `skills/libtv-dance-character-replacement` 路径安装技能。

安装后，在新对话中使用 `$libtv-dance-character-replacement`。技能文件位于 [skills/libtv-dance-character-replacement](skills/libtv-dance-character-replacement)。
