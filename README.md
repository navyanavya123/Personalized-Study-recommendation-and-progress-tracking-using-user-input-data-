PERSONALIZED STUDY RECOMMENDATION AND PROGRESS TRACKING SYSTEM USING USER INPUT DATA

📌 PROJECT OVERVIEW  
This project is designed to help students by offering personalized study material recommendations and tracking their academic progress. The system collects user input on quiz scores across multiple subjects and generates useful study suggestions, a weekly timetable, and performance feedback. Additionally, it visualizes student performance through bar graphs, helping to identify areas of strength and improvement.

🚀 FEATURES  
- User input for subjects and quiz scores: Users can input their subjects and corresponding quiz scores, allowing for customized suggestions and feedback.  
- Study material recommendation: Provides book recommendations, online resources, and YouTube videos based on subject performance.  
- Weekly study timetable: Automatically generates a personalized weekly study schedule based on the user's quiz scores.  
- Performance feedback: The system offers feedback for each subject, encouraging improvement in weaker areas and acknowledging strengths.  
- Performance visualization: Displays a bar graph to visualize the student's scores in different subjects, aiding in better understanding of performance trends.

🔧 TECH STACK  
- Python  
- Pandas (for data handling)  
- Matplotlib (for data visualization)

📂 DATASET  
The dataset includes the following information for each subject:  
- subject: Name of the subject (e.g., Maths, Science, etc.)  
- book_names: Available books for each subject  
- study_material_link: Links to online study resources for the subject  
- youtube_links: YouTube video links related to the subject

🛠️ SETUP AND INSTALLATION  
To run the system, follow the steps below:
1. Clone the repository  
   git clone <repository_link>  
   cd personalized-study-recommendation

2. Install required libraries  
   pip install pandas matplotlib

3. Run the program  
   python personalized_study_recommendation.py

🧠 HOW THE SYSTEM WORKS  
1. The user enters the subjects and their respective quiz scores.  
2. The system provides recommendations for study materials and generates a weekly study timetable based on performance.  
3. Feedback is given for each subject based on the score (below 50: needs improvement, below 75: good progress, above 75: excellent).  
4. A bar graph is displayed showing performance across all subjects.

🎯 EXPECTED OUTCOMES  
- Personalized study material recommendations tailored to the student's weakest subject.  
- A structured weekly timetable to organize study efforts effectively.  
- Constructive feedback to help improve in specific areas.  
- A clear graphical representation of the student’s performance.

📌 FUTURE ENHANCEMENTS  
- Add predictive analysis using past scores to predict future performance.  
- Extend the system to integrate with learning management systems (LMS) for seamless study tracking.  
- Implement machine learning to suggest more dynamic learning paths based on quiz results over time.

🤝 CONTRIBUTING  
We welcome contributions to enhance the system. Please fork the repository, make improvements, and submit a pull request.

📜 LICENSE  
This project is licensed under the MIT License — feel free to use and extend it.
