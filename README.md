# **How to Train RF-DETR Object Detection on a Custom Dataset**  

🚀 **Fine-tuning RF-DETR for Real-World Object Detection**  

RF-DETR is a cutting-edge transformer-based object detection model that outperforms traditional architectures like YOLO and DETR in both accuracy and adaptability. This repository provides a step-by-step guide to fine-tuning RF-DETR on a custom dataset.  

## 📌 **What You’ll Learn**  
- How to set up RF-DETR for training  
- Preparing a custom dataset for object detection  
- Fine-tuning RF-DETR for improved performance  
- Evaluating model performance on real-world datasets  

## 🔧 **Installation & Setup**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/muhammadrizwan11/How-to-Train-RF-DETR-Object-Detection-on-a-Custom-Dataset.git
   cd How-to-Train-RF-DETR-Object-Detection-on-a-Custom-Dataset
   ```  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Download the pretrained RF-DETR weights (if needed).  

## 🚀 **Training RF-DETR on Your Custom Dataset**  
Run the Jupyter Notebook to fine-tune RF-DETR:  
```bash
jupyter notebook Copy_of_how_to_finetune_rf_detr_on_detection_dataset.ipynb
```  

## 📊 **Model Performance**  
RF-DETR demonstrates state-of-the-art accuracy while maintaining real-time performance.  

| Model         | COCO mAP | Domain Adaptability | Speed (T4 GPU) |
|--------------|---------|-------------------|----------------|
| **RF-DETR-B** | 53.3    | **86.7**          | 6.0ms          |
| YOLOv8m      | 50.6    | 85.0              | 6.3ms          |
| YOLO11m      | 51.5    | 84.9              | **5.7ms**      |
| LW-DETR-M    | 52.5    | 84.0              | 6.0ms          |

📌 **Key Takeaway:** RF-DETR is the only model ranking #1 or #2 in all categories!  

## 🔗 **Resources**  
- RF-DETR Official Paper: *https://github.com/roboflow/rf-detr*  
- Roboflow Universe Dataset: *https://universe.roboflow.com/object-detection*  

## 🤝 **Contributing**  
Feel free to open issues or contribute improvements via pull requests.  

## 📢 **Let's Connect!**  
If you found this project helpful, give it a ⭐ and connect with me on **[LinkedIn](https://www.linkedin.com/in/datasciecnce/)**.  

