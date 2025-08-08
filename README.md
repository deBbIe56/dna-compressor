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
AGCTTTTCATTCTGACTGCAACGGGCAATATGTCTCTGTGTGGATTAAAAAA
GAGTGTCTGATAGCAGCCTTCTGAACTGGTTACCTGCCGTGAGTAAATTAAA

yaml
Copy
Edit

---

## 🚀 Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/BWT-Genomic-Compression.git
cd BWT-Genomic-Compression
2. Create a virtual environment & install dependencies
bash
Copy
Edit
python -m venv venv
source venv/bin/activate      # On Mac/Linux
venv\Scripts\activate         # On Windows
pip install -r requirements.txt
3. Run the web app
bash
Copy
Edit
python app.py
Access in browser: http://127.0.0.1:5000

📂 Project Structure
csharp
Copy
Edit
BWT-Genomic-Compression/
│── static/               # CSS, JS, images
│── templates/            # HTML templates
│── uploads/              # Uploaded files
│── compressed/           # Compressed outputs
│── app.py                 # Flask backend
│── bwt.py                 # Burrows–Wheeler Transform functions
│── rle.py                 # Run-Length Encoding functions
│── huffman.py             # Huffman coding functions
│── requirements.txt       # Python dependencies
│── README.md              # Project documentation
🛠 Technologies Used
Python (Flask) – Backend

HTML, CSS, JavaScript – Frontend

SQLite – Database

PyCryptodome – AES encryption

Git & GitHub – Version control

📊 Compression Workflow
[Input DNA Sequence] → BWT → RLE → Huffman → Compressed Output

📜 License
This project is licensed under the MIT License – feel free to use and modify.

👩‍💻 Author
Your Name – deBbIe56
Project for Final Year Research: Burrows–Wheeler Transform for Compressing Genomic Data in Web-Based Systems
