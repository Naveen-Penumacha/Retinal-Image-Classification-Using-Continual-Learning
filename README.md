# 🧿 Retinal Image Classification Using Continual Learning
📖 Introduction
Retinal image classification plays a pivotal role in the early diagnosis and treatment of sight-threatening diseases such as diabetic retinopathy, age-related macular degeneration, and glaucoma. Accurate detection at an early stage can prevent vision loss and significantly improve patient outcomes.

However, traditional machine learning models struggle to adapt when new data becomes available. Retraining these models frequently leads to catastrophic forgetting, where previously learned knowledge is lost. To overcome this, our project implements a robust continual learning framework that incrementally learns from new data while retaining previously acquired knowledge.

🎯 Objective

Develop an intelligent retinal image classification system capable of learning continuously from evolving data.

Minimize the risk of catastrophic forgetting using advanced continual learning algorithms.

Maintain high classification accuracy as new retinal images and disease patterns emerge.

Offer a practical solution for real-world, dynamic medical imaging scenarios.

🧩 Key Features

✨ Continual Learning:
Employs techniques such as Experience Replay and regularization-based methods to maintain performance on old tasks while learning new ones.

🔄 Incremental Updates:
Enables the model to adapt to new patient data without full retraining.

📊 Benchmark Validation:
Validated on well-known retinal image datasets to ensure reliability and reproducibility.

💡 Modular Design:
Clean, modular code structure to experiment with various continual learning strategies.

📈 Performance Tracking:
Logs training metrics, loss curves, and accuracy for each task.
