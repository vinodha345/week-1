📂# week-1-Design Phase Summary

Project Name : REAL-TIME FABRIC CLASSIFICATION USING ONNX and COMPUTER VISION
 
🧩 Problem Statement

The fashion industry significantly contributes to environmental pollution because it heavily uses slow-to-decompose, non-biodegradable synthetic fabrics like polyester and nylon. A key challenge to improving recycling is the absence of automated systems that can quickly and accurately identify different fabric types and their sustainability characteristics for large-scale sorting. 

💡 Solution :

This project proposes a Clothing Material Classification System using Convolutional Neural Networks (CNNs) — a deep learning model capable of recognizing and categorizing different clothing materials from images.

♦️ Expected output:

1. Identifies the Type of Cloth (e.g., Cotton, Polyester, Denim, Silk, etc.)
2. Detects if the Fabric is Mixed or Pure (e.g., Cotton + Polyester)
3. Displays Biodegradability Information (Yes/No)
4. Shows Estimated Time to Decompose in Soil
5. Indicates if the Material is Recyclable
6. Displays Model Accuracy using a Pie Chart
7. Performs Live Prediction — provides instant results for any input.

📃 Outcome:
Successfully completed the system design phase, finalized the project architecture, selected and prepared the dataset source, and planned the model training workflow for real-time fabric classification using ONNX and computer vision.

📂# week-2 - Implementation Phase Summary

🧩Implementation Overview: "Testing model was implemented".

✉️Dataset taken: "The Fabrics Dataset by iBUG" from kaggle.

🔍 Code Overview:
Section                     	Description
Imports & Setup	             Loads libraries like TensorFlow, OpenCV, PIL, Matplotlib, etc.
Dataset Paths                Uses train and validation folders (dataset_split/train,dataset_split/validation).
Data Checking                Verifies both folders contain the same fabric classes.
Data Augmentation	           Performs rescaling, shearing, zooming, flipping, etc.
Model	                       Builds a transfer learning model using MobileNetV2 (ImageNet weights).
Training	                    Uses ModelCheckpoint and EarlyStopping callbacks.
Evaluation	                  Displays validation accuracy and a pie chart.
Fabric Info	                 Stores eco-related info for each fabric (biodegradability, recyclability, etc.).
Prediction Functions	
Includes:                    *predict_image(model, img_path) for single image prediction.
                             *live_predict(model) for real-time webcam predictions.

📃 Outcome:
✅Achieved accurate fabric material classification using MobileNetV2.
✅Successfully distinguished between natural, synthetic, and blended fabrics.
✅Provided eco-impact insights like biodegradability, decomposition time, and recyclability.
✅Enabled both image-based and real-time webcam fabric predictions.
Demonstrated how AI can support sustainable fashion and material analysis.

📂# week-3 - Final Submission & Presentation Phase Summary

1.Completed the final version of the Real-Time Fabric Classification Dashboard
2.Integrated ONNX model, Gradio UI, and fabric biodegradability details
3.Added confidence visualization through pie-chart accuracy
4.Performed full testing with sample fabric images
5.Prepared final documentation, report, and presentation slides
6.Project ready for submission and demonstration

🏁 Outcome

The entire project — including the ONNX model, dashboard, documentation, and presentation — is fully completed and submitted.
The system successfully classifies various fabric types and provides biodegradability and recyclability information, demonstrating a practical real-world application of deep learning in sustainable textile management and smart recycling systems.
