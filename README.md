# Oral Vis FDI Tooth Detection using YOLO

This repository contains the code and configuration for detecting teeth and assigning FDI numbers using YOLOv8, implemented entirely in Google Colab.

---

## Environment

All dependencies are installed within the Colab notebook. The notebook installs the following packages:

- ultralytics
- opencv-python
- matplotlib
- numpy
- pillow

No local setup is required; just open the notebook in Colab.

---

## Running the Notebook

1. Open the Colab notebook: `OralVis_Assignment.ipynb`
2. Follow the cells in order:
   - Mount Google Drive (if using datasets or weights from Drive)
   - Install dependencies
   - Load the dataset
   - Train the model (optional)
   - Run inference on test images
3. Predicted images with bounding boxes and FDI numbers will be displayed and can also be saved to the `results/FDI_YOLO_results/content/runs` folder.

---

## Dataset


- Full dataset can be added by uploading images to Colab or mounting Google Drive.

---


