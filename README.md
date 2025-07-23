# 🚀 25x Agentic Calls

> **Maximize your AI agent interactions for the same price as Cursor and GitHub Copilot**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://opensource.org/)

## 🎯 Overview

25x Agentic Calls is an innovative open-source project designed to dramatically increase the number of AI agent interactions you can have while maintaining the same pricing structure as popular AI coding assistants like Cursor and GitHub Copilot.

## ✨ Features

- **📈 25x More Agent Calls**: Optimize your AI interactions to get maximum value
- **💰 Cost-Effective**: Same pricing as Cursor/GitHub Copilot, but with significantly more interactions
- **🔄 Interactive Loop**: Continuous task execution with user feedback
- **🛠 Easy Setup**: Simple Python script to get started
- **📝 Task Management**: Structured approach to handling multiple tasks
- **🎮 User-Friendly**: Interactive prompt system for seamless operation

## 🚀 Quick Start

### Prerequisites

- Python 3.8 or higher
- Terminal/Command Line access

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/devvrat-hans/25x-agentic-calls.git
   cd 25x-agentic-calls
   ```

2. **Verify the setup**
   ```bash
   python userinput.py
   ```

3. **Start using the interactive system**
   - Enter your tasks when prompted
   - Type `stop` to exit the loop

## 📖 How It Works

The system implements an interactive task loop that:

1. **Checks for `userinput.py`** in the root directory
2. **Executes assigned tasks** based on the workflow defined in `rules.md`
3. **Prompts for user input** through the terminal
4. **Processes feedback** and continues with the next set of tasks
5. **Reviews `rules.md`** after each task completion (mandatory step)
6. **Repeats the cycle** until user decides to stop

### Core Files

- **`userinput.py`**: Main interaction script
- **`rules.md`**: Workflow and task execution rules (must be reviewed after each task)
- **`prompts.txt`**: Task definitions and instructions with mandatory rule review pattern

## 🔧 Usage

### Basic Usage

```bash
python userinput.py
```

When prompted, enter your task or command. The system will:
- Process your input
- Execute the relevant tasks
- Ask for your next input
- Continue until you type `stop`

### Example Workflow

```
prompt: Create a new feature for user authentication. Also go through the rules.md file once you complete the assigned tasks.
[System processes the task and reviews rules.md]

prompt: Add error handling to the authentication. Also go through the rules.md file once you complete the assigned tasks.
[System processes the task and reviews rules.md]

prompt: stop
[System terminates]
```

**Note**: The phrase "Also go through the rules.md file once you complete the assigned tasks." is mandatory for proper workflow execution as defined in `prompts.txt`.

## 📋 Task System

The project includes a robust task management system defined in `prompts.txt`:

- **Task 1-11**: Each task includes reviewing `rules.md` after completion
- **Automated Flow**: Tasks are executed in sequence with user feedback
- **Flexible Input**: Users can modify tasks or add new ones dynamically

### Important: Task Completion Pattern

When working with the prompts from `prompts.txt`, **always ensure** that after completing any task, you include the following line:

```
Also go through the rules.md file once you complete the assigned tasks.
```

This is crucial for maintaining the workflow integrity. For example:
- **Task 1**: [Your task description] → Also go through the rules.md file once you complete the assigned tasks.
- **Task 2**: [Your task description] → Also go through the rules.md file once you complete the assigned tasks.
- And so on...

This pattern ensures that the system follows the proper workflow defined in `rules.md` and maintains consistency across all task executions.

### Prompts.txt Structure

The `prompts.txt` file contains 11 tasks, each following this exact pattern:
```
Task 1. Also go through the rules.md file once you complete the assigned tasks.
Task 2. Also go through the rules.md file once you complete the assigned tasks.
...
Task 11. Also go through the rules.md file once you complete the assigned tasks.
```

When creating your own tasks or modifying existing ones, **always maintain this pattern** to ensure proper system operation.

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add amazing feature'`)
4. **Push to the branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request**

### Development Guidelines

- Follow Python PEP 8 style guidelines
- Add comments for complex logic
- Update documentation for new features
- Test your changes thoroughly

## 📊 Performance

- **Efficiency**: 25x more agent calls compared to traditional methods
- **Cost Optimization**: Maintains same pricing structure as major AI assistants
- **Scalability**: Handles multiple concurrent tasks
- **Reliability**: Robust error handling and recovery

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by the need for cost-effective AI agent interactions
- Built for the open-source community
- Designed to democratize access to powerful AI tools

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/devvrat-hans/25x-agentic-calls/issues)
- **Discussions**: [GitHub Discussions](https://github.com/devvrat-hans/25x-agentic-calls/discussions)
- **Email**: [Contact the maintainer](mailto:devvrat.coding@gmail.com)

## 🗺 Roadmap

- [ ] Initial release with basic functionality
- [ ] Multiple AI provider support
- [ ] Integration with popular IDEs

---

**Made with ❤️ by [Devvrat Hans](https://github.com/devvrat-hans)**

*Star ⭐ this repository if you find it helpful!*