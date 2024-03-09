# SanskritOCR
!sudo apt-get install tesseract-ocr
!pip install pytesseract
!pip install PyPDF2
!pip install pdf2image
!apt-get install -y poppler-utils

import pytesseract
from pdf2image import convert_from_path
import cv2
import pandas as pd
import numpy as np
import PyPDF2
import json
import os
from PIL import Image, ImageDraw, ImageFont
