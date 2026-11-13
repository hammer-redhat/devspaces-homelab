# Ansible Dev Spaces workspace

This Devfile uses the same pinned Ansible image and demo commands as the `ansible-devspaces-demo` Devfile. The Molecule and Ansible Navigator commands expect that demo repository at `/projects/ansible-devspaces-demo`.

Dev Spaces installs the Codex extension (`openai.chatgpt`) from its configured Open VSX registry using `.vscode/extensions.json`. The registry must provide the extension and the workspace must be able to reach it. Sign in to Codex from the editor after it starts. The extension is installed into the workspace editor; the upstream container image is not rebuilt.
