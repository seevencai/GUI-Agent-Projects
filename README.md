# GUI-Agent-Projects
<!-- 中文版本 -->
# Awesome GUI Agent  🕹️🤖

> 精选的图形界面智能体（GUI Agent）开源项目列表，持续更新，欢迎 PR！

## 目录
- [移动端/跨平台](#移动端跨平台)
- [桌面端](#桌面端)
- [Web端](#web端)
- [环境/框架/数据集/基准](#环境框架数据集基准)
- [集合](#集合)
---

### 移动端/跨平台
| 名称 | 简介 |
|----|------|
| [Mobile-Agent](https://github.com/X-PLUG/MobileAgent) | 阿里 X-PLUG 第三代跨平台 GUI 代理，基于 7B 原生 VLM「GUI-Owl」，一句自然语言即可在 Android/iOS/Windows/macOS/Web 完成多应用协同任务，支持异常恢复与轨迹反思。 |
| [UI-TARS](https://github.com/bytedance/UI-TARS) | 字节 Seed 团队开源的原生视觉-语言 GUI Agent，仅用屏幕截图作为输入即可输出鼠标/键盘动作，在 AndroidWorld & OSWorld 均取得 SOTA，提供 2B/7B/72B 三档模型。 |
| [AutoGLM](https://github.com/THUDM/AutoWebGLM)| 智谱开源的「端侧+云端」GUI Agent 框架，基于 GLM-4.5/4.5V 双脑协同，支持 Phone/Browser/Computer Use，在 AndroidWorld、WebArena 等多项评测中位列 SOTA。 |

### 桌面端
| 名称 | 简介 |
|----|------|
| [PC-Agent](https://github.com/GAIR-NLP/PC-Agent) | 专注 Windows/macOS 的「离线」桌面助手，强调「While-You-Sleep」长时任务，支持多步骤规划、异常捕获与日记回溯。 |
| [OS-Atlas](https://osatlas.github.io) | 面向「全场景」的基座动作模型（4B/7B），可将自然语言指令映射为跨平台可执行动作，附带迄今最大 GUI Grounding 数据集（230 万截图 / 1300 万元素）[^11^]。 |

### Web端
| 名称 | 简介 |
|----|------|
| [WebVoyager](https://github.com/webvoyager/webvoyager) | 基于多模态大模型的端到端 Web Agent，支持多轮对话、表单填写、购物下单等复杂流程，已提供浏览器插件与 Docker 一键部署。 |

### 环境/框架/数据集/基准
| 名称 | 简介 |
| ---- | ---- |                             |
| [WebArena](https://github.com/web-arena-x/webarena)              | 独立可自托管的「高保真」Web 环境，提供电商、论坛、代码托管等 4 类真实功能站点及 812 条自然语言任务，支持基于 accessibility-tree 的交互接口与自动正确性校验，已成为 Web Agent 主流 benchmark。 |
| [AndroidWorld](https://github.com/google-research/android_world) | Google Research 发布的 Android 端任务级评测环境，内置 116 个跨应用任务与可脚本化模拟器，支持函数调用验证，已作为 AndroidAgent 社区事实基准。 

### 集合
| 名称 | 简介 |
|----|------|
| [Awesome-GUI-Agent](https://github.com/showlab/Awesome-GUI-Agent) | ShowLab 维护的「论文 + 代码 + 数据」汇总仓，包含 GUI 定位、动作序列、评测指标等最全资源列表，并支持 arXiv 链接自动格式化。 |

Maintained by **Seeven**.
