# ansible-role-shell

**OBSOLET -> merged intohttps://github.com/Allaman/ansible-role-dotfiles**

This roles configures my preferred settings for working with the shell on Linux based systems.

- Install kubectl-aliases
- Install zsh-autosuggestions
- Install fast-syntax-highlightning
- Install zsh-completions
- Install Powerlevel10k
- Install Tmux tpm

This works best with my [dotfiles](https://github.com/Allaman/dotfiles) and my [ansible role](https://github.com/Allaman/ansible-role-dotfiles)

## Test

Run `molecule test` to test this role via Docker

## Requirements

## Role Variables

No variables

## Dependencies

N/A

## Example Playbook

```
---
- name: Playbook
  hosts: localhost
  connection: local
  roles:
    - ansible-role-shell
```

## License

MIT
