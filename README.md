# 🛰️ Object Detection from Satellite Images

This project focuses on applying object detection techniques to satellite imagery for identifying and localizing specific targets. Using deep learning models, the notebook demonstrates the pipeline from image preprocessing to model inference on satellite-based data.

## 📌 Objective

To detect and classify objects from high-resolution satellite images using deep learning-based object detection frameworks.

## 📓 Project File

- **`Object Detection From Satellite Images.ipynb`**: A Jupyter Notebook containing all relevant code for loading images, running detection models, visualizing results, and analyzing outputs.

## 🛠️ Key Components

- **Image Preprocessing**: Resizing, normalization, and augmentation
- **Model Loading**: Pretrained object detection models (e.g., YOLO, Faster R-CNN)
- **Inference**: Running predictions on satellite imagery
- **Visualization**: Bounding box overlays on detected objects
- **Performance Metrics**: Precision, Recall, mAP (optional depending on the notebook's content)

## 🧪 Dependencies

Make sure to install the following libraries:

```bash
pip install opencv-python matplotlib torch torchvision
```



📂 Example Use
# Load image
img = cv2.imread('satellite_image.jpg')

# Run object detection
results = model(img)

# Display detected objects
results.show()


##📎 Future Improvements
Train on custom satellite datasets (e.g., DOTA, xView)

Fine-tune detection models

Incorporate geospatial metadata (e.g., bounding box in latitude/longitude)

Deploy as a web-based or API-based service

👨‍💻 Author
Hasin Md. Daiyan
Computer Science and Engineering
Ahsanullah University of Science and Technology
