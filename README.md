# LLM Directive - Option B (More Capable)

Extends A with JSON templates and installer. Now with end-to-end workflow for new projects (NL + IR placeholders).

Latest: web3.py 7.14.0, LangChain 1.1.0, n8n 1.121.2, Ollama 0.13.1, pytest 9.0.1, shellcheck 0.11.0, markdownlint-cli2 0.18.1

## Instructions
- **Download**: Grab repo.
- **Auto-Setup**: Run ./installer.sh (Ollama + model).
- **Manual**: See setup-manual.txt.
- **Usage**: Bake prompt, use templates for flows (e.g., parse JSON in scripts). For new projects: Input "create web app workflow" → Get full pipeline + deploy automation.
- **Ollama**: Custom model ready.
- **Tests**: pip install pytest==9.0.1; pytest
- **Linters**: Install shellcheck (brew install shellcheck or apt install shellcheck); shellcheck *.sh
  Install markdownlint-cli2 (npm install -g markdownlint-cli2@0.18.1); markdownlint-cli2 "*.md"
- **Warnings**: Sandbox, auth tasks, avoid illegals.

Fun: Red-team templates for prompt attacks!
