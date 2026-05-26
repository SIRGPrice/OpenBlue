# Third-Party Notices

OpenBlue is an independent product maintained by **SIRGPrice** and is
**not affiliated with, endorsed by, or sponsored by** any of the third-party
products listed below. OpenBlue does **not include, install, sublicense, or
redistribute** any of these products — it only communicates with their
documented public APIs or writes their documented configuration files.

---

## Claude Code / Anthropic API

- **Owner:** Anthropic, PBC
- **Website:** https://anthropic.com
- **Relationship:** OpenBlue writes documented configuration settings
  (environment variables and JSON files) that Claude Code reads at runtime.
  OpenBlue does not include, redistribute, or modify Claude Code.
- **User obligation:** You must obtain Claude Code separately from Anthropic
  and comply with Anthropic's Terms of Service, Acceptable Use Policy, and
  any applicable subscription requirements.

## LM Studio

- **Owner:** LM Studio / Element Labs, Inc.
- **Website:** https://lmstudio.ai
- **Relationship:** OpenBlue communicates with LM Studio's local HTTP API to
  list, load, unload, and manage models. OpenBlue does not include or
  redistribute LM Studio.
- **User obligation:** You must install LM Studio separately and comply with
  its license terms.

## Ollama

- **Owner:** Ollama, Inc.
- **Website:** https://ollama.com
- **Relationship:** OpenBlue communicates with Ollama's local HTTP API to
  list, pull, load, unload, and delete models. OpenBlue does not include or
  redistribute Ollama.
- **User obligation:** You must install Ollama separately and comply with
  its license terms.

## Visual Studio Code

- **Owner:** Microsoft Corporation
- **Website:** https://code.visualstudio.com
- **Relationship:** OpenBlue is a VS Code extension and consumes the public
  VS Code Extension API. OpenBlue does not include or redistribute VS Code.

## GitHub Copilot

- **Owner:** Microsoft Corporation / GitHub, Inc.
- **Website:** https://github.com/features/copilot
- **Relationship:** OpenBlue registers local models with the VS Code
  Language Model Chat API so that GitHub Copilot Chat can list and use them.
  OpenBlue does not include or redistribute GitHub Copilot.

## Hugging Face

- **Owner:** Hugging Face, Inc.
- **Website:** https://huggingface.co
- **Relationship:** When You explicitly browse or download GGUF models, the
  underlying LM Studio backend communicates with Hugging Face. OpenBlue
  itself does not host, mirror, or redistribute any model.

---

## Trademarks

"Claude", "Claude Code", "Sonnet", "Haiku", "Opus", and "Anthropic" are
trademarks or registered trademarks of Anthropic, PBC.

"LM Studio" is a trademark of LM Studio / Element Labs, Inc.

"Ollama" is a trademark of Ollama, Inc.

"Visual Studio Code", "VS Code", and "GitHub Copilot" are trademarks of
Microsoft Corporation.

"Hugging Face" is a trademark of Hugging Face, Inc.

All other product names, logos, and brands are the property of their
respective owners. Any use of these names in OpenBlue or its documentation
is solely for compatibility identification purposes and does not imply
affiliation, endorsement, or sponsorship.
