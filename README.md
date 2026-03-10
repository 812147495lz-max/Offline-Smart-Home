# 全本地智能家居系统白皮书

**——基于单节点边缘算力的个人落地终身进化版**

智能家居行业已从单品智能升级到全屋互联，但多数方案仍依赖云端、规则僵化、长期不稳定。本Jarvis全本地智能家居系统以单节点消费级边缘算力为核心，实现全本地闭环、多模态感知、用户意图精准识别与全场景协同，达成人在回路主导的终身自主进化体验。核心原则：全本地闭环、学习遗忘对称、软件定义体验、稳定优先。

**行业现有方案共性局限：**
1. 云端依赖：隐私泄露、断网失效、延迟高。
2. 规则僵化：无法适配动态需求、缺乏意图理解。
3. 规则堆积：无生命周期管理，长期误触发、系统臃肿。
4. 成本体验难平衡：高端硬件昂贵，消费级弱。

**系统核心创新：**
1. 全本地闭环：所有感知推理决策存储本地完成，零公网暴露，断网可用，隐私极致保护。
2. 学习与遗忘对称：规则自动附带休眠失效条件，长期未触发则删除，确保终身稳定、越用越精准。
3. 主动预判：空间语义感知+行为理解，提前匹配需求，实现无感智能。
4. 消费级旗舰体验：软件优化民用毫米波雷达、摄像头与Mac Mini，一台主机驱动全屋。

**核心技术体系：**
- 硬件：单台Mac Mini M4（32GB），低功耗7×24运行，Metal GPU加速。
- 感知：毫米波雷达触发+MediaPipe视觉校验追踪，软置信度状态，夜间优化。
- 决策引擎：Ollama本地分层大模型，轻量快决策+主脑复杂推理，响应<2秒。
- 记忆遗忘：三层架构（InfluxDB短期、SQLite缓冲、Qdrant长期向量），标签生命周期管理，避免膨胀。
- 交互：MediaPipe视线追踪+唇动免唤醒Whisper语音，纠错学习个性化。

**核心落地场景：**
- 起夜无感灯光陪伴路径。
- 全屋环境光自适应调光。
- 厨房免唤醒自然语音。
- 零穿戴跌倒应急救援。
- 模糊意图预判（如游戏模式）。
- 跨季节规则自动休眠唤醒。
- 访客模式一键切换。

**核心价值：**
- 隐私安全：100%本地闭环，断网无影响。
- 终身稳定：规则动态清理不臃肿。
- 主动智能：预判无感适配。
- 普惠落地：消费级成本旗舰体验。
- 用户可控：学习内容确认生效，人在回路。

---

# Full Local Smart Home System White Paper

**— Personal Deployment & Lifelong Evolution Edition Based on Single-Node Edge Computing**

The smart home industry has evolved from single-device intelligence to whole-home interconnection. However, most solutions still rely on the cloud, use rigid rules, and lack long-term stability. Our **Jarvis Full Local Smart Home System** uses a single consumer-grade edge computing node as its core to deliver a fully local closed-loop architecture. It enables multimodal spatial perception, precise user intent recognition, and full-scene device collaboration—achieving a lifelong autonomous evolution experience with humans firmly in the loop. Core principles: full local closed-loop, symmetric learning and forgetting, software-defined experiences, and stability-first.

**Common Limitations of Existing Solutions:**
1. Cloud Dependency: Privacy leaks, complete failure during outages, and high latency.
2. Rigid Rules: Cannot adapt to changing habits or understand real user intent.
3. Rule Accumulation: No lifecycle management leads to false triggers and system bloat over time.
4. Cost-Experience Gap: High-end hardware is prohibitively expensive; consumer-grade options deliver weak intelligence.

**Core Innovations:**
1. Full Local Closed-Loop: All perception, reasoning, decisions, and storage happen locally with zero public internet exposure. Works perfectly offline—ultimate privacy protection.
2. Symmetric Learning & Forgetting: Every auto-generated rule carries built-in dormancy and expiration conditions. Unused rules are automatically deleted, guaranteeing lifelong stability and ever-increasing precision.
3. Proactive Prediction: Spatial semantic awareness + behavior understanding anticipates needs before they arise, delivering truly imperceptible intelligence.
4. Consumer-Grade Flagship Experience: Advanced software unlocks the full potential of everyday millimeter-wave radars, cameras, and a single Mac Mini to power the entire home.

**Core Technology Stack:**
- Hardware: Single Mac Mini M4 (32GB) — ultra-low power 7×24 operation with native Metal GPU acceleration.
- Perception: Millimeter-wave radar trigger + MediaPipe visual verification & tracking with soft confidence states; night-mode optimized.
- Decision Engine: Ollama locally deployed layered models — lightweight for instant decisions + powerful main brain for complex reasoning (<2s response).
- Memory & Forgetting: Three-layer architecture (InfluxDB short-term, SQLite buffer, Qdrant long-term vector DB) with tagged lifecycle management to prevent any bloat.
- Interaction: MediaPipe gaze + lip-movement wake-free Whisper voice recognition with daily error-correction learning.

**Key Real-World Scenarios:**
- Nighttime gentle lighting path companion.
- Whole-home ambient light self-adaptation.
- Kitchen wake-free natural voice control.
- Zero-wear fall detection & emergency rescue.
- Fuzzy intent prediction (e.g., automatic game mode).
- Cross-season rule auto-dormancy and wakeup.
- One-click guest mode switching.

**Core Value:**
- Privacy & Security: 100% local closed-loop, completely unaffected by network outages.
- Lifelong Stability: Dynamic rule cleanup keeps the system lean forever.
- Proactive Intelligence: Predictive, seamless adaptation.
- Affordable & Accessible: Flagship-level experience at true consumer-grade cost.
- Full User Control: All learned content requires explicit confirmation—humans always stay in the loop.

*Shortened Chinese version (<1000 characters). Perfect for GitHub README.md or whitepaper.md. Copy and paste directly!*
