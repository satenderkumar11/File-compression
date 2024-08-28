# File Compression System Using Huffman Encoding

## Overview

This repository contains a Java-based implementation of a file compression system utilizing Huffman encoding. Huffman encoding is a lossless data compression algorithm that is widely used for reducing the size of data files without any loss of information. You can also decompress the file using this app into its original form. This app also has some additional features such as: Given a string of alphabetic characters, you can compress the size of its bit sequence to obtain a binary sequence that has size significantly lesser than the original, this new sequence can then be sent through a network or saved in file so that it can be decompressed whenever required.

## Features

- **Huffman Encoding**: Implements Huffman Tree and Encoding algorithms to compress files efficiently.
- **User Interface**: A simple GUI (`EncoderGUI.java`) to interact with the system.
- **Custom Data Structures**: Includes implementations of various data structures such as singly linked lists, priority queues, and more, tailored for the compression tasks.
- **Progress Tracking**: Visual progress bar to monitor the compression/decompression process.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher.
- A Java IDE (e.g., IntelliJ IDEA, Eclipse) or any text editor with Java support.

### Installation

1. Clone the repository to your local machine using:
   ```bash
   git clone https://github.com/ammarlodhi255/file-compression-system.git
   ```
   
2. Navigate to the project directory:
   ```bash
   cd file-compression-system/src
   ```

3. Open the project in your preferred Java IDE.

### Usage

1. **Compile the project**: Ensure all `.java` files are compiled. Most IDEs handle this automatically.
2. **Run the GUI**:
   - Execute `EncoderGUI.java` to launch the user interface.
   - Use the provided options to compress or decompress files.
3. **Command Line Interface (CLI)**:
   - If you prefer a non-GUI approach, modify the `HuffCompression.java` to take input from the command line.

### Example

- Compress a text file:
  1. Open the GUI.
  2. Select the file you want to compress.
  3. Click on the "Compress" button and specify the destination for the compressed file.

- Decompress a file:
  1. Open the GUI.
  2. Select the compressed file.
  3. Click on the "Decompress" button and choose where to save the decompressed file.


