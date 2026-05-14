<div align="center">

# Multimodal-DDL

多模态理解、VLM、AIGC、视频和音频评测挑战截止日追踪。

[![GitHub Pages](https://img.shields.io/badge/Pages-live-EC4899?style=for-the-badge)](https://just-agent.github.io/multimodal-ddl/)
[![Just-DDL](https://img.shields.io/badge/Just--DDL-network-101626?style=for-the-badge)](https://just-agent.github.io/just-ddl/)
[![Status](https://img.shields.io/badge/Demo-completed-059669?style=for-the-badge)](https://just-agent.github.io/multimodal-ddl/)

[专题页面](https://just-agent.github.io/multimodal-ddl/) · [Just-DDL Hub](https://just-agent.github.io/just-ddl/#/topic/multimodal-ddl) · [GitHub 仓库](https://github.com/Just-Agent/multimodal-ddl)

</div>

## Demo 已完善

这个仓库不再只是空 Pages 骨架。当前已经包含完整 demo DDL 列表、搜索筛选、状态统计、来源说明和统一 Just-DDL Network 导航。数据风格参考 AllConfs 的会议列表结构，以及 SinoConf 的国内会议/预告/回顾入口。

## Demo DDL Seed

| DDL | 阶段 | 截止日 | 地点 | 来源类型 |
| --- | --- | --- | --- | --- |
| MMMU Challenge 2026 | Leaderboard | 2026-08-15 | Online | Benchmark demo |
| VQA Challenge 2026 | Submission | 2026-07-01 | Online | Benchmark demo |
| AIGC Evaluation 2026 | Final submit | 2026-09-30 | Online | Kaggle-style demo |
| Video-MME Leaderboard Freeze | Leaderboard | 2026-10-12 | Online | Benchmark demo |
| TextVQA Refresh | Result upload | 2026-08-01 | Online | Benchmark demo |
| Audio-Visual Scene Challenge | Submission | 2026-11-05 | Online | Demo seed |
| CVPR VLM Workshop Paper | Workshop paper | 2026-12-01 | Online | Demo seed |
| ACL Multimodal NLP Workshop | Paper | 2027-01-25 | Online | Demo seed |

## 后续生产化

| 模块 | 当前 | 下一步 |
| --- | --- | --- |
| 页面 | 完整 demo 页面已上线 | 替换为真实数据源输出 |
| 数据 | seed 数据在 index.html 内置 | 拆出 JSON/YAML schema |
| Actions | Pages 自动部署 | 增加 crawler、validator、link-check |
| Hub 联动 | 已接入 Just-DDL Hub | 加入更新时间和数据健康状态 |
| 小程序 | 结构已预留 | 复用同一 schema 输出小程序专题页 |

## References

- AllConfs: https://www.allconfs.org/
- SinoConf: https://sinoconf.napstic.cn/index

## License

当前仓库处于产品孵化阶段。正式开源协议会在发布稳定版本前补齐。