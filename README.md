# Advanced PDF Compressor

An advanced PDF compression tool built with React that uses enhanced Huffman coding combined with Run-Length Encoding (RLE) preprocessing to efficiently compress PDF files into a custom `.huf` format and decompress them back to the original PDF. This project offers a user-friendly interface with drag-and-drop support, real-time progress updates, and detailed compression statistics.

---

## Features

- Compress PDF files using enhanced Huffman coding with RLE preprocessing for improved compression ratios.
- Decompress `.huf` files back to the original PDF format.
- Intuitive drag-and-drop file upload and browse support.
- Real-time progress and status updates during compression and decompression.
- Detailed compression statistics including entropy, efficiency, unique bytes, and space saved.
- PDF-specific optimizations to boost compression performance.
- Team information modal showcasing project contributors.

---

## How to Use

1. **Compress PDF:**
   - Select the "Compress PDF" mode.
   - Upload or drag-and-drop a PDF file.
   - Click the "Compress" button to start compression.
   - Download the compressed `.huf` file once complete.

2. **Decompress .huf:**
   - Select the "Decompress .HUF" mode.
   - Upload or drag-and-drop a `.huf` file.
   - Click the "Decompress" button to restore the original PDF.
   - Download the decompressed PDF file.

---

## Team Information

This project was developed by **Team Compile-X**:

| Name               | Role        | Roll No    | Email                   |
|--------------------|-------------|------------|-------------------------|
| Srivatsa Jakhmola  | Team Lead   | 220212007  | sjakhmola27@gmail.com   |
| Vatsank Dabral     | Team Member | 220111037  | vasuvatsank@gmail.com   |
| Jeevan Singh Baura | Team Member | 22011292   | baurajeevan405@gmail.com|
| Ishan Rawat        | Team Member | 220111407  | ishanrawat104@gmail.com |

---

## How It Works

The compression process involves three main steps:

1. **Preprocessing:**  
   Run-Length Encoding (RLE) is applied to compress repeated byte sequences, optimizing the data before Huffman coding.

2. **Huffman Coding:**  
   An enhanced frequency analysis builds optimal binary codes, assigning shorter codes to more frequent bytes to minimize overall size.

3. **Optimization:**  
   Advanced bit packing and PDF-specific frequency boosts maximize compression efficiency.

During decompression, the process is reversed by rebuilding the Huffman tree and decoding the compressed data, followed by reversing the RLE preprocessing.

---

## Technologies Used

- React for building the user interface.
- Lucide React icons for UI elements.
- Vite as the build tool and development server.
- JavaScript (ES6+) for core compression and decompression logic.

---

## Installation and Running Instructions

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd huffman-encoding-main
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open your browser and navigate to the URL provided by Vite (usually `http://localhost:5173`).

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Developed by Team Compile-X | Computer Science Engineering
