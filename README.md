# 🔐 PDF Protection Tool Using Python

A simple and secure utility that allows users to **add password protection to any PDF file** using Python.  
This tool reads an existing PDF, encrypts it with a user-provided password, and saves a protected version — ensuring your confidential documents remain private.



## 🚀 Features

- 🔒 Add password protection to PDF files  
- 📄 Preserve all pages and content while securing the document  
- 🧰 Built using Python and the PyPDF2 library  
- ⚙️ Command-line based for quick and flexible usage  
- 🛡️ Includes user-friendly error handling  



## 📁 Project Structure
```
PDF-Protection-Tool/
│── protection.py
│── README.md
│── sample.pdf
```



## 🖥️ How It Works

The tool performs three main actions:

1. **Reads the original PDF**  
2. **Applies password-based encryption**  
3. **Saves a new secure PDF**  

Only users who know the password will be able to open the protected document.



## 🔧 Installation

Make sure Python is installed on your system, then install the required library:
```
pip install PyPDF2
```


## ▶️ Usage

Run the script from the terminal using:
```
python protection.py <input_pdf> <output_pdf> <password>
```
Example:
```
python protection.py myfile.pdf myfile_protected.pdf secure123
```

Your encrypted PDF is now ready to use.



## 📝 Requirements

- Python 3.x  
- PyPDF2 library  



## 🌟 Future Improvements

- GUI-based interface for easier user interaction  
- Bulk PDF encryption  
- PDF decryption support (where legally allowed)  
- Features like merging, splitting, and watermarking  
- Stronger encryption algorithms  







