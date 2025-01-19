# Word to PDF convertor
This python code converts a word document to a pdf ousing docx2pdf module.

## Usage example
This will automatically create a 1.pdf file in the same directory.
```python
from docx2pdf import convert

# Convert a Word document to PDF
convert("1.docx")
```
If we want to specify a different output directory or filename, we can pass the output path as a second argument:
```python
from docx2pdf import convert
convert("1.docx", "output_folder/1.pdf")
```
