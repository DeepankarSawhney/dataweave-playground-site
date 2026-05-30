# DataWeave Playground — Site

This repository hosts the **GitHub Pages landing page** for the [DataWeave Playground](https://hub.docker.com/r/deepankar2810/dataweave-playground) Docker image.

🌐 **Live site:** https://deepankarsawhney.github.io/dataweave-playground-site/

---

## What is the DataWeave Playground?

A self-hosted, Docker-based clone of the [MuleSoft DataWeave Playground](https://developer.mulesoft.com/learn/dataweave).  
Write DataWeave 2.0 transformation scripts, supply any input format, and see the output instantly — no MuleSoft account or internet connection required.

## Docker image

| | |
|---|---|
| **Image** | `deepankar2810/dataweave-playground` |
| **Docker Hub** | https://hub.docker.com/r/deepankar2810/dataweave-playground |
| **Latest tag** | `v1.0.11` / `latest` |
| **Platforms** | `linux/amd64`, `linux/arm64` (Apple Silicon) |

### Quick start

```bash
docker run -p 3000:3001 deepankar2810/dataweave-playground:latest
```

Then open **http://localhost:3000** in your browser.

## Features

- Monaco Editor (VS Code engine) with DataWeave syntax highlighting
- Three resizable panels: Script · Input · Output
- DW 2.11, 2.6, and 2.3 pre-installed; more downloadable on demand
- Multiple named inputs (mix JSON, XML, CSV in one transform)
- Context-aware autocomplete, import/export workspaces
- Six built-in example scripts
- Supports: JSON, XML, CSV, YAML, NDJSON, Plain Text, Java Properties

## Supported formats

`application/json` · `application/xml` · `application/csv` · `application/yaml` · `application/x-ndjson` · `text/plain` · `text/x-java-properties`

## Bugs & feature requests

Found an issue? [Open a bug report](https://github.com/DeepankarSawhney/dataweave-playground-site/issues/new?labels=bug&template=bug_report.md&title=%5BBUG%5D+)  
Have an idea? [Request a feature](https://github.com/DeepankarSawhney/dataweave-playground-site/issues/new?labels=enhancement&template=feature_request.md&title=%5BFEATURE%5D+)

## License

Apache 2.0
