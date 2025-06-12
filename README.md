# Trento Documentation Site

This repository builds and publishes the Trento project's documentation site using [Antora](https://antora.org/).

The actual documentation content is maintained in [trento-project/docs](https://github.com/trento-project/docs) and included as a Git submodule or content source.

## 🛠️ How to Build the Documentation Site

### 1. Clone the Repository

```bash
git clone git@github.com:trento-project/docs-site.git
cd docs-site
```

### 1. Install Dependency

```bash
npm i -D -E antora
```

### 1. Build Antora page

```bash
npx antora --fetch antora-playbook.yml
```
