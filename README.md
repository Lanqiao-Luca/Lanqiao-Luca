# 程序员澜桥 · Luca

**Java 研发与 AI 工程实践。** 我做交易、订单等复杂业务系统，也用 AI 辅助拆需求、写代码、跑测试和审查改动，方便团队复核与交接。

## 代表成果

- **AI 协作研发案例** · 为一个虚构的 Spring Boot 标签接口，我用 AI 澄清需求、编写代码和测试，再分开验证、并行审查，最后汇总交付。案例公开了代码、测试和交付报告，记录显示最终通过 25 项离线 Spring 测试。[看完整协作案例](https://github.com/Lanqiao-Luca/ai-java-workflow/tree/main/examples/native-spring-workflow) · [查看运行结果](https://github.com/Lanqiao-Luca/ai-java-workflow/blob/main/examples/native-spring-workflow/result.md)
- **开源贡献** · 我向第三方项目 LangGraph4j 提交修复，解决并行分支完成后最终结果可能丢失的问题，并补上回归测试。[查看已合并的 PR #517](https://github.com/langgraph4j/langgraph4j/pull/517)
- **视频作品** · 《雨夜最后一班电车》，约 30 秒的 AI 漫画短片。[查看成片](https://github.com/Lanqiao-Luca/ai-video-marker/blob/main/assets/videos/reference-comic/preview.mp4)

## 主要项目

### Java / Spring Boot 研发 · ai-java-workflow

把业务要求写成可检查的验收条件，交付时留下代码、测试和审查记录，方便团队复核与交接。

| 批量归档案例 | 交付与验证 |
| --- | --- |
| **任务要求** | 批量归档时遇到无效条目，整个请求失败，原有数据保持原样。 |
| **完成内容** | 实现 Spring Boot 接口，先检查全部条目与版本，再提交变更。 |
| **验收结果** | 记录显示，当前实现通过全部 14 项测试。预设错误版本触发 3 项预期失败，用于检查测试能否识别部分写入问题。 |
| **适用范围** | 虚构业务、单进程内存数据，使用模拟身份。测试范围为本地接口与服务行为。 |

[看完整案例](https://github.com/Lanqiao-Luca/ai-java-workflow/tree/main/examples/design-to-spring) · [查看运行回执](https://github.com/Lanqiao-Luca/ai-java-workflow/blob/main/examples/design-to-spring/result.json) · [查看独立复跑记录](https://github.com/Lanqiao-Luca/ai-java-workflow/blob/main/examples/design-to-spring/independent-result.json)

### 视频创作 · ai-video-marker

把分镜、素材、剪辑和导出过程留给后续创作复用。仓库提供已完成的漫画短片和可本地重渲的像素动画示例。

<a href="https://github.com/Lanqiao-Luca/ai-video-marker/blob/main/assets/videos/reference-comic/preview.mp4"><img src="https://raw.githubusercontent.com/Lanqiao-Luca/ai-video-marker/main/assets/images/reference-comic/poster.jpg" width="320" alt="《雨夜最后一班电车》封面，点击查看成片"></a>

[▶ 点击观看约 30 秒成片](https://github.com/Lanqiao-Luca/ai-video-marker/blob/main/assets/videos/reference-comic/preview.mp4) · [漫画短片制作说明](https://github.com/Lanqiao-Luca/ai-video-marker/tree/main/examples/reference-comic) · [看 44 秒像素动画《屋顶晒太阳》](https://github.com/Lanqiao-Luca/ai-video-marker/blob/main/assets/videos/pixel-rooftop/preview.mp4)

## 工程经验

- **复杂业务** · 梳理交易、订单和售后流程，明确状态流转、异常分支和变更边界。
- **性能与稳定性** · 关注可观测性、性能瓶颈定位和线上问题排查。
- **AI 辅助研发** · 用 Claude、Codex 辅助整理需求、实现改动和检查遗漏，交付时保留验证记录。

## 深入了解

[Java 项目使用说明与架构](https://github.com/Lanqiao-Luca/ai-java-workflow#框架架构) · [视频项目与运行方法](https://github.com/Lanqiao-Luca/ai-video-marker) · [GitHub 项目交流](https://github.com/Lanqiao-Luca/ai-java-workflow/issues)

如果你想试一个小范围的研发任务，可以带一个验收条件明确的需求，在项目 Issues 里交流怎样验证交付结果。
