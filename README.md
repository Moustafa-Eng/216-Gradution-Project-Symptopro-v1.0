# 216-Gradution-Project-Symptopro-v1.0
## 💡 Features – SymptoPro

- 🔐 **Authentication & Role-Based Access Control**  
  Secure login system with role differentiation:  
  - 👤 **User**: Can report symptoms and receive predictions.  
  - 🧑‍⚕️ **Doctor**: Can view patient predictions and offer feedback.  
  - 🛠️ **Admin**: Full access to manage users, doctors, and system configurations.

- 🩺 **Disease Prediction Based on Symptoms**  
  Utilizes machine learning and deep learning models (served as microservices) to predict possible diseases based on user-reported symptoms.

- 👨‍⚕️ **Doctor Recommendation Engine**  
  Suggests a specialized doctor based on the predicted condition to help the user connect with the right medical expert.

- 🧪 **CBC Report Analysis**  
  Users can upload their CBC blood test results as a file. The system analyzes the report using AI to:  
  - Extract and interpret the values.  
  - Identify any abnormal readings.  
  - Provide explanations for non-normal values.

- ⚙️ **Microservices Architecture**  
  All AI/ML functionalities are decoupled and deployed as independent microservices for better scalability and maintainability.

- 🎨 **Frontend Built with Angular**  
  A responsive and modern UI built using Angular, ensuring a smooth experience across desktop and mobile devices.
