# SMS Spam Detector 
### **Project Overview**  
This project builds a **machine learning model** to classify SMS messages as **spam or ham** using **TF-IDF vectorization** and **LinearSVC**. The dataset, **“SMSSpamCollection,”** provides labeled messages for training. After preprocessing, a **pipeline** integrates **TF-IDF** with **LinearSVC** to efficiently classify messages. A **Gradio interface** allows users to input SMS messages and get real-time predictions.  

### **🔹 Functionality**  
- **Data Processing:** `pandas` for data handling, `train_test_split` for splitting, and `TfidfVectorizer` for text-to-numeric conversion.  
- **Model Training:** `Pipeline` streamlines TF-IDF transformation & classification using `LinearSVC`.  
- **Deployment:** `gradio` enables an easy-to-use web interface for message classification.  

### **🔹 Real-World Applications**  
✔ **Customer Support** – Filters spam to improve response times.  
✔ **Email Spam Detection** – Prevents spam from cluttering inboxes.  
✔ **Social Media Monitoring** – Identifies and removes spam content.  

### **🔹 Key Takeaways**  
1️⃣ **TF-IDF is crucial** for extracting meaningful text features.  
2️⃣ **LinearSVC** is **fast and effective** for text classification.  
3️⃣ **Gradio** makes it easy for non-technical users to have access to the model quickly and effectively with no complicated deployment system 

### **Conclusion**  
This project showcases **end-to-end SMS spam detection** with **TF-IDF & LinearSVC**, highlighting **feature engineering’s role** in text classification. The **Gradio interface** makes it **user-friendly**, demonstrating how machine learning can be applied in real-world scenarios. 🚀
