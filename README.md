# BWT Genomic Data Compression Web App

## 📌 Overview
This project implements a **Burrows–Wheeler Transform (BWT)** based **DNA sequence compression and decompression** system, optimized for genomic research data.  
It combines **BWT**, **Run-Length Encoding (RLE)**, and **Huffman Coding** to achieve efficient, lossless compression of large DNA datasets.  

The web-based system is designed for use in **academic, research, and low-infrastructure environments** where storage optimization is critical.

---

## ✨ Features
- **Upload DNA sequence files** (`.fasta`, `.txt`)
- **Compression pipeline**:  
  1. **BWT** (rearranges sequence for better compression)  
  2. **RLE** (compresses repeated runs of bases)  
  3. **Huffman Encoding** (minimizes bit representation)
- **Decompression**: Restores original DNA sequence with 100% accuracy
- **Download support** for compressed binary and code map
- **Optional AES encryption** for compressed output
- **Logs stored in SQLite** for usage tracking
- **Desktop app packaging** for offline use
- **GitHub integration** for version control

---

## 🧬 Example DNA Input
