Predicting Mental Health Illness of Working Professionals Using Machine Learning

1.1 Overview
The contemporary professional landscape is rife with challenges that extend beyond traditional workplace dynamics. The advent of technology and globalization has ushered in a new era, transforming not only how we work but also how we perceive and manage mental health in professional settings. The acknowledgment of mental health as a fundamental component of overall well-being has gained unprecedented recognition. This project seeks to transcend conventional approaches by harnessing the power of advanced machine learning techniques to develop a predictive model uniquely tailored for working professionals.

The driving force behind this initiative lies in the recognition that the modern workplace, marked by relentless demands, high expectations, and intricate stressors, requires innovative solutions. The primary goal is not merely to identify potential mental health risks but to revolutionize the paradigm through which mental health is approached in professional settings. By meticulously analyzing a myriad of factors and intricate patterns, the model aspires to usher in a new era of proactive mental health management, enabling organizations to not only recognize individuals at risk but to implement preemptive measures for the overall well-being of their employees.

1.2 Purpose
The purpose of this project is multi-faceted, reflecting the intricate nature of mental health challenges in the workplace. Firstly, it acknowledges the pressing need to address mental health challenges proactively rather than reactively. The conventional approach of dealing with mental health issues after they manifest is no longer sufficient. This project seeks to construct a sophisticated machine learning tool that not only identifies individuals at risk but empowers organizations to implement preemptive measures, creating a paradigm shift towards a more holistic and proactive approach to mental health.

Secondly, the purpose extends beyond the immediate scope of this project. It aligns with a broader commitment to fostering a healthy and supportive work environment. The aim is to move away from the siloed discussions of mental health towards an integrated approach where mental well-being is considered an integral part of organizational success. This dual-purpose recognizes not only the urgency of addressing mental health issues but the potential of organizations to actively contribute to creating environments that promote overall well-being.

2. Literature Survey
2.1 Existing Problem
The contemporary workplace is a complex ecosystem with its unique set of challenges that pose formidable threats to mental health. High workloads, the looming specter of job insecurities, and the relentless pursuit of work-life balance contribute to the multifaceted stressors faced by working professionals. Existing methods for identifying mental health issues often rely on subjective self-reporting, introducing potential biases and inaccuracies into the assessment process.

Traditional surveys and assessments, while valuable, may not capture the nuanced and dynamic nature of mental health in a rapidly evolving work environment. The limitations of current methodologies underscore the need for a paradigm shift. Machine learning, with its ability to analyze vast datasets and identify intricate patterns, emerges as a potent tool for addressing these limitations and providing a more accurate and comprehensive assessment of mental well-being.

2.2 References
- Smith, A., Jones, B., & Doe, C. (20XX). "Workplace Stress and Mental Health: A Comprehensive Review." Journal of Occupational Health, 10(2), 123-145.
- Johnson, M., & Brown, S. (20XX). "Machine Learning Applications in Mental Health Prediction: A Systematic Review." Journal of Artificial Intelligence in Medicine, 15(4), 245-262.
- World Health Organization. (2019). "Mental Health in the Workplace: Information Sheet."
3.3 Problem Statement Definition
Despite heightened awareness surrounding mental health, a conspicuous gap remains in the availability of efficient tools for predicting and addressing mental health issues in the workplace. This project aims to bridge this gap by creating a reliable, data-driven approach to identify early signs of mental health issues in working professionals.

The significance of this problem statement lies not only in recognizing the prevalence of mental health challenges but in actively contributing to a healthier work environment through informed intervention. Traditional approaches to mental health management often rely on reactive measures, addressing issues after they have manifested. The proposed solution seeks to usher in a new era where mental health is proactively managed, creating a workplace environment that not only supports professional growth but also nurtures the mental well-being of its workforce.










3. Ideation & Proposed Solution
3.1 Empathy Map Canvas
An integral aspect of developing a solution for predicting mental health issues in working professionals is understanding the nuanced needs and concerns of individuals in a professional setting. To achieve this understanding, an empathy map canvas was meticulously constructed.
The empathy map delves into the intricate aspects of the professional experience, capturing not only the tangible challenges such as workload and job satisfaction but also the more intangible elements like the emotional impact of work-related stressors. By exploring the professional journey through the lens of empathy, the map serves as a foundational tool for ideation and solution development.


3.2 Ideation & Brainstorming
Brainstorming Ideas for Predicting Mental Health Illness of Working Professionals Using Machine Learning:
    1) Feature Engineering and Selection: Explore the dataset thoroughly and identify relevant features such as work hours, stress levels, job roles, job satisfaction scores, and any self-reported mental health indicators. Engage in feature engineering to create new meaningful features that might enhance the predictive power of the model. Use techniques like correlation analysis to select the most impactful features for the prediction task.

    2)  Sentiment Analysis on Open-Ended Responses: If your dataset includes open-ended responses from surveys or questionnaires, perform sentiment analysis on these responses. Extract sentiments and emotions expressed by professionals about their work environment, workload, and colleagues. Incorporate this sentiment analysis as a feature in your machine learning model.

    3) Temporal Analysis: Analyze the dataset over time to identify trends or patterns related to mental health. This could involve looking at how mental health indicators change over months or years, considering external factors such as work deadlines or major company events. Time-based patterns might provide valuable insights for prediction.

    4) Anomaly Detection: Implement anomaly detection techniques to identify unusual patterns or behaviors in the dataset. Unusual patterns might indicate periods of extreme stress or dissatisfaction, which could be early indicators of mental health issues. Anomaly detection models such as Isolation Forest or One-Class SVM can be valuable for this purpose.

    5) Ensemble Learning: Experiment with ensemble learning techniques like Random Forest, Gradient Boosting, or Stacking. Ensemble models often outperform individual models by combining predictions from multiple base models. Try different combinations of base models and ensemble methods to find the best-performing ensemble for your specific prediction task.

    6) Deep Learning Approaches: Consider using deep learning models such as recurrent neural networks (RNNs) or long short-term memory networks (LSTMs) if your dataset contains sequential or time-series data. These models can capture complex temporal dependencies and might improve prediction accuracy, especially if the dataset spans a considerable timeframe.



Idea Submission:
Based on the provided dataset, we propose the following idea:

Idea: Temporal Analysis and Anomaly Detection

We suggest conducting a detailed temporal analysis of the dataset to identify patterns related to mental health indicators over time. Simultaneously, implement anomaly detection techniques to pinpoint unusual or extreme behaviours or sentiments expressed by working professionals. By combining these analyses, we can build a predictive model that not only captures temporal trends but also detects early signs of mental health issues through anomalies. This approach offers a holistic view of the dataset, enabling us to create a robust and accurate machine learning model for predicting mental health illness among working professionals.






4. Requirement Analysis
4.1 Functional Requirement
The functionality of the predictive model extends beyond mere identification of potential mental health issues. The system is intricately designed to collect, process, and analyze multifaceted data related to both work-related and personal factors. The machine learning model then delivers precise predictions regarding the likelihood of mental health issues based on this comprehensive dataset. Functional requirements include seamless integration with existing organizational systems, real-time data processing capabilities, and an intuitive user interface for effortless interaction.

4.2 Non-Functional Requirements
The robustness of the system is fortified by a set of non-functional requirements. Data privacy is a paramount consideration, ensuring that sensitive information is handled with the utmost care and compliance with relevant regulations. User-friendliness is a key non-functional requirement, aiming to make the tool accessible and intuitive for users with varying levels of technical expertise. Real-time predictive capabilities form another crucial aspect, enabling organizations to respond promptly to potential mental health concerns.

5. Project Design
5.1 Data Flow Diagrams & User Stories
The design phase is marked by meticulous planning, involving the creation of detailed data flow diagrams illustrating the seamless flow of information from data collection to prediction. These diagrams serve as a visual representation of the system's architecture, ensuring clarity in understanding the intricate processes. Complementing this, user stories are crafted to capture the intricate interactions and expectations of end-users throughout the entire process. These user stories guide the development process, ensuring a user-centric design approach that aligns with the needs and expectations of those interacting with the system.




User Stories
User Type
Functional Requirement (Epic)
User Story Number
User Story/Task
Acceptance Criteria
Priority
Release
Customer
Registration
User 1
As a user, I can register for the application by entering my email, password, and confirming my password.
I can access my account/dashboard
High
Sprint - 1


User 2
As a user, I will receive confirmation email once I have registered for the application
I can receive confirmation
email & click confirm
High
Sprint - 1


User 3
As a user, I can register for the application using my Office credentials

Low
Sprint - 2

Login
User 4
As a user, I can log into the application by entering email & password

High
Sprint - 1

























5.2 Solution Architecture
Our solution optimizes mental health assessment for working professionals by harnessing machine learning algorithms. By leveraging comprehensive data and advanced modeling techniques, it enhances early detection and intervention, contributing to improved well-being and productivity.

    1. Data Collection and Gathering: Gather diverse data, including employment history and stress factors, to build a holistic dataset for analysis.

    2. Data Preprocessing and Feature Engineering: Cleanse and transform data, creating meaningful features essential for accurate mental health predictions.

    3. Model Selection and Building: Explore models like Logistic Regression, Random Forest, and Neural Networks, evaluating based on accuracy and reliability.

    4. Training and Validation: Split data, train models on one subset, and validate on another to ensure performance and avoid overfitting.

    5. Hyperparameter Tuning and Optimization: Fine-tune models through grid search, optimizing parameters for enhanced predictive power.

    6. Model Evaluation and Interpretability: Assess model performance, interpret predictions, and visualize key features for transparent decision-making.

    7. Real-time Prediction and Analysis: Deploy the model for real-time predictions, allowing professionals to input data and receive instant mental health assessments.

    8. Continuous Learning and Adaptation: Implement a feedback loop, updating the model with new data to ensure relevance and accuracy over time.

    9. Ethical Considerations and Privacy: Adhere to ethical guidelines, ensuring data privacy and obtaining informed consent from participants, respecting their confidentiality and well-being.

Solution Architecture Diagram: 



6. Project Planning & Scheduling
6.1 Technical Architecture
The technical architecture of the project is meticulously crafted, employing industry-standard tools and frameworks. Python serves as the primary programming language, offering versatility and an extensive ecosystem of libraries conducive to machine learning development. Flask is utilized for web application development, providing a lightweight and scalable framework. Scikit-learn, a powerful machine learning library, forms the backbone for the implementation of the predictive model. This strategic selection of technologies ensures a robust and efficient technical foundation for the project.

6.2 Sprint Planning & Estimation
To ensure a systematic and efficient development process, the project is divided into sprints, each addressing specific features or functionalities. Sprint planning involves a detailed analysis of the tasks to be accomplished in each sprint, with a focus on breaking down complex features into manageable subtasks. Time estimates for each sprint are meticulously calculated, taking into account the complexity of the tasks, dependencies, and the overarching goal of timely project completion. This iterative and incremental approach to development ensures flexibility in responding to evolving requirements and facilitates continuous improvement throughout the development lifecycle.




7. Coding & Solutioning
Table-1 : Components & Technologies: 
S.No 
Component 
Technology
1. 
User Interface 
HTML, CSS, Python
2. 
ML Model
Python (sklearn library)
3. 
Database 
CSV
4. 
Preprocessing
  Python (sklearn library)
5. 
Evaluation
Local Filesystem
  6. 
Infrastructure (Server / Cloud) 
Google Cloud.


8. Performance Testing
8.1 Performance Metrics
The performance testing phase evaluates the effectiveness and efficiency of the developed system. Performance metrics, such as accuracy, precision, recall, and F1 score, are used to assess the predictive capabilities of the machine learning model. Additionally, metrics related to system responsiveness, scalability, and data processing speed are considered to ensure optimal performance in real-world scenarios.

S.No.
Parameter
Values
Screenshot
    1. 
Metrics
Regression Model:
MAE-0.218666,
MSE-0.218666,
R2 score-0.125277













Classification Model:
Confusion Matrix-
50.72222,















Accuray Score-
0.7813333 & 







Classification Report-
0.80 
MAE,MSE,R2:



CONFUSION MATRIX:

ACCURACY SCORE:


CLASSIFICATION REPORT:

    2. 
Tune the Model
Hyperparameter Tuning - 
Validation Method - 

HYPERPARAMETER TUNING:


VALIDATION METHOD:






SCREENSHOTS:
MAE,MSE,R2:

CONFUSION MATRIX:

ACCURACY SCORE: 

CLASSIFICATION REPORT:

HYPERPARAMETER TUNING:


VALIDATION METHOD:




9. Results
9.1 Output Screenshots
The results section showcases the output and performance of the developed system. Screenshots of the user interface, visualizations of prediction outcomes, and relevant graphs depicting the model's accuracy over time are presented. This section provides a tangible representation of the project's outcomes and serves as a visual summary of the system's capabilities.

10. Advantages & Disadvantages
The advantages and disadvantages section critically evaluates the strengths and limitations of the developed solution. Advantages may include the proactive identification of mental health issues, real-time prediction capabilities, and user-friendly interfaces. On the flip side, potential disadvantages, such as the need for extensive data for accurate predictions or the challenge of interpreting complex machine learning models, are also explored. This balanced assessment provides stakeholders with a comprehensive understanding of the project's implications.

11. Conclusion
The conclusion summarizes the key findings, outcomes, and implications of the project. It reflects on how the developed solution contributes to the broader field of mental health management in professional settings. Additionally, the conclusion may touch upon the significance of adopting proactive approaches to mental health, the lessons learned during the project, and potential areas for further research and improvement.

12. Future Scope
The future scope section outlines potential avenues for expanding and enhancing the project. This could include refining the machine learning model based on additional data, incorporating feedback from users to improve user experience, or exploring partnerships with mental health professionals for a more comprehensive approach. The future scope provides a roadmap for the ongoing development and evolution of the project beyond its initial implementation.

13. Appendix
	- Source Code
Flask code
from flask import Flask, request, render_template
import pickle, joblib
import pandas as pd

app = Flask(__name__)

model = pickle.load(open("model.pkl", "rb"))
ct = joblib.load('feature_values')

@app.route('/')
def home():
    return render_template('home.html')

@app.route('/pred')
def predict():
    return render_template("index.html")

@app.route('/out', methods=["POST"])
def output():
    feature_cols = ['Age', 'Gender', 'self_employed', 'family_history',
                    'work_interfere', 'no_employees', 'remote_work', 'tech_company',
                    'benefits', 'care_options', 'wellness_program', 'seek_help',
                    'anonymity', 'leave', 'mental_health_consequence',
                    'phys_health_consequence', 'coworkers', 'supervisor',
                    'mental_health_interview', 'phys_health_interview',
                    'mental_vs_physical', 'obs_consequence']

    data = []
    for col in feature_cols:
        data.append(request.form.get(col, ''))

    pred = model.predict(ct.transform(pd.DataFrame([data], columns=feature_cols)))[0]
    if pred:
        return render_template("output.html", y="This person requires mental health treatment")
    else:
        return render_template("output.html", y="This person doesn't require mental health treatment")

if __name__ == '__main__':
    app.run(debug=True)

HTML CODES
    1) home.html
    2) <!DOCTYPE html>
    3) <html>
    4) <head>
    5)     <title>Mental health Predictor</title>
    6)     <style>
    7)         body {
    8)             font-family: Arial, sans-serif;
    9)             text-align: center;
    10)             background-color: #f2f2f2;
    11)             margin: 0;
    12)             padding: 0;
    13)         }
    14)         .container {
    15)             position: absolute;
    16)             top: 50%;
    17)             left: 50%;
    18)             transform: translate(-50%, -50%);
    19)         }
    20)         .description {
    21)             font-size: 18px;
    22)             margin-bottom: 20px;
    23)         }
    24)         .proceed-button {
    25)             padding: 10px 20px;
    26)             font-size: 16px;
    27)             background-color: #333;
    28)             color: white;
    29)             border: none;
    30)             cursor: pointer;
    31)         }
    32)     </style>
    33) </head>
    34) <body>
    35)     <div class="container">
    36)         <h1>Welcome to Mental Health Predictor</h1>
    37)         <div class="description">
    38)             <p>Creating a supportive workplace environment is crucial for maintaining good mental health among employees. Encouraging open conversations, providing mental health resources, and ensuring a healthy work-life balance are key factors.</p>
    39)         </div>
    40)         <form action="/pred" method="get">
    41)             <input class="proceed-button" type="submit" value="Proceed">
    42)         </form>
    43)     </div>
    44) </body>
    45) </html>
    46) 


2) index.html
<!DOCTYPE html>
<html>
<head>
    <title>Mental Health Prediction</title>
</head>
<body>
    <h1>Mental Health Prediction</h1>
    <form action="/out" method="post">
        <label for="Age">Age:</label>
        <input type="text" id="Age" name="Age"><br><br>

        <label for="Gender">Gender:</label>
        <select id="Gender" name="Gender">
            <option value="Male">Male</option>
            <option value="Female">Female</option>
            <option value="Other">Other</option>
        </select><br><br>

        <label for="self_employed">Are you self-employed?</label>
        <select id="self_employed" name="self_employed">
            <option value="Yes">Yes</option>
            <option value="No">No</option>
        </select><br><br>

        <label for="family_history">Family history of mental health issues?</label>
        <select id="family_history" name="family_history">
            <option value="Yes">Yes</option>
            <option value="No">No</option>
        </select><br><br>

        <label for="work_interfere">Does work interfere with mental health?</label>
        <select id="work_interfere" name="work_interfere">
            <option value="Often">Often</option>
            <option value="Rarely">Rarely</option>
            <option value="Never">Never</option>
            <option value="Sometimes">Sometimes</option>
        </select><br><br>

        <label for="no_employees">Number of employees in your company:</label>
        <select id="no_employees" name="no_employees">
            <option value="1-5">1-5</option>
            <option value="6-25">6-25</option>
            <option value="26-100">26-100</option>
            <option value="100-500">100-500</option>
            <option value="More than 500">More than 500</option>
        </select><br><br>

        <label for="remote_work">Is your work primarily remote?</label>
        <select id="remote_work" name="remote_work">
            <option value="Yes">Yes</option>
            <option value="No">No</option>
        </select><br><br>

        <label for="tech_company">Is it a tech company?</label>
        <select id="tech_company" name="tech_company">
            <option value="Yes">Yes</option>
            <option value="No">No</option>
        </select><br><br>

        <label for="benefits">Do you receive benefits?</label>
        <select id="benefits" name="benefits">
            <option value="Yes">Yes</option>
            <option value="No">No</option>
        </select><br><br>

        <label for="care_options">Do you have care options?</label>
        <select id="care_options" name="care_options">
            <option value="Yes">Yes</option>
            <option value="No">No</option>
        </select><br><br>

        <label for="wellness_program">Is there a wellness program?</label>
        <select id="wellness_program" name="wellness_program">
            <option value="Yes">Yes</option>
            <option value="No">No</option>
        </select><br><br>

        <label for="seek_help">Do you seek help for mental health issues?</label>
        <select id="seek_help" name="seek_help">
            <option value="Yes">Yes</option>
            <option value="No">No</option>
        </select><br><br>

        <label for="anonymity">Do you prefer anonymity?</label>
        <select id="anonymity" name="anonymity">
            <option value="Yes">Yes</option>
            <option value="No">No</option>
        </select><br><br> <label for="leave">How flexible is your leave?</label>
        <select id="leave" name="leave">
            <option value="Somewhat easy">Somewhat easy</option>
            <option value="Very easy">Very easy</option>
            <option value="Somewhat difficult">Somewhat difficult</option>
            <option value="Very difficult">Very difficult</option>
            <option value="Don't know">Don't know</option>
        </select><br><br>

        <label for="mental_health_consequence">Does mental health affect work?</label>
        <select id="mental_health_consequence" name="mental_health_consequence">
            <option value="Yes">Yes</option>
            <option value="No">No</option>
            <option value="Maybe">Maybe</option>
        </select><br><br>

        <label for="phys_health_consequence">Does physical health affect work?</label>
        <select id="phys_health_consequence" name="phys_health_consequence">
            <option value="Yes">Yes</option>
            <option value="No">No</option>
            <option value="Maybe">Maybe</option>
        </select><br><br>

        <label for="coworkers">Would you discuss with coworkers?</label>
        <select id="coworkers" name="coworkers">
            <option value="Yes">Yes</option>
            <option value="No">No</option>
            <option value="Some of them">Some of them</option>
        </select><br><br>

        <label for="supervisor">Would you discuss with a supervisor?</label>
        <select id="supervisor" name="supervisor">
            <option value="Yes">Yes</option>
            <option value="No">No</option>
            <option value="Some of them">Some of them</option>
        </select><br><br>

        <label for="mental_health_interview">Would you discuss in a job interview?</label>
        <select id="mental_health_interview" name="mental_health_interview">
            <option value="Yes">Yes</option>
            <option value="No">No</option>
            <option value="Maybe">Maybe</option>
        </select><br><br>

        <label for="phys_health_interview">Would you discuss physical health in a job interview?</label>
        <select id="phys_health_interview" name="phys_health_interview">
            <option value="Yes">Yes</option>
            <option value="No">No</option>
            <option value="Maybe">Maybe</option>
        </select><br><br>

        <label for="mental_vs_physical">Do you think mental and physical health are equally important?</label>
        <select id="mental_vs_physical" name="mental_vs_physical">
            <option value="Yes">Yes</option>
            <option value="No">No</option>
            <option value="Don't know">Don't know</option>
        </select><br><br>

        <label for="obs_consequence">Do you think there could be any negative consequences?</label>
        <select id="obs_consequence" name="obs_consequence">
            <option value="Yes">Yes</option>
            <option value="No">No</option>
            <option value="Maybe">Maybe</option>
        </select><br><br>

        <input type="submit" value="Submit">
    </form>
</body>
</html>

3) output.html
<!DOCTYPE html>
<html>
<head>
    <title>Result</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
        }
        .container {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }
        .output-message {
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 30px;
        }
        .button-group {
            display: flex;
            justify-content: center;
        }
        .button {
            margin: 0 10px;
            padding: 10px 20px;
            font-size: 16px;
            background-color: #333;
            color: white;
            border: none;
            cursor: pointer;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="output-message">
            {% if y %}
                {{ y }}
            {% endif %}
        </div>
        <div class="button-group">
            <a class="button" href="/">Home</a>
            <a class="button" href="/pred">Predict</a>
        </div>
    </div>
</body>
</html>

		
- Github and project demo link
https://github.com/smartinternz02/SI-GuidedProject-597115-1697564774
