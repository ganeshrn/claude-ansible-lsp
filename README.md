# ansible-lsp

Ansible language server for Claude Code, providing code intelligence features like diagnostics, auto-completion, hover documentation, and go-to-definition for Ansible playbooks and roles.

## Supported Extensions

`.yml`, `.yaml`

## Features

- Real-time validation via ansible-lint (falls back to `ansible --syntax-check`)
- Smart auto-completion for plays, blocks, tasks, and module options
- Hover documentation for Ansible keywords, modules, and module options
- Go-to-definition for module source code
- Semantic highlighting for Ansible keywords, modules, and Jinja expressions

## Installation

Install the Ansible Language Server globally via npm:

```bash
npm install -g @ansible/ansible-language-server
```

### Requirements

- Ansible 2.9+
- ansible-lint (recommended, for full validation support)
- yamllint (optional)

## More Information

- [@ansible/ansible-language-server on npm](https://www.npmjs.com/package/@ansible/ansible-language-server)
- [Ansible Language Server documentation](https://github.com/ansible/vscode-ansible/blob/main/docs/als/README.md)
- [GitHub Repository](https://github.com/ansible/vscode-ansible)
