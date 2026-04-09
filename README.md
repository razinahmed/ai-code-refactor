# AI Code Refactor

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![AI](https://img.shields.io/badge/AI-Powered-purple)
![License](https://img.shields.io/badge/License-MIT-green)

An AI-powered code refactoring tool that analyzes source code and suggests intelligent improvements. Leverages large language models to identify code smells, simplify complex logic, and produce cleaner, more maintainable code.

---

## Features

- **Automated Refactoring** -- Detects anti-patterns and restructures code for clarity and performance
- **Multi-Language Support** -- Processes Python, JavaScript, TypeScript, and more
- **AI-Driven Suggestions** -- Uses LLM-based analysis to propose meaningful improvements
- **Batch Processing** -- Refactor entire directories or individual files
- **Safe Transformations** -- Preserves functionality while improving code quality
- **Configurable Rules** -- Customize which refactoring patterns to apply

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Python 3.9+ | Core runtime |
| OpenAI / LLM API | AI inference engine |
| AST Module | Code parsing and analysis |
| Makefile | Build and test automation |

---

## Quick Start

```bash
# Clone the repository
git clone https://github.com/razinahmed/ai-code-refactor.git
cd ai-code-refactor

# Install dependencies
pip install -r requirements.txt

# Run the refactoring engine
python core/ai_worker.py --input <source_file>
```

---

## Project Structure

```
ai-code-refactor/
├── core/
│   └── ai_worker.py       # Main AI processing engine
├── Makefile                # Build and test commands
├── LICENSE                 # MIT License
├── SECURITY.md             # Security policy
└── README.md
```

---

## Usage

```bash
# Build the project
make build

# Run tests
make test
```

---

## Contributing

1. Fork the repository
2. Create a feature branch -- `git checkout -b feature/your-feature`
3. Commit your changes -- `git commit -m "feat: add new feature"`
4. Push and open a Pull Request

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

**Built by [Razin Ahmed](https://github.com/razinahmed)**
