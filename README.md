PDF Table Extractor:

This Python script extracts table content from PDF files using the pdfplumber library, and then aligns the extracted tables into a structured format using regular expressions and namedtuple.

How it Works:-
    1. The script first uses pdfplumber to extract text content from the PDF file.
    2. It then identifies table content using regular expressions to match table patterns.
    3. Once tables are identified, the script aligns the data into a structured format using namedtuple.
