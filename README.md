# PDF-Extraction
This Python script extracts text, images, and tables from a PDF file, organizing the extracted content into designated subdirectories for each file type. It then creates a folder named after the original PDF and stores all the extracted files within it. Finally, once the extraction process is complete, the script places the original PDF file into the newly created folder.

You can specify a character limit to split PDFs into multiple text files. Additionally, you can designate a default folder location to process all PDFs within that directory.
<BR><BR>
<img src = "https://github.com/ayeruntech/personal/blob/fa7e274c67c3946f6b4e55dfbbbf99eb1e2f80e7/PDF%20ExtractorPDF/Extractor.png">
<BR><BR>
Installation:
  - Install required libraries: pdf2image, pytesseract, Pillow, PyMuPDF, tabula-py, PyPDF2
      - ```pip install pandas pdf2image pytesseract Pillow PyMuPDF tabula-py PyPDF2```
      - <a href= "https://github.com/UB-Mannheim/tesseract/wiki">pytesseract download link</a>
      - ```pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe' ```

How to use:
  - ```cd 'path to where the script is' ```
  - ``` python PDFExtractor.py' ```

