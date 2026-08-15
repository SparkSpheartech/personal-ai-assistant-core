# 🧠 Oynx AI — Local AI Assistant Agent

> **Oynx AI: Your personal autonomous AI assistant — running 100% locally**  
> Voice-enabled, privacy-first, tool-equipped.

---

## 🧠 AI Agent Architecture

```mermaid
graph TB
    subgraph INTERFACE["🎤 Interface"]
        I1[Voice Commands]
        I2[Text Chat]
    end

    subgraph CORE["🧠 Oynx Core Agent"]
        C1[Intent Recognition]
        C2[Context Manager]
        C3[Response Generator]
    end

    subgraph TOOLS["🔧 Tool Agents"]
        T1[Search Agent]
        T2[Memory Agent]
        T3[Web Fetch Agent]
    end

    I1 --> C1
    I2 --> C1
    C1 --> C2
    C2 --> C3
    C3 --> T1
    C3 --> T2
    C3 --> T3

    style C1 fill:#4CAF50,stroke:#333,color:#fff
    style C2 fill:#2196F3,stroke:#333,color:#fff
    style C3 fill:#FF9800,stroke:#333,color:#fff
```

Built by **[Shazaly Musa](https://github.com/SparkSpheartech)** — Founder, SparkSphear Tech  
*AI Agents for Local Personal AI Assistants*