# MiniMax H3 双采样 V4 · ComfyUI 工作流备份

这是本机「【46】H3 最强全能流再进化 V4」整合包的**工作流与部署清单**，方便备份和复现。`workflows/H3-双采样V4.json` 从原整合包原样复制；本仓库没有整合包原作者的来源或授权证明，因此不声明原创，也不附加新的许可。

## 仓库包含什么

- `workflows/H3-双采样V4.json`：原始工作流，SHA-256 `4f00162b29bd95a945b156991e0664fcc930e205cbbcc72bcbbed4d2947349ea`。
- `MODELS.md`：原整合包内模型文件名和运行工作流所需的模型。
- `SOURCES.md`：ComfyUI、H3 模型及第三方节点的上游项目。

**这里不包含** Windows 便携版程序、Python 环境、模型权重、LoRA、原始 RAR 包、用户素材、输出视频和数据库。原整合包约 198 GiB，单个 RAR 约 47 GiB；GitHub 普通 Git 单文件上限为 100 MiB，Git LFS 也有单文件大小限制。

## 使用

1. 安装近期版本的 [ComfyUI](https://github.com/Comfy-Org/ComfyUI)，并按 [SOURCES.md](SOURCES.md) 安装工作流需要的第三方节点。保留各上游项目的许可证和说明。
2. 将模型放到 ComfyUI 的 `models/` 对应子目录；具体文件名见 [MODELS.md](MODELS.md)。模型文件应从有权分发的原始来源获取。
3. 在 ComfyUI 中打开 `workflows/H3-双采样V4.json`，检查缺失节点和模型选择。原工作流引用了一个未随 JSON 附带的参考图文件，运行前要替换为自己的图片。
4. 本机 RTX 5060 Ti 环境中，曾通过启动参数 `--disable-xformers --use-pytorch-cross-attention` 绕过 xformers 兼容问题。这是本机记录，不保证适用于其他显卡。

## 来源与发布

「【46】H3 最强全能流再进化 V4」是一个本地整合包，不是已确认的单一 GitHub 项目。工作流原作者及整合包下载页目前未确认。此仓库草稿应先作为**私有备份**；公开发布前应确认工作流和各模型、LoRA 的再分发许可，并补上原作者署名和来源。
