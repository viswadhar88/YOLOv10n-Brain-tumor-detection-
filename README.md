# Brain Tumor Detection
 
YOLO-Based Deep Learning for Automated Brain Tumor Detection and Classification in MRI
Team: K CHARAN 22BCE1759
            K VISWADHAR 22BCE1950

About Brain Tumors and Detection
What is a Brain Tumor?
A brain tumor is an abnormal growth of cells within the brain or central spinal canal. Tumors can be benign (non-cancerous) or malignant (cancerous) and may originate in the brain (primary tumors) or spread from other parts of the body (secondary or metastatic tumors). Depending on their size, type, and location, brain tumors can interfere with vital brain functions, leading to symptoms like headaches, seizures, cognitive decline, and neurological deficits.
Importance of Early Detection
Early and accurate detection of brain tumors is critical for:
•	Timely treatment planning (surgery, chemotherapy, or radiotherapy)
•	Reducing mortality rates
•	Improving quality of life and survival rates
Traditionally, MRI scans (Magnetic Resonance Imaging) are used to visualize brain structures. However, manual interpretation by radiologists can be time-consuming, subjective, and prone to human error. Therefore, automated tumor detection using AI is emerging as a powerful tool to assist radiologists and improve diagnostic efficiency.
________________________________________
🤖 YOLO and Its Role in Tumor Detection
What is YOLO?
YOLO (You Only Look Once) is a state-of-the-art real-time object detection algorithm. Unlike traditional detectors that apply classification models in a sliding window fashion, YOLO frames object detection as a single regression problem and predicts bounding boxes and class probabilities directly from full images in one evaluation.
Why YOLO for Medical Imaging?
YOLO is particularly suited for brain tumor detection in MRI images due to:
•	Speed: Real-time detection allows for faster diagnosis.
•	Accuracy: High precision and recall in detecting complex tumor shapes.
•	End-to-end training: All parts of the model are trained simultaneously.
•	Localization and classification: It detects the tumor's location and identifies whether it's present or not.
YOLOv10: The Latest and Fastest
YOLOv10, released in 2024, introduces significant improvements:
•	Better performance with fewer parameters.
•	Improved accuracy on small objects, like early-stage tumors.
•	Efficient deployment on low-compute environments (e.g., edge devices in healthcare).
This project uses YOLOv10n, the nano version, optimized for speed and resource constraints while maintaining high detection accuracy—ideal for lightweight medical applications or deployment on embedded systems.

Architecture diagram
![alt text][architecture diagram]

[architecture diagram]: image.png


References

To access refernces [click here](https://drive.google.com/drive/folders/1D-YzYBjRMhMxMKBBkwV_EVmvGPjIrfrE?usp=drive_link)

Result
![alt text][result image]

[result image]: image-1.png

