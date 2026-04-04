🧠 Brain Tumor Classification (Deep Learning)

🚀 End-to-end Deep Learning pipeline for brain tumor detection and classification from MRI scans, built using CNN architectures with a focus on real-world healthcare applications.



📌 Project Highlights

🧠 Built a Convolutional Neural Network (CNN) for multi-class brain tumor classification
📊 Designed a complete ML pipeline: preprocessing → training → evaluation → prediction
⚡ Achieved strong performance on validation data (high accuracy & stable loss trends)
🧩 Structured for scalability & deployment (ready for Streamlit/Flask integration)
🔍 Demonstrates practical understanding of medical imaging + deep learning workflows
🛠️ Tech Stack
    Category	Tools & Libraries
    Language	Python
    Deep Learning	TensorFlow, Keras
    Data Processing	NumPy, OpenCV
    Visualization	Matplotlib
    Environment	Jupyter Notebook



🧠 Problem Statement

    Brain tumors are life-threatening conditions requiring early and accurate diagnosis. Manual MRI analysis is time-consuming and prone to human error.

👉 This project leverages deep learning to automate tumor detection and classification, assisting medical professionals with faster and more consistent analysis.



📊 Dataset

    MRI images categorized into:
    Glioma Tumor
    Meningioma Tumor
    Pituitary Tumor
    No Tumor
    Includes diverse image variations:
    Different tumor sizes & shapes
    Varying intensity and noise levels



⚙️ Model Architecture

    The model is a custom CNN designed for image classification:

    Convolution Layers → Feature extraction
    MaxPooling → Dimensionality reduction
    Fully Connected Layers → Classification
    Softmax Activation → Multi-class prediction

🔁 Easily extendable to Transfer Learning (ResNet, VGG, EfficientNet)



🚀 End-to-End Workflow
    Key Steps:
        Image resizing & normalization
        Label encoding
        Model training with validation
        Performance evaluation using accuracy & loss curves
        📈 Results & Performance
        ✅ High classification accuracy on validation dataset
        📉 Stable training & validation loss (low overfitting)
        🎯 Strong generalization on unseen MRI images

 92% Accuracy obatained using PyTorch through Fine-Tuned ResNet50 Model
 89% Accuracy obatained using TensorFlow through ResNet50 Model


🧪 How to Run
    # Clone the repository
    git clone https://github.com/Learningsabd/Brain-Tumor-Classification.git

    # Navigate into the project
    cd Brain-Tumor-Classification

    # Install dependencies
    pip install -r requirements.txt

    # Run Jupyter Notebook
    jupyter notebook
    🖼️ Sample Prediction Flow
    Input MRI Image
        Model processes image
    Output:
        Tumor Type OR
        No Tumor


🔥 Key Learnings
    Practical implementation of CNNs for image classification
    Handling real-world medical image datasets
    Avoiding overfitting with proper validation strategies
    Building modular and reusable ML pipelines
    🔮 Future Improvements
    🚀 Implement Transfer Learning (ResNet50, EfficientNet)
    🌐 Deploy as a web application (Streamlit / Flask)
    🧠 Add Explainable AI (Grad-CAM visualization)
    📦 Convert to production-ready API
    📊 Improve dataset size for better generalization
    ⚠️ Disclaimer

This project is intended for educational purposes only and should not be used for real medical diagnosis.

🤝 Let's Connect

    If you're interested in AI, Deep Learning, or Healthcare Tech, feel free to connect or collaborate!

⭐ Why This Project Stands Out

    ✔ Real-world problem (Healthcare AI)
    ✔ End-to-end implementation
    ✔ Strong foundation for deployment
    ✔ Demonstrates practical ML engineering skills