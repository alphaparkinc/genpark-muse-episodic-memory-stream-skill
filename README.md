# GenPark Muse Episodic Memory Stream Skill

[![GenPark Certified](https://img.shields.io/badge/GenPark-Certified%20Skill-00E599?style=flat-square)](https://genpark.ai)
[![Protocol](https://img.shields.io/badge/MCP-Standard%20Skill-6A0DAD?style=flat-square)](https://genpark.ai)
[![Category](https://img.shields.io/badge/Category-Service%20Agent-blue?style=flat-square)](https://genpark.ai)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg?style=flat-square)](LICENSE)

> GenPark AI Agent Skill - Continuous hierarchical episodic memory stream, exponential temporal decay, cross-session preference anchoring, and personal knowledge graphs.  
> *Inspired by architectural paradigms from Meta Muse (about.meta.com).*

---

## 🌟 Overview & Architecture

Modern personal agents must evolve past static prompt-response turn-taking into **continuous ambient cognitive companions**.  
The `genpark-muse-episodic-memory-stream-skill` brings production-grade primitives for Model Context Protocol (MCP) clients, autonomous agent swarms, and personal assistants operating within the GenPark ecosystem.

```
+-------------------------------------------------------------+
|                GenPark Personal Agent Swarm                 |
+-------------------------------------------------------------+
       |                                              |
       v                                              v
+-----------------------------+        +------------------------------+
|   Zero-Prompt Anticipator   |        |   Hierarchical Memory Stream |
| (Activity & Context Sensing)|        |   (Temporal Decay & Vectors) |
+-----------------------------+        +------------------------------+
       |                                              |
       +----------------------+-----------------------+
                              |
                              v
       +----------------------------------------------+
       |     Autonomous Guardrailed Micro-Delegator    |
       |  (Sandboxed Dispatch & Token Budget Gating)  |
       +----------------------------------------------+
```

---

## 🛠️ Exposed Tools & Capabilities

### `append_episodic_stream`
Appends multimodal conversation turns, situational context, and key decisions into the continuous episodic stream.

### `query_hierarchical_memory`
Performs semantic vector recall with exponential recency decay weighting and personal preference priors.

### `synthesize_personal_profile`
Extracts long-term user tendencies, persistent goals, and domain preferences into structured profile anchors.


---

## 🚀 Quickstart & MCP Configuration

Add this skill to your `genpark.config.json` or Claude / Cursor desktop MCP configurations:

```json
{
  "mcpServers": {
    "genpark-muse-episodic-memory-stream-skill": {
      "command": "npx",
      "args": ["-y", "@alphapark/genpark-muse-episodic-memory-stream-skill"],
      "env": {
        "GENPARK_API_KEY": "your_genpark_api_key"
      }
    }
  }
}
```

---

## 📄 License
Apache-2.0 © 2026 GenPark AI Inc. (alphaparkinc)
