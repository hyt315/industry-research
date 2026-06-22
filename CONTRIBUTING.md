# 贡献指南 / Contributing Guide

感谢你考虑为行业研究方法论贡献内容！这个项目旨在帮助更多人从散乱信息中建立结构化的行业认知，你的参与很有价值。

## 贡献方式

- **新增分析框架**：在 `references/frameworks.md` 中补充经过验证的行业分析框架
- **补充输出示例**：在 `references/output-standards.md` 中添加新的行业研究端到端示例
- **改进认知防护**：在 `references/cognitive-traps.md` 中补充新的认知偏差类型或检测方法
- **报告问题**：发现框架描述不准确、数据分层标准有误或内容遗漏
- **翻译优化**：改进中英文内容的自然度和准确性

## 开发流程

1. **Fork** 本仓库
2. 创建你的特性分支：`git checkout -b feature/your-feature`
3. 做出改动并提交：`git commit -m "feat: add something"`
4. 推送到分支：`git push origin feature/your-feature`
5. 创建 Pull Request

## 提交规范

本项目遵循 [Conventional Commits](https://www.conventionalcommits.org/) 规范：

- `feat:` 新增框架或示例
- `fix:` 修复内容错误
- `docs:` 文档改进
- `refactor:` 内容重构（不改变功能）

## 内容准则

- **数据可信度是红线**：新增内容必须遵守 L1-L5 数据分层标准，不标注可信度的精确数据不予接受
- **循证原则**：新增分析框架应有公认的学术或实践基础（PEST、Porter 等级别）
- **来源可追溯**：每个数据点应标注采集日期、来源类型、可信度等级
- **认知防护**：新增内容应避免引入认知偏差，参考 `references/cognitive-traps.md`

## 审查标准

PR 审查时我们会关注：

- [ ] 方法论内容保持准确
- [ ] 新增内容遵守 L1-L5 数据分层标准
- [ ] 新增框架有学术或实践依据支撑
- [ ] 中英文内容结构对应
- [ ] 不修改 LICENSE
- [ ] 内容不包含敏感商业数据或个人隐私

## 行为准则

参与本项目即表示你同意遵守 [行为准则](CODE_OF_CONDUCT.md)。
