# PDF-Extraction
This Python script extracts text, images, and tables from a PDF file, organizing the extracted content into designated subdirectories for each file type. It then creates a folder named after the original PDF and stores all the extracted files within it. Finally, once the extraction process is complete, the script places the original PDF file into the newly created folder.

Installation:
  - Install required libraries: pdf2image, pytesseract, Pillow, PyMuPDF, tabula-py, PyPDF2
  -   - pip install pandas pdf2image pytesseract Pillow PyMuPDF tabula-py PyPDF2
      - https://github.com/UB-Mannheim/tesseract/wiki
      - pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'

How to use:
  - cd 'path to where the script is'
  - python 'name of script'
