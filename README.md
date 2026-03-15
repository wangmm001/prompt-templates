# Prompt Templates Library - 提示词模板库

🎯 专业的 AI 提示词模板集合，聚焦流量分析、技术评估、安全研究领域

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Templates](https://img.shields.io/badge/templates-15+-blue.svg)](templates/)
[![Quality](https://img.shields.io/badge/quality-rated-green.svg)](docs/evaluation.md)

---

## 📖 项目简介

本仓库收集并整理了高质量的 AI 提示词模板，特别针对：

- 🔍 **流量分析** - 网络流量检测、协议识别、异常发现
- 🛡️ **网络安全** - 威胁检测、漏洞评估、事件响应
- 📊 **技术评估** - 技术路线规划、竞品分析、ROI 评估
- 🤖 **AI 应用** - 大模型应用、自动化分析、智能报告

### 核心特色

- ✅ **质量评级** - 每个模板经过严格评估，附带质量评分
- ✅ **开箱即用** - 参数化设计，替换变量即可使用
- ✅ **领域专业** - 由安全专家设计，体现行业最佳实践
- ✅ **持续更新** - 定期新增模板，跟进技术发展

---

## 📁 项目结构

```
prompt-templates/
├── README.md                 # 项目说明
├── docs/                     # 文档
│   ├── evaluation.md         # 质量评价框架
│   ├── best-practices.md     # 最佳实践指南
│   └── prompt-engineering.md # 提示词工程基础
├── templates/                # 模板库
│   ├── traffic-analysis/     # 流量分析模板
│   ├── security/             # 安全领域模板
│   ├── tech-assessment/      # 技术评估模板
│   └── general/              # 通用模板
├── examples/                 # 使用示例
│   ├── input-examples/       # 输入示例
│   └── output-samples/       # 输出样例
└── config/                   # 配置文件
    └── template-config.yaml  # 模板配置
```

---

## 🚀 快速开始

### 使用模板

1. **选择模板**: 浏览 `templates/` 目录找到合适模板
2. **替换参数**: 将 `{{parameter}}` 替换为实际值
3. **发送给 AI**: 将完整提示词发送给 AI 助手
4. **优化迭代**: 根据输出质量调整参数

### 示例

```markdown
# 使用流量分析模板

## 原始模板
请分析 {{traffic_type}} 流量，检测 {{threat_types}} 类型威胁。
准确率要求：{{accuracy}}，延迟要求：{{latency}}

## 替换后
请分析 HTTPS 加密流量，检测 C2 通信和数据外泄类型威胁。
准确率要求：>95%，延迟要求：<100ms
```

---

## 📊 模板分类

### 按领域分类

| 类别 | 模板数量 | 说明 |
|-----|---------|------|
| 流量分析 | 6 | 网络流量检测、协议识别、加密分析 |
| 安全评估 | 4 | 威胁检测、漏洞评估、事件响应 |
| 技术规划 | 3 | 技术路线、竞品分析、趋势预测 |
| 通用分析 | 2 | ROI 分析、实施计划 |

### 按质量分级

| 等级 | 模板数量 | 说明 |
|-----|---------|------|
| ⭐⭐⭐⭐⭐ 优秀 | 5 | 可直接用于生产环境 |
| ⭐⭐⭐⭐ 良好 | 6 | 少量修改即可使用 |
| ⭐⭐⭐ 可用 | 4 | 需要适当调整 |

---

## 📋 模板列表

### 流量分析系列

| 模板 | 评分 | 用途 |
|-----|------|------|
| [综合技术路线分析](templates/traffic-analysis/tech-roadmap.md) | ⭐⭐⭐⭐⭐ | 年度技术规划 |
| [加密流量分析](templates/traffic-analysis/encrypted-traffic.md) | ⭐⭐⭐⭐⭐ | TLS 流量检测 |
| [威胁检测对比](templates/traffic-analysis/threat-detection.md) | ⭐⭐⭐⭐ | 安全产品选型 |
| [深度学习应用](templates/traffic-analysis/deep-learning.md) | ⭐⭐⭐⭐ | AI 技术调研 |
| [快速评估](templates/traffic-analysis/quick-assessment.md) | ⭐⭐⭐⭐ | 快速决策 |
| [技术成熟度](templates/traffic-analysis/trl-assessment.md) | ⭐⭐⭐ | 技术评估 |

### 安全评估系列

| 模板 | 评分 | 用途 |
|-----|------|------|
| [安全事件分析](templates/security/incident-analysis.md) | ⭐⭐⭐⭐⭐ | 事件响应 |
| [漏洞评估](templates/security/vulnerability-assessment.md) | ⭐⭐⭐⭐ | 风险评估 |
| [攻击溯源](templates/security/attack-attribution.md) | ⭐⭐⭐⭐ | 威胁情报 |
| [合规检查](templates/security/compliance-check.md) | ⭐⭐⭐ | 审计支持 |

### 技术评估系列

| 模板 | 评分 | 用途 |
|-----|------|------|
| [竞品分析](templates/tech-assessment/competitive-analysis.md) | ⭐⭐⭐⭐ | 产品选型 |
| [技术趋势](templates/tech-assessment/tech-trends.md) | ⭐⭐⭐ | 战略规划 |
| [ROI 分析](templates/tech-assessment/roi-analysis.md) | ⭐⭐⭐ | 成本评估 |

---

## 🎯 质量评价框架

每个模板从 5 个维度进行评估：

```
结构完整性 (25%) - 角色、上下文、任务、输出格式
可执行性 (25%)   - 指令清晰、可操作、无歧义
领域专业性 (20%) - 专业知识、术语准确
灵活性 (15%)     - 参数化、可扩展、适配场景
输出质量 (15%)   - 结构化、可验证、有价值
```

详见：[docs/evaluation.md](docs/evaluation.md)

---

## 📚 使用指南

### 最佳实践

```markdown
✅ 明确具体的角色定义
✅ 提供充分的上下文信息
✅ 指定清晰的输出格式
✅ 设定合理的约束条件
✅ 包含可验证的评估标准

❌ 避免模糊的指令
❌ 避免过于宽泛的问题
❌ 避免缺少输出格式要求
```

### 提示词工程框架

#### CO-STAR 框架
- **C**ontext: 上下文
- **O**bjective: 目标
- **S**tyle: 风格
- **T**one: 语气
- **A**udience: 受众
- **R**esponse: 响应格式

#### CREATE 框架
- **C**haracter: 角色
- **R**equest: 请求
- **E**xamples: 示例
- **A**djustments: 调整
- **T**ype: 类型
- **E**xtras: 额外信息

详见：[docs/prompt-engineering.md](docs/prompt-engineering.md)

---

## 🔧 高级用法

### 模板组合

多个模板组合使用获得更全面分析：

```
技术路线模板 + ROI 分析模板 = 完整技术方案
威胁检测模板 + 竞品分析模板 = 产品选型报告
```

### 参数化配置

使用配置文件批量管理参数：

```yaml
# config/template-config.yaml
traffic_analysis:
  daily_volume: "10TB"
  accuracy_target: "99%"
  latency_limit: "50ms"
```

### 输出后处理

结合脚本自动化处理 AI 输出：

```bash
# 提取关键结论
ai-output | grep "## 核心结论" -A 10
```

---

## 🤝 贡献指南

欢迎贡献新的提示词模板！

### 提交要求

1. 遵循模板格式规范
2. 提供质量自评（5 个维度）
3. 包含使用示例
4. 添加适当的标签分类

### 提交流程

1. Fork 项目
2. 创建模板文件
3. 更新模板列表
4. 提交 PR

详见：[docs/contributing.md](docs/contributing.md)

---

## 📄 许可证

MIT License - 详见 [LICENSE](LICENSE) 文件

---

## 📬 联系方式

- 🐛 Issues: [GitHub Issues](https://github.com/wangmm001/prompt-templates/issues)
- 💬 Discussions: [GitHub Discussions](https://github.com/wangmm001/prompt-templates/discussions)

---

## ⭐ Star History

如果这些模板对你有帮助，请给一个 Star! 🌟
