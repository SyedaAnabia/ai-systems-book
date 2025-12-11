# AI Systems Book
Comprehensive textbook for AI practitioners: Qwen models, multimodal AI, and practical AI systems deployment.

[![Deploy to GitHub Pages](https://github.com/Ameen-Alam/ai-systems-book/workflows/Deploy%20to%20GitHub%20Pages/badge.svg)](https://github.com/Ameen-Alam/ai-systems-book/actions)
[![Build Validation](https://github.com/Ameen-Alam/ai-systems-book/workflows/Build%20Validation/badge.svg)](https://github.com/Ameen-Alam/ai-systems-book/actions)

## Overview
This textbook provides hands-on training for building AI systems using:

- **Qwen Models**: Foundation models, fine-tuning, and deployment
- **Multimodal AI**: Vision-language models and cross-modal learning
- **AI Systems**: Architecture, optimization, and production deployment
- **Practical Applications**: Real-world case studies and implementations

**Target Audience**: AI practitioners, ML engineers, and developers with Python programming knowledge.

## Course Structure
| Module | Weeks | Focus |
|--------|-------|-------|
| Introduction | 1-2 | AI Systems Foundations |
| Module 1: Qwen Fundamentals | 3-5 | Model Architecture, Training, Inference |
| Module 2: Multimodal AI | 6-8 | Vision-Language Models, Cross-Modal Learning |
| Module 3: AI Systems Design | 9-11 | Scalability, Optimization, MLOps |
| Module 4: Advanced Applications | 12-13 | RAG, Agents, Production Deployment |
| Capstone | Week 14 | End-to-End AI System Project |

## Hardware Requirements
Choose one of three configurations:

1. **Local Workstation**: RTX 3060+ GPU, 16GB+ RAM, Ubuntu 22.04/Windows 11
2. **Cloud-Based**: AWS/Azure/GCP with GPU instances
3. **Lightweight Setup**: CPU-only with quantized models

## Quick Start
```bash
# Clone the repository
git clone https://github.com/Ameen-Alam/ai-systems-book.git
cd ai-systems-book

# Install dependencies
npm install

# Start development server
npm start

# Open http://localhost:3000
```

For detailed setup instructions, see the [Quickstart Guide](./docs/setup/quickstart.md).

## Documentation Site
This project uses Docusaurus 3 with:

- Dashboard-style homepage with module cards
- Nested sidebar with collapsible categories
- Hybrid search (Algolia + Flexsearch)
- Custom metadata for chapter prerequisites and learning objectives
- GitHub Actions CI/CD with quality gates

## Project Structure
```
ai-systems-book/
├── docs/                   # Main content
│   ├── intro.md
│   ├── setup/              # Installation guides
│   ├── module-1-qwen/      # Qwen fundamentals
│   ├── module-2-multimodal/     # Multimodal AI
│   ├── module-3-systems/   # AI systems design
│   ├── module-4-advanced/  # Advanced applications
│   ├── capstone/
│   └── references/         # Glossary, APIs, troubleshooting
├── src/                    # Custom React components
│   ├── components/
│   └── pages/index.tsx     # Dashboard homepage
├── specs/                  # Feature specifications
│   └── 001-book-master-plan/
│       ├── spec.md
│       ├── plan.md
│       ├── tasks.md
│       └── contracts/      # JSON Schema for validation
└── .github/workflows/      # CI/CD pipelines
```

## Contributing
We welcome contributions! Please see the [Quickstart Guide](./docs/setup/quickstart.md) for:

- Development setup
- Creating new chapters
- Running quality checks
- Metadata validation

## Quality Gates
All PRs must pass:

- ✅ Build with 0 errors/warnings
- ✅ Link validation (0 broken links)
- ✅ Lighthouse scores: Performance ≥90, Accessibility ≥95, SEO ≥95
- ✅ Chapter metadata validation against JSON Schema

## Specification-Driven Development
This project follows Spec-Driven Development (SDD) using Spec-Kit Plus:

- **Constitution**: Core principles in `.specify/memory/constitution.md`
- **Specifications**: Feature specs in `specs/001-book-master-plan/spec.md`
- **Planning**: Implementation plan in `specs/001-book-master-plan/plan.md`
- **Tasks**: Breakdown in `specs/001-book-master-plan/tasks.md`
- **History**: Prompt History Records in `history/prompts/`

## Technology Stack
- **Documentation**: Docusaurus 3.x
- **Language**: TypeScript 5.x
- **UI**: React 18.x
- **Build Tools**: Node.js 18+
- **Search**: Algolia DocSearch + Flexsearch
- **CI/CD**: GitHub Actions
- **Deployment**: GitHub Pages
- **AI Assistant**: Claude Code

## Key Topics Covered

### Qwen Models
- Model architecture and variants
- Fine-tuning techniques
- Inference optimization
- Quantization and deployment

### Multimodal AI
- Vision-language understanding
- Cross-modal alignment
- Multimodal fusion strategies
- Real-world applications

### AI Systems
- Scalable architecture design
- Model serving and optimization
- MLOps best practices
- Monitoring and maintenance

### Advanced Applications
- Retrieval-Augmented Generation (RAG)
- AI agents and autonomous systems
- Production deployment strategies
- Case studies and implementations

## Roadmap
- ✅ Week 1-2: Introduction chapters
- 🔄 Week 3-5: Qwen fundamentals module
- ⏳ Week 6-8: Multimodal AI module
- ⏳ Week 9-11: AI systems design module
- ⏳ Week 12-13: Advanced applications module
- ⏳ Capstone project guide
- ⏳ Assessment rubrics
- ⏳ Video tutorials
- ⏳ Interactive code examples

## License
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## Acknowledgments
- Built with [Docusaurus](https://docusaurus.io/) by Meta
- Developed using Claude Code AI Assistant
- Following Spec-Kit Plus methodology
- Inspired by industry best practices in AI education
- Powered by Qwen models from Alibaba Cloud



---

**Built with Claude Code** • **Powered by Spec-Driven Development**
# Deployment test
