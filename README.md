# OCR-with-Tesseract-example


Tesseract OCR: Extracting texts from images

This is a notebook that uses pytesseract to do OCR (Optical Character Recognition). It iterates over a parent directory, going inside of every subfolder and processing every file contained in each subfolder.

For each image file (jpg, png) that is processed, it outputs a copy of the image with all bounding boxes drawn, and also a .txt file with all text detected by tesseract, and saves both files in a directory you choose, with the same filename as the source image.

For each pdf that is processed, it outputs the detected and extracted text from all pages, concatenated in a single .txt file. At the moment it does not output the drawn bounding boxes for each page so it doesn't mess up the directory in case of pdf files with thousands of pages.

Obs.: Obviously, you will need to change your paths for this to work on your files.
