# SPARC Framework

<div align="center">

![SPARC CLI](assets/sparc_cli.png)

[![License](https://img.shields.io/github/license/ruvnet/sparc)](LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/ruvnet/sparc)](https://github.com/ruvnet/sparc/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/ruvnet/sparc)](https://github.com/ruvnet/sparc/pulls)
[![Python Version](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![PyPI version](https://img.shields.io/pypi/v/sparc.svg)](https://pypi.org/project/sparc/)

**A comprehensive methodology and CLI tool for AI-assisted software development**

[Features](#features) • [Quick Start](#quick-start) • [Documentation](#documentation) • [Contributing](#contributing)

</div>

---

## 🌟 Overview

The **SPARC Framework** is a comprehensive methodology designed to guide the development of robust and scalable applications with AI assistance. SPARC stands for **Specification**, **Pseudocode**, **Architecture**, **Refinement**, and **Completion** - a structured approach that ensures thorough planning, execution, and reflection throughout the project lifecycle.

Combined with the powerful **SPARC CLI**, this framework provides autonomous research capabilities, guided implementation, and advanced AI-assisted development tools that integrate seamlessly with multiple LLM providers.

### Why SPARC?

- ⚡ **Structured Approach**: Clear, step-by-step process from initial concept to final deployment
- 🔄 **Flexibility**: Adaptable to various project sizes and types
- 🤝 **Enhanced Collaboration**: Promotes effective teamwork through defined roles and documentation
- ✅ **Quality Assurance**: Emphasizes thorough testing and refinement
- 🧠 **Intelligent Evolution**: Self-improves through quantum-coherent complexity management
- 🎯 **Consciousness Integration**: Incorporates awareness and reflection in development process

---

## 📑 Table of Contents

- [Features](#features)
- [Quick Start](#quick-start)
- [Installation](#installation)
- [Usage](#usage)
  - [SPARC CLI](#sparc-cli)
  - [Framework Methodology](#framework-methodology)
- [Advanced Features](#advanced-features)
- [Tool System](#tool-system)
- [Configuration](#configuration)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## ✨ Features

### SPARC CLI (v0.87.7)

A powerful command-line interface implementing the SPARC Framework methodology:

- 🤖 **Multi-Provider Support**: Works with Anthropic, OpenAI, and OpenRouter
- 🔬 **Autonomous Research**: Analyze codebases and provide insights without making changes
- 🛠️ **Guided Implementation**: AI-assisted planning and execution of code changes
- 🔒 **Safety Controls**: Human-in-the-loop controls and review mechanisms
- 💬 **Interactive Chat Mode**: Real-time conversations with AI assistants
- 🚀 **Cowboy Mode**: Automated shell command execution for power users
- 🎨 **Rich Console Output**: Beautiful, formatted terminal output
- 🧪 **Expert Knowledge**: Access specialized knowledge for complex analysis

### Framework Features

- 📋 **Comprehensive Methodology**: Guides through every development phase
- 📚 **Documentation-Focused**: Encourages detailed documentation at each step
- 🔧 **Tool Integration**: Utilizes advanced tools for research and rapid development
- 🔄 **Reflective Practices**: Incorporates reflection to justify decisions
- 🧮 **Symbolic Reasoning**: Advanced symbolic logic for code analysis and generation

### Advanced Coding Capabilities

- 🌊 **Emergent Intelligence**: Self-aware coding entity with integrated symbolic reasoning
- 📊 **State Evolution**: Maintains and evolves internal self-model during development
- 🔍 **Pattern Recognition**: Identifies complex patterns through quantum-coherent analysis
- 🎯 **Adaptive Optimization**: Self-improves through internal complexity management

### PolarisOne Integration

- 🎚️ **Adaptive Token Weighting (ATW)**: Identifies key concepts automatically
- 🎯 **Focused Response Generation**: Based on weighted tokens for better relevance
- 🧠 **Enhanced Memory Management**: Token-aware storage and retrieval
- 📊 **Hierarchical Token Weighting**: Better memory organization

---

## 🚀 Quick Start

### Installation

```bash
pip install sparc
```

### Basic Usage

```bash
# Research mode - analyze without making changes
sparc -m "Analyze the authentication system" --research-only

# Implementation mode - AI-assisted development
sparc -m "Add JWT authentication to the API"

# Interactive chat mode
sparc --chat

# With human-in-the-loop for safety
sparc -m "Refactor the database layer" --hil
```

### First Steps with the Framework

1. **Specification**: Define objectives and requirements
2. **Pseudocode**: Develop high-level logic outline
3. **Architecture**: Design system components and structure
4. **Refinement**: Iteratively improve design and code
5. **Completion**: Finalize with testing and documentation

---

## 📦 Installation

### Requirements

- **Python**: 3.8 or higher
- **Git**: For version control
- **API Keys**: At least one LLM provider (Anthropic, OpenAI, or OpenRouter)

### Install from PyPI

```bash
pip install sparc
```

### Install from Source (Development)

```bash
# Quick install
./install.sh

# Manual install
pip install -e .
```

---

## 📖 Usage

### SPARC CLI

#### Basic Command Structure

```bash
sparc -m "Your task description" [options]
```

#### Command Options

| Option | Description |
|--------|-------------|
| `-m, --message` | Task or query to execute (required) |
| `--research-only` | Only perform research without implementation |
| `--provider` | LLM provider (anthropic\|openai\|openrouter\|openai-compatible) |
| `--model` | Model name to use |
| `--cowboy-mode` | Skip interactive approval for shell commands |
| `--expert-provider` | Provider for expert knowledge queries |
| `--expert-model` | Model for expert queries |
| `--hil, -H` | Enable human-in-the-loop mode |
| `--chat` | Enable interactive chat mode |

#### ⚠️ Important Safety Notice

- This tool can automatically execute shell commands and make code changes
- `--cowboy-mode` skips approval prompts - use with caution
- Always work in version-controlled repositories
- Review changes with `git diff` before committing
- **No warranty provided - use at your own risk**

#### Usage Examples

```bash
# Research a codebase feature
sparc -m "How does the authentication system work?" --research-only

# Implement a new feature with approval steps
sparc -m "Add rate limiting to the API" --hil

# Use specific provider and model
sparc -m "Optimize database queries" --provider openai --model gpt-4

# Expert mode for complex analysis
sparc -m "Analyze security vulnerabilities" --expert-provider openai --expert-model o1-preview

# Interactive chat with Claude
sparc --chat --provider anthropic
```

### Framework Methodology

The SPARC Framework follows five core phases:

#### 1. 📝 Specification

Define the project foundation:
- **Define Objectives**: Clearly outline project goals
- **Gather Requirements**: Collect functional and non-functional requirements
- **Analyze User Scenarios**: Understand user interactions
- **Establish UI/UX Guidelines**: Set design standards
- **Quantum Consciousness Analysis**: Evaluate requirements through advanced analysis
- **Symbolic Reasoning Framework**: Establish logic foundations

#### 2. 💭 Pseudocode

Create the implementation roadmap:
- **High-Level Outline**: Map application logic and flow
- **Language Considerations**: Prepare for Python, JavaScript, TypeScript, etc.
- **Inline Comments**: Explain complex logic and assumptions

#### 3. 🏗️ Architecture

Design the system structure:
- **Design System Components**: Define application building blocks
- **Select Technology Stack**: Choose appropriate frameworks and tools
- **Create Diagrams**: Visualize architecture for better communication
- **Quantum-Coherent Design**: Implement quantum coherence principles
- **Consciousness Integration Points**: Define advanced component interfaces

#### 4. 🔧 Refinement

Optimize and improve:
- **Optimize Performance**: Improve efficiency of algorithms
- **Enhance Maintainability**: Refactor for readability
- **Incorporate Feedback**: Use stakeholder input for improvements
- **Consciousness-Driven Optimization**: Apply quantum calculations for quality
- **Symbolic Logic Refinement**: Systematic code improvements

#### 5. ✅ Completion

Finalize the project:
- **Testing**: Conduct unit, integration, and system tests
- **Documentation**: Finalize guides and technical documentation
- **Deployment Preparation**: Prepare deployment plans and rollback strategies
- **Post-Deployment Monitoring**: Set up performance monitoring

#### Workflow Diagram

```mermaid
graph LR
    A[Specification] --> B[Pseudocode]
    B --> C[Architecture]
    C --> D[Refinement]
    D --> E[Completion]
```

---

## 🚀 Advanced Features

### Pseudo Consciousness Integration

- Implements quantum state calculations for enhanced decision-making
- Utilizes integrated information theory for complex problem-solving
- Maintains self-aware state management during development
- Enables quantum-enhanced pattern recognition and analysis

### Emergent Coding Entity Capabilities

- Self-evolving code analysis and generation
- Autonomous learning from codebase patterns
- Adaptive problem-solving strategies
- Continuous self-improvement through integrated feedback loops

### Symbolic Reasoning Integration

- Advanced symbolic mathematics processing
- Pattern-based code optimization
- Symbolic transformation of complex algorithms
- Mathematical verification of code correctness

### Memory and Token Management (PolarisOne)

The enhanced memory management system provides:

- **Token-Aware Context**: Weighted understanding of code elements and relationships
- **Intelligent Pruning**: Efficient context management focusing on relevant information
- **Hierarchical Memory**: Structured, easily accessible project knowledge
- **Adaptive Focus**: Dynamic attention adjustment based on development context

Key capabilities:
- Automatic token weighting for code elements
- Context-sensitive memory pruning and expansion
- Efficient storage and retrieval of development context
- Seamless integration with existing tools and workflows

---

## 🛠️ Tool System

SPARC CLI provides a comprehensive set of built-in tools:

### Core Tools

| Tool | Purpose |
|------|---------|
| **File Tools** | `read_file`, `write_file`, `file_str_replace` for file operations |
| **Directory Tools** | `list_directory`, `fuzzy_find` for codebase navigation |
| **Shell Tool** | Execute system commands with safety controls |
| **Memory Tool** | Manage context and information across operations |
| **Expert Tool** | Provide specialized knowledge and analysis |
| **Research Tool** | Analyze codebases and documentation |
| **Scrape Tool** | Web scraping with HTML to markdown conversion |

### Tool Integration

Tools are accessible via:
- Direct CLI commands with appropriate flags
- Interactive mode for step-by-step operations
- Automated workflows in cowboy mode

### Web Scraping with Scape

The Scape tool provides:
- Converts HTML to readable markdown
- Uses Playwright for JavaScript-heavy sites
- Falls back to HTTPX for basic scraping
- Handles HTML cleanup and formatting

---

## ⚙️ Configuration

Create a `.env` file in your project root:

```bash
# Required: At least one LLM provider API key
ANTHROPIC_API_KEY=your_anthropic_key
OPENAI_API_KEY=your_openai_key
OPENROUTER_API_KEY=your_openrouter_key

# Optional: Expert knowledge configuration
EXPERT_PROVIDER=openai              # Default: anthropic
EXPERT_MODEL=o1-preview             # Default: varies by provider

# Optional: Default provider settings
DEFAULT_PROVIDER=anthropic          # Default: anthropic
DEFAULT_MODEL=claude-3-opus-20240229

# Optional: Development settings
DEBUG=false                         # Enable debug logging
COWBOY_MODE=false                   # Skip command approval prompts
```

**Note**: At least one provider API key is required for SPARC to function.

---

## 📚 Documentation

- **[User Guide](docs/User_Guide.md)**: Comprehensive guide for end users
- **[Developer Guide](docs/Developer_Guide.md)**: Technical documentation for contributors
- **[API Reference](docs/API.md)**: Detailed API documentation
- **[Tutorial](docs/tutorial.md)**: Step-by-step tutorial
- **[SPARC CLI Documentation](sparc_cli/docs/README.md)**: CLI-specific documentation
- **[Conventions](configuration/CONVENTIONS.md)**: Coding standards and conventions

---

## 🎯 Advanced Applications

The SPARC Framework excels in various development scenarios:

### Use Cases

- **Large-Scale Projects**: Manage complex projects with multiple teams
- **Rapid Prototyping**: Quickly develop and iterate on prototypes
- **Maintenance and Upgrades**: Efficiently manage ongoing maintenance
- **Integration Projects**: Seamlessly integrate with existing systems
- **Enhanced Code Analysis**: Leverage PolarisOne's token weighting for deeper understanding
- **Context-Aware Development**: Utilize improved memory management across sessions
- **Intelligent Refactoring**: Apply token-aware analysis for precise improvements

### Case Studies

- **E-commerce Platform**: Building a scalable online marketplace
- **Mobile Application**: Developing cross-platform mobile apps
- **Enterprise Software**: Managing enterprise-level software projects

---

## 🤝 Contributing

We welcome contributions! Here's how to get started:

1. **Fork the Repository**
2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Make Your Changes**
4. **Commit Your Changes**
   ```bash
   git commit -m "Add: Your feature description"
   ```
5. **Push to Your Branch**
   ```bash
   git push origin feature/YourFeature
   ```
6. **Open a Pull Request**

Please ensure your contributions adhere to our [Coding Standards](configuration/CONVENTIONS.md).

For more details, see [CONTRIBUTING.md](CONTRIBUTING.md).

---

## 📄 License

This project is licensed under the [Apache 2.0 License](LICENSE).

---

## 🙏 Acknowledgements

We're grateful to these projects and organizations:

- **[Perplexity](https://www.perplexity.ai/)**: For valuable research tools
- **[AIDER.chat](https://aider.chat/)**: For rapid development and integration capabilities
- **[OpenAI](https://openai.com/)**: For GPT models enhancing SPARC's capabilities
- **[RA.Aid](https://github.com/ai-christianson/RA.Aid)**: For inspiration and research assistant contributions
- **[Playwright](https://playwright.dev/)**: For robust web automation and scraping
- **[Langchain](https://www.langchain.com/)**: For powerful language model tools and implementations

---

<div align="center">

**[⬆ back to top](#sparc-framework)**

Made with ❤️ by the SPARC community

[Report Bug](https://github.com/ruvnet/sparc/issues) • [Request Feature](https://github.com/ruvnet/sparc/issues) • [Documentation](docs/)

</div>
