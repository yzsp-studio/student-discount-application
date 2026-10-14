<div align="center">

# 🎬 student-discount-application

## 认证卡住？9 类状态逐个给话术，直到权益到账
## Nine states, one script each — guided until the benefit lands

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

这是一个办理专业版学生优惠申请的对话技能。它按统一工具返回的阶段文本路由，引导用户完成抖音账号绑定、学生认证和权益领取，并逐阶段给出用户口吻的提示话术。首次进入学生认证阶段时会执行一次学信网当前有效学籍核验，再展示本轮返回的认证二维码——二维码只从当轮返回内容里提取，绝不复用旧链接。它的安全边界很硬：不询问账号密码、短信验证码、身份证号和人脸信息，登录、实名、人脸与付费环节一律交还用户亲自在浏览器完成。只有明确的权益到账终态才告知领取成功，其余终态如实说明原因并立即结束流程。

### ✨ 能做什么

- 按工具返回的阶段文本路由，覆盖账号绑定、学生认证、权益领取全流程
- 9 类业务状态各有对应话术，不把内部操作提示直接转发给用户
- 首次学生认证阶段执行一次学信网有效学籍核验，每个办理周期仅一次
- 二维码只取本轮返回的链接，杜绝复用旧码和猜测链接
- 不询问密码 / 验证码 / 身份证号 / 人脸信息，敏感操作全部交还用户手动完成
- 终态立即停止、自动重查上限 1 次，权益名称与有效期只按返回内容展示

### 📦 包含的技能

- `student-discount-application` —— 见 [`student-discount-application/SKILL.md`](student-discount-application/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/student-discount-application.git
cp -r student-discount-application/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

A conversational skill that handles a professional-tier student discount application. It routes on the stage text returned by a single business tool, walking the user through account binding, student verification and benefit redemption with a natural, user-facing script at each stage. On the first entry into student verification it runs one enrollment-status check and then shows the QR code from that same turn's response — the code is extracted only from the current turn and never reused. Its safety boundary is strict: it never asks for passwords, SMS codes, ID numbers or face data, and hands login, identity verification, face scan and any payment step back to the user to complete in their own browser. It only announces success at an explicit benefit-granted end state, and otherwise explains the real reason and stops immediately.

### ✨ What it does

- Routes on the returned stage text and covers the full flow of binding, student verification and redemption
- Nine business states each get their own user-facing script instead of internal tool instructions
- Runs one enrollment-status check on first entry to student verification, at most once per application cycle
- QR codes come only from the current turn's response, so stale codes and guessed links are ruled out
- Never asks for passwords, verification codes, ID numbers or face data; sensitive steps go back to the user
- Stops immediately at end states with at most one automatic re-query, and shows benefit names and validity only as returned

### 📦 Skills included

- `student-discount-application` — [`student-discount-application/SKILL.md`](student-discount-application/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/student-discount-application.git
cp -r student-discount-application/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
