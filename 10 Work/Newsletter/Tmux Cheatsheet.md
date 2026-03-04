---
title: Tmux Cheatsheet
type:
  - reference
tags:
  - dev/tmux
---

## Session Management
| Command               | Action                      |
| :-------------------- | :-------------------------- |
| `tmux`                | Start new session           |
| `tmux new -s name`    | Start new named session     |
| `tmux ls`             | List sessions               |
| `tmux attach -t name` | Attach to session           |
| `Ctrl+b d`            | Detach from session         |
| `Ctrl+b s`            | List sessions (interactive) |
| `Ctrl+b $`            | Rename session              |

## Window Management
| Command    | Action             |
| :--------- | :----------------- |
| Ctrl+b c   | Create window      |
| Ctrl+b w   | List windows       |
| Ctrl+b n   | Next Window        |
| Ctrl+b p   | Previous Window    |
| Ctrl+b 0-9 | Switch to window # |
| Ctrl+b , | Rename window |
| Ctrl+b & | Kill window |

## 