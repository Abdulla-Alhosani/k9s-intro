# k9s Intro

A modern, single-page website introducing [k9s](https://github.com/derailed/k9s) — the popular terminal UI for Kubernetes.

## Live Demo

Open `index.html` in a browser, or host it on GitHub Pages:

1. Go to **Settings → Pages**
2. Set source to **Deploy from a branch** → `main` / `/ (root)`
3. Your site will be available at `https://abdulla-alhosani.github.io/k9s-intro/`

## About k9s

k9s provides a terminal-based UI to interact with your Kubernetes clusters. It simplifies navigating, observing, and managing your applications in a production-grade way.

- Real-time resource views
- Powerful keyboard shortcuts
- Logs, describe, exec, port-forward
- Multi-cluster & multi-namespace support
- Highly customizable with plugins and skins

## Install k9s

```bash
brew install derailed/k9s/k9s
# or
go install github.com/derailed/k9s@latest
```

Then run:

```bash
k9s
```

---

Unofficial introduction site. All credit goes to the k9s maintainers.
