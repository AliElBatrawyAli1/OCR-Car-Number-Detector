This project is an OCR system that detects and highlights text in images. Users can upload an image, and the application identifies text using EasyOCR, draws green bounding boxes around detected text, and displays the extracted text along with confidence scores.

How It Works:
Text Detection: EasyOCR detects text, returning its position and confidence level.
Bounding Boxes: Each detected text is highlighted with a green box.
Display Results: The annotated image and extracted text with confidence scores are shown to the user.
Technologies Used:
Gradio: Web interface
EasyOCR: Text recognition
OpenCV & NumPy: Image processing
