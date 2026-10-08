# self-hosted-PKM
适用于 Windows 的离线笔记软件，参考飞书文档的编辑体验，支持富文本、表格、图片、视频与本地附件。

安装与保存
使用 Windows 10/11 64 位系统，双击 `本地笔记-0.7.2-安装包.exe` 安装，可选择安装位置并创建快捷方式。
有 E 盘时，默认笔记目录为 `E:\practice\Codex-noteapp`；无 E 盘时使用当前用户的“文档\本地笔记”。每篇文档可另选文件夹，普通编辑覆盖保存，保留最近 10 组会话内撤销；需要副本时可手动导出 Word、PDF 或完整 ZIP 备份。
对照参考飞书官方[文档帮助中心与[表格编辑]，本项目与飞书无官方关联。
<img width="2242" height="1440" alt="image" src="https://github.com/user-attachments/assets/1942e964-09fd-4807-ae48-de2353c1fad7" />
<img width="2242" height="1440" alt="image" src="https://github.com/user-attachments/assets/e1659602-4c11-4a5a-8f70-91b2a5fd8708" />

本地开发
使用 Node.js 22.12+，首次安装开发依赖需要联网。桌面程序运行所需资源随安装包提供，日常使用可离线进行。
