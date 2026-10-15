# Synvarin Harness v1.0.0

Synvarin is an autonomous AI agent harness and native desktop workspace designed for software engineering, deep research, and collaborative problem-solving. It runs natively on Windows with support for both local offline LLMs and major cloud AI providers.

---

### Highlights & Capabilities

- **Unified Model Support**: Connect seamlessly to local inference servers (llama.cpp, Ollama, LM Studio) or leading cloud AI providers (OpenAI, Anthropic, and Google Gemini).
- **Specialized Operational Modes**:
  - **Coding Mode**: Autonomous multi-step development, project directory navigation, file edits, and system command execution.
  - **Chat Mode**: Focused conversational assistance and co-working.
  - **Deep Research**: Comprehensive multi-step exploration and analysis workflows.
- **Safety & Approval Controls**: Granular permission settings ranging from manual step approvals to automated policy controls.
- **Integrated Live Browser & Preview**: Built-in tabbed preview panel to inspect generated web projects and artifacts side-by-side with the agent transcript.
- **Project Workspaces**: Fast folder switching and project memory isolation tailored to your active codebase.
- **Context Management & Auto-Compaction**: Live visual tracking of conversation token consumption with automatic transcript compaction at high utilization.
- **Extensible Architecture**: Support for custom agent roles, MCP servers, domain experts, and local skills.

---

### Installation (Windows 10 / 11)

1. Download **`Synvarin-Setup-1.0.0.exe`** from the **Assets** section below.
2. Run the installer and follow the setup wizard.
3. Launch **Synvarin** from your Start menu or desktop shortcut.

> **Note on Windows SmartScreen**: Because this installer is freshly built and not yet signed with a commercial certificate, Windows Defender SmartScreen may display an *"Unrecognized app"* notice. Click **More info** followed by **Run anyway** to proceed.

---

### System Requirements

- **Operating System**: Windows 10 or Windows 11 (64-bit)
- **Web Runtime**: Microsoft Edge WebView2 (pre-installed on most modern Windows systems)
- **Optional**: Local LLM server (Ollama, LM Studio, or llama.cpp) running on port `8080`, `11434`, or `1234` for 100% offline usage.
