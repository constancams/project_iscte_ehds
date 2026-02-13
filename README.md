!pip install pymupdf pillow pytesseract

pytesseract.pytesseract.tesseract_cmd = r"C:\Program Files\Tesseract-OCR\tesseract.exe"

import fitz
from PIL import Image
import pytesseract

print("PyMuPDF OK")
print("Pillow OK")
print("Tesseract version:", pytesseract.get_tesseract_version())

import re
import json
from pathlib import Path
import pandas as pd

import fitz  # PyMuPDF
from PIL import Image
import pytesseract
