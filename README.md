 Smart Health Prediction System (Web Version)

This is a basic Java web application that predicts possible illnesses based on user-input symptoms. It is designed as a beginner-friendly project to showcase understanding of web development using HTML, CSS, Java Servlets, and basic logic handling.

## Features
- Accepts comma-separated symptom input from the user
- Uses predefined rules to predict common illnesses
- Displays prediction result with a simple and clean UI
- Easy to extend or integrate with databases and APIs

## Technologies Used
- *Frontend*: HTML, CSS
- *Backend*: Java Servlets
- *Server*: Apache Tomcat
- *No database* used (logic-based prediction)

## How It Works
1. User accesses the main form at index.html.
2. Enters symptoms (e.g., fever, cough).
3. The form sends data to the HealthPredictServlet.
4. Servlet processes symptoms and returns a possible diagnosis.

## Example Predictions
- Input: fever, cough → Output: *Possible Flu or COVID-19*
- Input: headache, nausea → Output: *Possible Migraine*
- Input: cold → Output: *Unable to predict. Please enter more specific symptoms.*

## How to Run the Project
1. Download and unzip the project.
2. Open Eclipse (or any IDE supporting Dynamic Web Projects).
3. Import the project as a *Dynamic Web Project*.
4. Make sure Apache Tomcat is configured in your IDE.
5. Run the project on the server and open it in a browser.
