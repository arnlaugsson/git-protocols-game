# Git Courier — SSH vs HTTPS

An interactive browser-based game that teaches you how Git protocols actually work. Play through concept cards and quizzes to build a solid mental model of SSH, HTTPS, and the GitHub CLI.

**[Play it live →](https://arnlaugsson.github.io/git-protocols-game/)**

## What you'll learn

- How SSH key authentication works (and why your private key never leaves your machine)
- Why HTTPS with a token is safe despite "sending credentials over the wire"
- When to use SSH vs HTTPS (spoiler: CI/CD has a clear winner)
- How `gh auth login` works under the hood
- The difference between git transport layers and workflow tools like `gh`

## Topics covered

| Round | Type | Subject |
|-------|------|---------|
| 1 | Concept | SSH key pairs & challenge-response auth |
| 2 | Quiz | SSH basics |
| 3 | Concept | HTTPS & TLS handshake |
| 4 | Quiz | HTTPS & token security |
| 5 | Sort game | SSH vs HTTPS properties |
| 6–7 | Concept + Quiz | CI/CD & firewall considerations |
| 8–9 | Concept + Quiz | How `gh` CLI uses OAuth |
| 10 | Quiz | Putting it all together |

## Running locally

Just open `index.html` in a browser — no build step, no dependencies.

```bash
open index.html
```

## Deploying

Hosted on GitHub Pages from the `main` branch root. Any push to `main` updates the live site.
