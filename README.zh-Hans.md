# EnvStudio 用户反馈

<p align="right">
  <a href="README.md">English (US)</a>
  |
  <a href="README.zh-Hant.md">繁體中文</a>
  |
  <a href="README.ja.md">日本語</a>
  |
  <a href="README.de.md">Deutsch</a>
  |
  <a href="README.fr.md">Français</a>
  |
  <a href="README.es.md">Español</a>
  |
  <a href="README.pt.md">Português</a>
  |
  <a href="README.ru.md">Русский</a>
  |
  <a href="README.ko.md">한국어</a>
</p>

## 关于 EnvStudio

**EnvStudio** 是一款现代化的 Windows 环境变量管理工具，基于 WinUI 3 原生构建。它替代了那个 20 年几乎没有变过的「系统属性 → 环境变量」对话框，为环境变量管理带来了原生的 Windows 11 体验。

<p align="center">
  <img src="https://prunelab.net/products/envstudio/covers/zh/cover1.png" width="48%" />
  <img src="https://prunelab.net/products/envstudio/covers/zh/cover2.png" width="48%" />
</p>

## 下载

<p>
  <a href="https://apps.microsoft.com/detail/9nl5scxw3320" target="_blank">
    <img src="https://get.microsoft.com/images/en-us%20dark.svg" width="200" alt="Download from Microsoft Store"/>
  </a>
</p>

## 核心功能

- **直观的可视化编辑器** — 通过现代化的 WinUI 3 界面添加、编辑、删除和重排环境变量。
- **PATH 列表管理** — 拖拽排序、一键去重、死链检测，PATH 条目管理从未如此简单。
- **EXE 覆盖检测** — 扫描 PATH 中所有目录的可执行文件，展示被覆盖的程序，一键跳转到冲突项。
- **作用域冲突检测** — 用户变量覆盖同名系统变量时显示删除线和警告图标，一眼看清当前生效的值。
- **非破坏性开关** — 禁用变量而不删除，随时一键恢复，告别"删了怕找不回来"的焦虑。
- **删除安全检查** — 删除前自动扫描其他变量中的 `%VARNAME%` 引用，防止级联故障。
- **变量展开预览** — 鼠标悬停在 `%VAR%` 引用上即可看到完整解析路径。
- **外部变更检测** — 实时监控注册表，其他程序修改环境变量时立即提醒刷新。
- **方案切换** — 为不同开发环境保存命名配置方案（如"Java 8""Node.js""AI/ML"），侧栏一键切换。
- **快照与回滚** — 每次保存自动创建快照，Git 风格的差异对比，一键回滚到任意历史版本。
- **搜索与筛选** — 支持正则表达式，匹配的 PATH 子项自动展开并显示匹配数量。
- **导出脚本** — 一键导出为 `.ps1`、`.bat` 或 `.env` 文件，方便团队共享或系统重装后恢复。
- **UAC 提权** — 无缝的管理员提权，用于编辑系统变量。
- **即时广播** — 通过 `WM_SETTINGCHANGE` 将更改立即广播至整个系统。

## 100% 离线 · 完全免费

EnvStudio **不联网、不上传数据、不包含任何遥测或统计埋点。** 你的环境变量配置始终只存储在自己的电脑上。

所有功能**完全免费**，无广告，无付费墙。未来可能会增加捐赠入口，但不会对任何功能收费。

详情请参阅[隐私政策](https://prunelab.net/zh/products/envstudio/privacy)。

---

## 反馈入口

> **注意：** 本仓库**不包含** EnvStudio 的源代码，仅用于收集用户反馈和问题跟踪。

| 操作 | 链接 |
|------|------|
| 反馈 Bug | [提交 Bug 报告](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=bug_report.yml) |
| 功能建议 | [提交新功能建议](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=feature_request.yml) |
| 查看全部 Issues | [Issues](https://github.com/PruneLab/EnvStudio-Feedback/issues) |

## 反馈前须知

请先搜索[已有 Issues](https://github.com/PruneLab/EnvStudio-Feedback/issues)，避免重复提交。

提交 Bug 报告时请包含：
- **EnvStudio 版本**（在「设置 → 关于」中查看）
- **Windows 版本**（如 Windows 11 23H2）
- **复现步骤**
- **期望行为** vs **实际行为**
- 截图（如有）

## 功能建议

我们很乐意听到你的想法！提交前请注意：
- 检查是否已有人提出类似建议
- 描述使用场景——这个功能能解决什么问题？
- 欢迎提供示意图或参考链接
