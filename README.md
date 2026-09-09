<div align="center">

# Jignesh Borse (Jay)

### **Software Engineer · iOS Systems · Developer Tooling · Model Context Protocol (MCP)**

*Building production mobile systems, Apple ecosystem tools, and local AI agent infrastructure.*

<br/>

<p align="center">
  <a href="https://www.npmjs.com/~jigneshborse">
    <img src="https://img.shields.io/badge/npm-Packages-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm"/>
  </a>
  <a href="https://github.com/JayBorse/appsvantage-preflight">
    <img src="https://img.shields.io/badge/MCP-Server-4F46E5?style=for-the-badge&logo=anthropic&logoColor=white" alt="MCP"/>
  </a>
  <a href="https://www.linkedin.com/in/jignesh-borse-60182a21a/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://twitter.com/jayborse1">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/>
  </a>
  <a href="mailto:jigneshborse111@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

</div>

---

### 👨‍💻 About

I am a Software Engineer specializing in **native iOS / mobile systems**, **developer tooling**, and **local AI agent architectures**. 

My core work sits at the intersection of **Apple system APIs** (CoreML, CoreMIDI, ARKit, TestFlight), **zero-dependency CLI utilities**, and **Model Context Protocol (MCP) servers** for Cursor, Windsurf, and Claude Code. I design software with a strong emphasis on client-side privacy, deterministic execution, and low-latency performance.

* 📱 **Native iOS & Mobile**: Swift, SwiftUI, Objective-C, React Native, Xcode, App Store Connect.
* 🛠️ **Developer Infrastructure**: Zero-dependency standalone CLIs, npm distribution, CI/CD build gates.
* 🤖 **AI Agents & MCP**: Autonomous developer tools via Model Context Protocol, local LLM orchestration.
* 🎓 **Education**: B.E. in Computer Engineering (SPPU) · Honors in Spatial Computing & AR/VR.

---

### 🚀 Featured Engineering & Open Source

#### 🛡️ [`appsvantage-preflight`](https://github.com/JayBorse/appsvantage-preflight) — Apple App Store Pre-Flight Auditor & MCP Server
[![npm version](https://img.shields.io/npm/v/appsvantage-preflight.svg?style=flat-square&color=CB3837)](https://www.npmjs.com/package/appsvantage-preflight)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![MCP Compatible](https://img.shields.io/badge/MCP-Cursor%20%7C%20Claude-4F46E5.svg?style=flat-square)](https://github.com/JayBorse/appsvantage-preflight)

An automated pre-submission compliance engine and stdio MCP server for iOS engineers to catch Apple App Review rejections *before* uploading to TestFlight.

```bash
# Instant local audit with zero installation (100% private execution)
npx appsvantage-preflight ./ios

# Launch autonomous MCP server for Cursor / Claude Code
npx appsvantage-preflight mcp
