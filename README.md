# Personal-Fitness-Tracker
Personal Fitness Tracker
Overview
The Personal Fitness Tracker is a machine learning-based web application that predicts the number of calories burned based on user-specific inputs such as age, BMI, exercise duration, heart rate, body temperature, and gender. Built using Python, Streamlit, and Scikit-Learn, this project helps individuals monitor their fitness levels and optimize their workouts.

Features
✅ Predicts Calories Burned using a trained Random Forest Regressor model.
✅ User-friendly Web Interface built with Streamlit for easy input and instant predictions.
✅ Data Visualization (Histograms, percentile comparisons) to help users understand their fitness metrics.
✅ Optimized Performance using caching and parallel processing for faster predictions.
✅ Similar Results Feature to find individuals with matching workout patterns.

Technologies Used
Python (Primary programming language)
Streamlit (For web application interface)
Scikit-Learn (Machine learning model)
Pandas & NumPy (Data manipulation)
Matplotlib & Seaborn (Data visualization)
Installation Guide
Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/Personal-Fitness-Tracker.git
cd Personal-Fitness-Tracker
Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
Run the Application
bash
Copy
Edit
streamlit run app.py
Usage
Open the Streamlit app in your browser.
Input your details (Age, BMI, Exercise Duration, Heart Rate, Body Temperature, Gender).
Click Predict to see the estimated calories burned.
View similar results and compare your fitness stats with others.
Dataset
The dataset used consists of real-world fitness records, combining exercise and calorie data. It is preprocessed to include essential features like BMI calculation and gender encoding.

Future Enhancements
🔹 Integration with wearable devices for real-time tracking.
🔹 Incorporating deep learning models for improved predictions.
🔹 Adding dietary recommendations based on activity levels.

Contributors
👨‍💻 [Your Name] - Developer
👩‍🏫 Prof. Saomya Chaudhary - Supervisor

License
This project is licensed under the MIT License.
