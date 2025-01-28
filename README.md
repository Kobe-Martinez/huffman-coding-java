# Transit Simulation

The Huffman Coding project is a Java-based implementation of the Huffman encoding algorithm for file compression and decompression. It processes text files to build Huffman trees based on character frequency, encodes them into compact binary formats, and decodes them back into the original text. This project demonstrates efficient file compression techniques while preserving data integrity.

This simulation is an excellent tool for understanding Huffman encoding, binary trees, and file handling in Java. It provides a practical demonstration of data compression techniques and is ideal for students and developers exploring computer science concepts.


## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Requirements](#requirements)
- [File Outputs](#file-outputs)
- [License](#license)
- [Important Note](#important-note)


## Features

- **Huffman Tree Construction**

  - Creates a Huffman tree based on the frequency of characters in a text file

- **Encoding**

   - Encodes text files into compact binary formats using Huffman codes

- **Decoding**

   - Decodes compressed binary files back into readable text

- **File Operations**

   - Reads and writes files efficiently using custom bitstring handling

- **Data Consistency**

   - Ensures accurate compression and decompression by preserving Huffman tree structure


## Usage

1. **Clone the Repository**
   
bash
   git clone https://github.com/Kobe-Martinez/huffman-coding-java.git


2. **Compile the Code**
   
bash
   javac huffman-coding-java


3. **Run the Program**

   - Use the main method to provide test cases for encoding and decoding operations.

    - Example:
       
        - Call `makeSortedList` to create frequency data from a text file
          
        - Build the Huffman tree with `makeTree`
        
        - Generate Huffman encodings with `makeEncodings`
        
        - Use `encodeFromArray` and `decode` for compression and decompression

## Code Structure

- **HuffmanCoding.java**
  
  - Core class containing methods for encoding, decoding, and Huffman tree construction

- **File Handling**
  
  - `writeBitString`: Writes compressed binary data to a file
    
  - `readBitString`: Reads binary data from a file

- **Tree Management**
  
  - Builds a Huffman tree based on character frequency
 
  - Traverses the tree to generate Huffman encodings 

- **Encoding and Decoding**
  
  - Uses Huffman codes to compress and decompress text files

## Requirements

- **Java**: Version 8 or higher

## File Outputs

- Encoded File: A compressed binary file with minimal size
  
- Decoded File: A text file identical to the original input

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Important Note

This project is designed for educational purposes to demonstrate Huffman encoding and decoding using Java. It highlights the practical application of binary trees in file compression and serves as a learning tool for algorithmic efficiency and file handling in computer science.
