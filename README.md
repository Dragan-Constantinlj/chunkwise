# chunkwise

Minimal RAG over a folder of markdown notes, no vector DB

Small but I use it weekly.

## Features

- Chunk markdown with overlap, keep source paths
- Swap in any LLM for the answer step
- Prints sources with scores for transparency
- TF-IDF retrieval: zero external services needed

## How to use

```bash
python rag.py ./notes "how do I rotate logs?"
```

## Install

```bash
pip install -r requirements.txt
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── dependabot.yml
│   └── pull_request_template.md
├── data/
│   └── sample.md
├── docs/
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── rag.py
└── requirements.txt
```

## Acknowledgments

- README structure inspired by popular OSS templates
- Thanks to everyone opening issues with ideas

## License

MIT - see [LICENSE](LICENSE).
