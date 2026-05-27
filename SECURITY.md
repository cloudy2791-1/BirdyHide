# Security Policy

本文档说明了 Birdy 项目的安全策略及漏洞报告流程，感谢您为项目安全做出的贡献。

## Reporting a Vulnerability

我们非常重视 Birdy 的安全。如果您发现安全漏洞，请**负责任地私密报告**。

**推荐方式**：  
使用 GitHub 内置的私密报告功能：  
**Security → Report a vulnerability**（本文件生效后按钮会自动出现）

**请勿** 在公开 Issue、Discussion 或 Pull Request 中报告安全问题。

**报告时请提供以下信息**：
- 漏洞详细描述
- 受影响组件（例如：zTXt 解析、AES-GCM 加密、密码强度检查、大文件处理等）
- 完整复现步骤
- 浏览器版本和操作系统
- 潜在影响评估

---

## Disclosure Policy（披露政策）

- 我们遵循 **Coordinated Vulnerability Disclosure (CVD)** 协调披露原则
- 修复完成后我们会发布 GitHub Security Advisory
- 您可以在修复发布后公开讨论

---

## Scope（适用范围）

**在范围内（欢迎报告）**：
- AES-256-GCM 实现缺陷
- PNG zTXt / JPEG 隐写嵌入或提取逻辑问题
- 客户端内存安全、侧信道泄露
- PBKDF2 密钥派生弱点
- 完整性校验绕过
- 大文件处理时的拒绝服务风险

**不在范围内**：
- 用户主动忽略浏览器安全警告导致的问题
- 社会工程学攻击、钓鱼
- 需要物理接触用户设备的场景
- 将工具用于非法用途（详见 LICENSE 与工具内免责声明）

---

**感谢所有安全研究者！**  
您的贡献让 Birdy 更安全，也让隐私保护工具更可靠。

Birdy 项目维护者  
2026 年
