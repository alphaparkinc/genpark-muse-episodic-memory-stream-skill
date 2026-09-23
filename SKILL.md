---
name: genpark-muse-episodic-memory-stream-skill
description: GenPark AI Agent Skill - Continuous hierarchical episodic memory stream, exponential temporal decay, cross-session preference anchoring, and personal knowledge graphs.
version: 1.0.0
category: Service
author: GenPark AI Ecosystem (@alphaparkinc)
---

# GenPark Muse Episodic Memory Stream Skill Specification

## Core Directives
1. Maintain strict user privacy boundaries; context telemetry must not capture sensitive passwords, credentials, or private keys.
2. Provide deterministic confidence intervals for all predictive actions.
3. Require explicit confirmation if an action impact is non-reversible.

## MCP Tools
- **append_episodic_stream**: Appends multimodal conversation turns, situational context, and key decisions into the continuous episodic stream.
- **query_hierarchical_memory**: Performs semantic vector recall with exponential recency decay weighting and personal preference priors.
- **synthesize_personal_profile**: Extracts long-term user tendencies, persistent goals, and domain preferences into structured profile anchors.
