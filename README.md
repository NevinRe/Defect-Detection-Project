# Defect-Detection-Project
Car Part Defect Detection Model
An AI-powered computer vision system to automatically identify manufacturing defects on car parts in real-time.

This project utilizes a YOLOv8 object detection model to find, classify, and locate common defects like cracks, dents, and scratches on manufactured components. It is designed to be integrated into a quality control pipeline to increase inspection speed, consistency, and accuracy.

(Replace the link above with a GIF or screenshot of your model in action)

📝 Overview
Manual quality control in manufacturing is often slow, subjective, and prone to human error, leading to increased costs and potential safety risks. This project aims to solve that problem by providing an automated, reliable, and data-driven solution. The model analyzes an image or video feed of a car part and provides an instant PASS/FAIL verdict, highlighting any defects it finds.

✨ Key Features
Defect Detection: Identifies multiple classes of defects (e.g., Cracks, Dents, Scratches).

Bounding Box Localization: Pinpoints the exact location of each defect on the part.

Confidence Scoring: Provides a confidence level for each detection to gauge certainty.

Real-Time Processing: Capable of analyzing live video streams from a production line.

PASS/FAIL Logic: Automatically provides a final verdict for each part based on the presence of defects.

🚀 Tech Stack
Python 3.8+

PyTorch

YOLOv8

OpenCV

NumPy

